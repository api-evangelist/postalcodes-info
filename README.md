# PostalCodes.info

Postal-code lookup, search, country exports, and address validation worldwide. PostalCodes.info publishes a same-origin reference API and bulk CSV / JSON / XLSX downloads for 123+ countries, anchored on GeoNames and national open-data feeds, released under the Open Database License (ODbL) 1.0.

- **Provider:** PostalCodes.info (Global Postal Code Repository)
- **Maintainer:** Pablo Cirre — `social@genera.work`
- **Homepage:** https://postalcodes.info/
- **API documentation:** https://postalcodes.info/api
- **Dataset documentation:** https://postalcodes.info/datasets
- **OpenAPI (live):** https://postalcodes.info/openapi.json
- **License:** [Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/)
- **Source apis.json:** https://raw.githubusercontent.com/PabloCirre/postalcodes-info-open-data/main/apis.json
- **Upstream repo:** https://github.com/PabloCirre/postalcodes-info-open-data
- **api-search issue:** [api-search/network#22](https://github.com/api-search/network/issues/22)

## Coverage

- 123+ countries and territories
- ~1,827,156 postal records (~1,080,895 distinct postal codes; ~888k mapped localities)
- ~99.2% geocoding coverage (WGS84 locality centroids, not delivery-point coordinates)
- Annual master snapshot (e.g., `2026.1`) plus weekly minor refreshes; corrections within 48–72 business hours after verification

## API Surface

Canonical host: `https://postalcodes.info`

| Operation | Method | Path | Tag |
|---|---|---|---|
| Search Postal Codes, Places or Countries | GET | `/search` | Search |
| Preview Records for One Country | GET | `/ajax-preview` | Search |
| Mint a Same-Origin Download Token | GET | `/download-token.php` | Downloads |
| Download a Country Dataset | GET | `/download.php` | Downloads |
| Open a Country Postal-Code Reference Page | GET | `/postal-codes/{country}` | Lookup Pages |

Reads are public and unauthenticated. Country downloads require a short-lived same-origin token (browser flow with `Referer` and `X-Requested-With: XMLHttpRequest`).

## Profiling Artifacts

This repository is the API Evangelist Network profile of PostalCodes.info. Generated artifacts live alongside the `apis.yml` index.

| Folder | Contents |
|---|---|
| `openapi/` | OpenAPI 3.1 spec sourced from `https://postalcodes.info/openapi.json` and saved as YAML |
| `capabilities/` | Naftiko per-API capability plus `postal-data-lookup` and `country-dataset-export` workflow compositions |
| `rules/` | Spectral ruleset enforcing PostalCodes.info conventions (postal codes as strings, ODbL license, same-origin download flow, sanctioned tags) |
| `json-schema/` | JSON Schemas for `PostalRecord`, `SearchSuggestion`, and `Error` |
| `json-structure/` | Tabular `PostalRecord` structure for CSV / XLSX / JSON exports |
| `json-ld/` | JSON-LD context mapping records to schema.org, WGS84 geo, ISO country codes, and DCAT |
| `examples/` | Per-operation request/response pairs and entity-level samples |
| `vocabulary/` | Operational and capability vocabulary across postal codes, geocoding, admin hierarchy, datasets, lookups, and governance |
| `plans/` | API Commons Plans 0.1 document (`reconciled: false` — ODbL public access; no paid tier) |
| `rate-limits/` | API Commons Rate Limits 0.1 document (`reconciled: false` — no numeric quota published; same-origin token controls described) |
| `finops/` | FinOps / FOCUS-aligned consumer-side cost view (no provider billing surface exists) |

## Use Cases

- E-commerce address validation and autocomplete
- Logistics zone normalization and carrier routing tables
- Master data quality and locality enrichment in CRM / CDP / ERP
- Citation-grade postal corpora for research and benchmarking (Zenodo DOIs available)

## Licensing & Attribution

Data is distributed under the **Open Database License (ODbL) 1.0**. Commercial reuse is permitted with attribution and reciprocal licensing of derivatives. Suggested attribution:

> Contains information from the Global Postal Code Repository (postalcodes.info), available under the Open Database License (ODbL).

Selling raw datasets as standalone products is prohibited, as is automated retrieval that violates `robots.txt` or institutional headers.

## Citation

- Dataset DOI: https://zenodo.org/records/19493709
- Methodology note: https://zenodo.org/records/19930578
- Coverage benchmark: https://zenodo.org/records/19930688

## Upstream Data Sources

- [GeoNames](https://www.geonames.org/) — place, admin hierarchy, WGS84 coordinates
- [Saudi Post (SPL)](https://splonline.com.sa/) — Saudi Arabia open-data postal workbooks
- Kazakhstan National Open-Government Postal Index
- Oracle Cloud — hosting infrastructure
