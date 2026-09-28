## Hi, I'm Srujan 👋

Data engineer with ~10 years of experience building large-scale data platforms on AWS and Azure — PySpark, Apache Iceberg lakehouses, and event-driven architectures.
I contribute to open-source data tooling..

## Open Source Contributions

### [OpenLineage](https://github.com/OpenLineage/OpenLineage): the open standard for data lineage

- **SSL context support for the Python HTTP transport**: added an `ssl_context` option to `HttpConfig` so clients can use custom CA bundles and mTLS ([issue #3460](https://github.com/OpenLineage/OpenLineage/issues/3460), [PR #4983](https://github.com/OpenLineage/OpenLineage/pull/4983) — under review).

### [SQLMesh](https://github.com/SQLMesh/sqlmesh): data transformation framework

- **Fix: drop clustering key before dropping columns it references** ([issue #5813](https://github.com/SQLMesh/sqlmesh/issues/5813), [PR #6095](https://github.com/SQLMesh/sqlmesh/pull/6095) — under review).

### [Dagster](https://github.com/dagster-io/dagster): data orchestration platform

- **Fix execution hang when a skip is unblocked by an abandon**: `plan_events_iterator` now runs the skip/abandon phases to a fixed point instead of a single pass, so a skip unblocked by an abandonment can no longer stall execution forever ([issue #33661](https://github.com/dagster-io/dagster/issues/33661), [PR #34238](https://github.com/dagster-io/dagster/pull/34238) — under review).

## Research

- **Silent data loss in serverless Spark** — arXiv paper (2026).

