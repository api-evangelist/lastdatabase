---
name: lastdatabase-search-leads
description: Search LastDatabase email, phone or fax lead inventory by country, city, industry or keyword with a Bearer API key, respecting the per-request cap and the plan's daily limit.
api: lastdatabase:lead-search-api
operations:
- searchLeads
generated: '2026-09-23'
method: generated
source: openapi/lastdatabase-openapi.yml
---

# Search LastDatabase leads

1. Authenticate every request with `Authorization: Bearer <API key>` (key created in the customer API Keys area; keep it server-side).
2. Call `searchLeads` — `GET https://lastdatabase.com/api/leads/search` — with any of `type` (`email` default, `phone`, `fax`), `country`, `city`, `industry`, `keyword` (matches country, city, industry or company name) and `limit` (default 25, capped at 100).
3. Read `status`, `type`, `count` and the `data` array. Record fields depend on the lead type and source record: treat every field as optional and handle an empty `data` array.
4. On `401`, the token is missing or invalid — stop and fix the key. On `429` ("Daily API limit exceeded."), the plan's daily quota (100 / 10,000 / 100,000 requests per key per day) is spent: do not retry until the usage period resets.
5. The call is read-only, so it is safe to repeat; there is no pagination cursor, so narrow filters instead of paging.
6. Contact data carries legal obligations: the customer is responsible for consent and communications rules (see https://lastdatabase.com/compliance).
