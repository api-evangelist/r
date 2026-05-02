# R

R is a free, open-source programming language and statistical computing environment maintained by the R Core Team and supported by the R Foundation. It provides a wide variety of statistical and graphical techniques and is highly extensible through its package ecosystem on CRAN (Comprehensive R Archive Network), Bioconductor, and GitHub. R is widely used among statisticians, data scientists, and researchers for data analysis, visualization, and reproducible research.

**Website:** [https://www.r-project.org/](https://www.r-project.org/)
**Package Registry:** [https://cran.r-project.org/](https://cran.r-project.org/)
**GitHub Org:** [https://github.com/r-lib](https://github.com/r-lib)
**APIs.yml:** [https://raw.githubusercontent.com/api-evangelist/r/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/r/refs/heads/main/apis.yml)

## APIs

### METACRAN CranDB API

CouchDB-based REST API providing programmatic access to metadata for all CRAN R packages. Supports package lookup, version history, and package dependency data in JSON format. No authentication required.

- **Base URL:** `https://crandb.r-pkg.org`
- **Documentation:** [https://github.com/metacran/crandb](https://github.com/metacran/crandb)
- **OpenAPI:** [openapi/r-metacran-crandb-openapi.yml](openapi/r-metacran-crandb-openapi.yml)

### METACRAN CranLogs API

REST API providing download statistics for R packages from the RStudio CRAN mirror. Supports daily, weekly, monthly, and grand-total download counts with badge generation endpoints. No authentication required.

- **Base URL:** `https://cranlogs.r-pkg.org`
- **Documentation:** [https://github.com/metacran/cranlogs.app](https://github.com/metacran/cranlogs.app)
- **OpenAPI:** [openapi/r-metacran-cranlogs-openapi.yml](openapi/r-metacran-cranlogs-openapi.yml)

### R Versions API

REST API reporting current and previous stable releases of R, including version numbers, release dates, and nicknames. Used by CI/CD tools and package managers to determine supported R versions.

- **Base URL:** `https://rversions.r-pkg.org`
- **Documentation:** [https://github.com/metacran/rversions.app](https://github.com/metacran/rversions.app)
- **OpenAPI:** [openapi/r-rversions-openapi.yml](openapi/r-rversions-openapi.yml)

## OpenAPI Specifications

| API | File |
|-----|------|
| METACRAN CranDB API | [openapi/r-metacran-crandb-openapi.yml](openapi/r-metacran-crandb-openapi.yml) |
| METACRAN CranLogs API | [openapi/r-metacran-cranlogs-openapi.yml](openapi/r-metacran-cranlogs-openapi.yml) |
| R Versions API | [openapi/r-rversions-openapi.yml](openapi/r-rversions-openapi.yml) |

## Capabilities

Naftiko capabilities combining the METACRAN APIs into analytics workflows.

| Capability | Description |
|-----------|-------------|
| [capabilities/r-package-analytics.yaml](capabilities/r-package-analytics.yaml) | R package ecosystem analytics combining metadata, download statistics, and R version data |

### Shared Definitions

| API | File |
|-----|------|
| METACRAN CranDB | [capabilities/shared/metacran-crandb.yaml](capabilities/shared/metacran-crandb.yaml) |
| METACRAN CranLogs | [capabilities/shared/metacran-cranlogs.yaml](capabilities/shared/metacran-cranlogs.yaml) |
| R Versions | [capabilities/shared/rversions.yaml](capabilities/shared/rversions.yaml) |

## JSON Schema

| Schema | File |
|--------|------|
| CRAN Package | [json-schema/r-cran-package-schema.json](json-schema/r-cran-package-schema.json) |
| Download Statistics | [json-schema/r-download-stats-schema.json](json-schema/r-download-stats-schema.json) |
| R Version | [json-schema/r-version-schema.json](json-schema/r-version-schema.json) |

## JSON Structure

| Structure | File |
|-----------|------|
| CRAN Package | [json-structure/r-cran-package-structure.json](json-structure/r-cran-package-structure.json) |

## JSON-LD

| Context | File |
|---------|------|
| R Context | [json-ld/r-context.jsonld](json-ld/r-context.jsonld) |

## Examples

| Example | File |
|---------|------|
| Get Package Download Totals | [examples/r-get-package-download-totals-example.json](examples/r-get-package-download-totals-example.json) |
| Get Package Metadata | [examples/r-get-package-metadata-example.json](examples/r-get-package-metadata-example.json) |
| Get Current R Release | [examples/r-get-r-release-example.json](examples/r-get-r-release-example.json) |

## Rules

| Ruleset | File |
|---------|------|
| R Spectral Rules | [rules/r-spectral-rules.yml](rules/r-spectral-rules.yml) |

## Vocabulary

| Vocabulary | File |
|-----------|------|
| R Vocabulary | [vocabulary/r-vocabulary.yml](vocabulary/r-vocabulary.yml) |

## Tags

R, Statistics, Data Science, Open Source, Programming Language, CRAN

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
