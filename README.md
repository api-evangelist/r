# R (r)

R is a free, open-source programming language and statistical computing environment maintained by the R Core Team and supported by the R Foundation. It provides a wide variety of statistical and graphical techniques and is highly extensible through its package ecosystem on CRAN (Comprehensive R Archive Network), Bioconductor, and GitHub. R is widely used among statisticians, data scientists, and researchers for data analysis, visualization, and reproducible research.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/r/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/r/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- R
- Statistics
- Data Science
- Open Source
- Programming Language

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### METACRAN CranDB API

CouchDB-based REST API providing programmatic access to metadata for all CRAN R packages. Supports package lookup, version history, and package dependency data in JSON format.

- **Human URL:** [https://github.com/metacran/crandb](https://github.com/metacran/crandb)
- **Base URL:** `https://crandb.r-pkg.org`

#### Tags

- CRAN
- Packages
- Metadata

#### Properties

- [Documentation](https://github.com/metacran/crandb)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/r/refs/heads/main/openapi/r-metacran-crandb-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/r-metacran-crandb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/r-metacran-crandb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/r-metacran-cranlogs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/r-metacran-cranlogs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/r-rversions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/r-rversions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### METACRAN CranLogs API

REST API providing download statistics for R packages from the RStudio CRAN mirror. Supports daily, weekly, monthly, and grand-total download counts with badge generation endpoints.

- **Human URL:** [https://github.com/metacran/cranlogs.app](https://github.com/metacran/cranlogs.app)
- **Base URL:** `https://cranlogs.r-pkg.org`

#### Tags

- CRAN
- Downloads
- Statistics

#### Properties

- [Documentation](https://github.com/metacran/cranlogs.app)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/r/refs/heads/main/openapi/r-metacran-cranlogs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/r-metacran-crandb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/r-metacran-crandb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/r-metacran-cranlogs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/r-metacran-cranlogs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/r-rversions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/r-rversions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### R Versions API

REST API that reports the current and previous stable releases of R, including version numbers and release dates. Used by CI tools and package managers to determine supported R versions.

- **Human URL:** [https://github.com/metacran/rversions.app](https://github.com/metacran/rversions.app)
- **Base URL:** `https://rversions.r-pkg.org`

#### Tags

- R
- Versions
- Releases

#### Properties

- [Documentation](https://github.com/metacran/rversions.app)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/r/refs/heads/main/openapi/r-rversions-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/r-metacran-crandb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/r-metacran-crandb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/r-metacran-cranlogs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/r-metacran-cranlogs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/r-rversions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/r-rversions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.r-project.org/)
- [Documentation](https://cran.r-project.org/manuals.html)
- [Git Hub Org](https://github.com/r-lib)
- [Git Hub Org](https://github.com/r-devel)
- [Package Registry](https://cran.r-project.org/)
- [Package Registry](https://bioconductor.org/)
- [Package Search](https://www.rdocumentation.org/)
- [Package Search](https://rdrr.io/)
- [Blog](https://blog.r-project.org/)
- [Forum](https://stat.ethz.ch/mailman/listinfo/r-help)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/r)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
