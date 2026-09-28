Enterprise architect working on data and AI platforms in regulated industries: governance,
real-time data, and the operating models that make them work. I've done this work as an
advisor to CIOs and CTOs and from inside a regulated enterprise.

**[federation](https://github.com/Acatium/federation)**: can one governance layer sit safely
above Databricks, Snowflake and AWS? This reference implementation mirrors each platform's
access grants into Apache Ranger, queries across the platforms with Trino, and computes what
happens when the mirror drifts. The answer turns on identity. With passthrough, a stale
policy is harmless. With the shared service credentials most deployments use, it exposes
data until the next sync.
*Python · Apache Ranger · Trino · Gravitino · Unity Catalog · Snowflake · AWS Lake Formation*
