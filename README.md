# DiscGolfAPI (discgolfapi)

DiscGolfAPI is a free, read-only public API that publishes structured JSON data about disc golf courses — for developers, clubs, publishers, apps, and AI systems. It provides machine-readable course records with names, locations, countries, regions, hole counts where known, coordinates where available, operational and access fields, confidence and verification signals, update timestamps, and attribution/licence metadata. DiscGolfAPI is infrastructure and reference data — not a review site, rating platform, or social network.

**URL:** [https://discgolfapi.com/](https://discgolfapi.com/)

## Tags

- Disc Golf, Sports, Courses, Open Data, Recreation

## APIs

### DiscGolfAPI REST API

Read-only structured disc golf course data for apps, maps, directories, websites, and developer tools. Provides course listings filtered by country and region with pagination, course detail by stable public ID, country and region coverage indexes, recent update feed, and the public dataset manifest with content-addressable artefacts. Public endpoints do not require an API key. Use is subject to the DiscGolfAPI licence which requires visible attribution.

**Human URL:** [https://discgolfapi.com/](https://discgolfapi.com/)
**Base URL:** `https://io.discgolfapi.com/v1`

#### Tags

- Courses, Countries, Regions, Updates, Metadata, Disc Golf, Open Data

#### Properties

- [Documentation](https://discgolfapi.com/docs/)
- [OpenAPI (local)](openapi/discgolfapi-openapi.yml)
- [OpenAPI (canonical)](https://discgolfapi.com/openapi.json)
- [APIs.json](https://discgolfapi.com/apis.json)
- [Terms of Service](https://discgolfapi.com/terms/)
- [License](https://discgolfapi.com/licence/)
- [Contact](https://discgolfapi.com/contact/)
- [llms.txt](https://discgolfapi.com/llms.txt)
- [robots.txt](https://discgolfapi.com/robots.txt)
- [Manifest](https://io.discgolfapi.com/manifest.json)
- [Schema](https://discgolfapi.com/schema/)
- [Coverage](https://discgolfapi.com/coverage/)
- [Changelog](https://discgolfapi.com/changelog/)

## Artifacts

### OpenAPI

| File | Description |
|---|---|
| [openapi/discgolfapi-openapi.yml](openapi/discgolfapi-openapi.yml) | DiscGolfAPI REST API — course list, course detail, country and region coverage indexes, recent updates feed, and dataset manifest |

### Rules

| File | Description |
|---|---|
| [rules/discgolfapi-rules.yml](rules/discgolfapi-rules.yml) | Spectral ruleset enforcing DiscGolfAPI conventions: Title Case summaries, documented 429/500 responses, stable ID pattern, attribution envelope, licence + contact requirements |

### Capabilities

| File | Description |
|---|---|
| [capabilities/disc-golf-courses.yaml](capabilities/disc-golf-courses.yaml) | Unified disc golf course data workflow capability exposing both REST and MCP surfaces |
| [capabilities/shared/discgolfapi.yaml](capabilities/shared/discgolfapi.yaml) | Shared DiscGolfAPI HTTP API consumption definitions |

### JSON Schema

| File | Description |
|---|---|
| [json-schema/discgolfapi-course-schema.json](json-schema/discgolfapi-course-schema.json) | JSON Schema for the public Course resource including the PrimaryLayout substructure |
| [json-schema/discgolfapi-manifest-schema.json](json-schema/discgolfapi-manifest-schema.json) | JSON Schema for the dataset manifest with counts and content-addressable artefact metadata |

### JSON Structure

| File | Description |
|---|---|
| [json-structure/discgolfapi-course-structure.json](json-structure/discgolfapi-course-structure.json) | Field-level structural documentation for the Course and PrimaryLayout shapes |

### JSON-LD

| File | Description |
|---|---|
| [json-ld/discgolfapi-context.jsonld](json-ld/discgolfapi-context.jsonld) | JSON-LD context aligning DiscGolfAPI fields with schema.org, geo, dcat, and dct |

### Examples

| File | Description |
|---|---|
| [examples/discgolfapi-list-courses-example.json](examples/discgolfapi-list-courses-example.json) | Example: list courses in Great Britain with envelope, attribution, and pagination |
| [examples/discgolfapi-get-course-example.json](examples/discgolfapi-get-course-example.json) | Example: get a single course by stable public ID |
| [examples/discgolfapi-manifest-example.json](examples/discgolfapi-manifest-example.json) | Example: dataset manifest with counts and content-addressable artefacts |

### Vocabulary

| File | Description |
|---|---|
| [vocabulary/discgolfapi-vocabulary.yml](vocabulary/discgolfapi-vocabulary.yml) | DiscGolfAPI domain vocabulary covering courses, layouts, coverage, manifest, confidence, and attribution concepts |

### Plans

| File | Description |
|---|---|
| [plans/discgolfapi-plans-pricing.yml](plans/discgolfapi-plans-pricing.yml) | API Commons Plans definition — free public read-only tier + commercial enquiry channel (`reconciled: false`) |

### Rate Limits

| File | Description |
|---|---|
| [rate-limits/discgolfapi-rate-limits.yml](rate-limits/discgolfapi-rate-limits.yml) | API Commons Rate Limits definition — documented 429/503 signalling and fair-use policy (`reconciled: false`) |

### FinOps

| File | Description |
|---|---|
| [finops/discgolfapi-finops.yml](finops/discgolfapi-finops.yml) | FinOps Framework + FOCUS-aligned definition for a free open-data API (`reconciled: false`) |

## Authentication

Public read endpoints **do not require an API key**. Use of the data is subject to the DiscGolfAPI licence, which requires visible attribution where data is displayed: "Course data supplied by DiscGolfAPI."

## Common Properties

- [Website](https://discgolfapi.com/)
- [Documentation](https://discgolfapi.com/docs/)
- [APIs.json](https://discgolfapi.com/apis.json)
- [OpenAPI](https://discgolfapi.com/openapi.json)
- [Terms of Service](https://discgolfapi.com/terms/)
- [License](https://discgolfapi.com/licence/)
- [Contact](https://discgolfapi.com/contact/)
- [llms.txt](https://discgolfapi.com/llms.txt)
- [robots.txt](https://discgolfapi.com/robots.txt)
- [Schema](https://discgolfapi.com/schema/)
- [Coverage](https://discgolfapi.com/coverage/)
- [Changelog](https://discgolfapi.com/changelog/)
- [Use Our Data](https://discgolfapi.com/use-our-data/)

## Maintainers

**Name:** DiscGolfAPI
**Contact:** [https://discgolfapi.com/contact/](https://discgolfapi.com/contact/)

## Timestamps

- **Created:** 2026-05-03
- **Modified:** 2026-05-16

## Source

- api-search-network issue: [#23](https://github.com/api-search/network/issues/23)
