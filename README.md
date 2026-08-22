# PostalCodes.info (postalcodes-info)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Postal-code lookup, search, country exports, and address validation worldwide. PostalCodes.info publishes a same-origin reference API and bulk CSV / JSON / XLSX downloads for 123+ countries, anchored on GeoNames and national open-data feeds, released under the Open Database License (ODbL) 1.0.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/postalcodes-info/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/postalcodes-info/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Postal Codes
- Geocoding
- Open Data
- Address Validation
- Logistics

## Timestamps

- **Created:** 2026-05-16
- **Modified:** 2026-05-19

## APIs

### PostalCodes.info Postal Code Reference API

Same-origin postal-code search, country export, and lookup-page endpoints used by the public PostalCodes.info UI. Coverage spans 123+ countries with approximately 1.83M postal records and 99.2% geocoding coverage on locality centroids. Designed for lookup, testing, education, geospatial examples, and data-quality workflows. Not a delivery-grade postal authority API.

- **Human URL:** [https://postalcodes.info/api](https://postalcodes.info/api)
- **Base URL:** `https://postalcodes.info`

#### Tags

- Postal Codes
- Geocoding
- Open Data
- Address Validation
- Logistics

#### Properties

- [Documentation](https://postalcodes.info/api)
- [OpenAPI](https://postalcodes.info/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/postalcodes-info-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/postalcodes-info.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/postalcodes-info.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Dataset  Documentation](https://postalcodes.info/datasets)
- [License](https://opendatacommons.org/licenses/odbl/1-0/)
- [License](https://postalcodes.info/licensing)
- [Terms of Service](https://postalcodes.info/terms)
- [Privacy Policy](https://postalcodes.info/privacy)
- [Update Policy](https://postalcodes.info/update-policy)
- [Data Sources](https://postalcodes.info/data-sources)
- [Citation](https://zenodo.org/records/19493709)
- [A P Is J S O N](https://raw.githubusercontent.com/PabloCirre/postalcodes-info-open-data/main/apis.json)
- [Git Hub](https://github.com/PabloCirre/postalcodes-info-open-data)
- [Spectral Rules](rules/postalcodes-info-rules.yml)
- [Plans](plans/postalcodes-info-plans-pricing.yml)
- [Rate Limits](rate-limits/postalcodes-info-rate-limits.yml)
- [Fin Ops](finops/postalcodes-info-finops.yml)
- [Vocabulary](vocabulary/postalcodes-info-vocabulary.yml)
- [JSON-LD](json-ld/postalcodes-info-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/postalcodes-info-postal-record-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/postalcodes-info-search-suggestion-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/postalcodes-info-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/postalcodes-info-postal-record-structure.json)
- [Example](examples/postalcodes-info-search-postal-codes-example.json)
- [Example](examples/postalcodes-info-preview-country-records-example.json)
- [Example](examples/postalcodes-info-create-download-token-example.json)
- [Example](examples/postalcodes-info-download-country-dataset-example.json)
- [Example](examples/postalcodes-info-get-country-lookup-page-example.json)
- [Example](examples/postalcodes-info-postal-record-example.json)
- [Example](examples/postalcodes-info-search-suggestion-example.json)

## Common Properties

- [Website](https://postalcodes.info/)
- [Documentation](https://postalcodes.info/api)
- [Dataset  Documentation](https://postalcodes.info/datasets)
- [OpenAPI](https://postalcodes.info/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [License](https://postalcodes.info/licensing)
- [License](https://opendatacommons.org/licenses/odbl/1-0/)
- [Terms of Service](https://postalcodes.info/terms)
- [Privacy Policy](https://postalcodes.info/privacy)
- [Contact](https://postalcodes.info/contact)
- [Data Sources](https://postalcodes.info/data-sources)
- [Update Policy](https://postalcodes.info/update-policy)
- [A P Is J S O N](https://raw.githubusercontent.com/PabloCirre/postalcodes-info-open-data/main/apis.json)
- [Git Hub](https://github.com/PabloCirre/postalcodes-info-open-data)
- [Citation](https://zenodo.org/records/19493709)
- [Methodology Note](https://zenodo.org/records/19930578)
- [Coverage Benchmark](https://zenodo.org/records/19930688)

## Maintainers

**FN:** Pablo Cirre, PostalCodes.info
**Email:** social@genera.work
**URL:** https://postalcodes.info/contact
