# Oracle GoldenGate (oracle-goldengate)

Oracle GoldenGate enables real-time data integration and replication in heterogeneous IT environments. These APIs provide programmatic access to manage and monitor GoldenGate deployments, processes, and configurations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/oracle-goldengate/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/oracle-goldengate/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- CDC
- Data Integration
- Data Synchronization
- Database
- Enterprise
- Real-Time Replication

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### Oracle GoldenGate REST API

RESTful API for managing Oracle GoldenGate Microservices Architecture, including deployment configuration, process management, and monitoring.

- **Human URL:** [https://docs.oracle.com/en/middleware/goldengate/core/](https://docs.oracle.com/en/middleware/goldengate/core/)
- **Base URL:** `https://<goldengate-host>:<port>/services/v2`

#### Tags

- CDC
- Data Replication
- ETL
- Microservices
- Real-Time Data Integration

#### Properties

- [Documentation](https://docs.oracle.com/en/middleware/goldengate/core/21.3/oggra/index.html)
- [OpenAPI](openapi/oracle-goldengate-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/oracle-goldengate-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-goldengate-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://docs.oracle.com/en/middleware/goldengate/core/21.3/oggra/authentication.html)
- [Documentation](https://docs.oracle.com/en/database/goldengate/core/26/oggra/index.html)
- [Authentication](https://docs.oracle.com/en/database/goldengate/core/26/oggra/authenticate.html)
- [Getting Started](https://docs.oracle.com/en/database/goldengate/core/26/)
- [Tutorials](https://docs.oracle.com/en/database/goldengate/core/26/tutorials.html)
- [Changelog](https://docs.oracle.com/en/database/goldengate/core/26/release-notes/)

### Oracle GoldenGate for Big Data REST API

API for managing Oracle GoldenGate for Big Data deployments, allowing integration with Hadoop, Kafka, and other big data targets.

- **Human URL:** [https://docs.oracle.com/en/middleware/goldengate/big-data/](https://docs.oracle.com/en/middleware/goldengate/big-data/)
- **Base URL:** `https://<goldengate-host>:<port>/services/v2`

#### Tags

- Big Data
- Hadoop
- Kafka
- NoSQL
- Streaming

#### Properties

- [Documentation](https://docs.oracle.com/en/middleware/goldengate/big-data/21.3/gadbd/index.html)
- [OpenAPI](openapi/oracle-goldengate-big-data-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/oracle-goldengate-big-data-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-goldengate-big-data-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Getting Started](https://docs.oracle.com/en/middleware/goldengate/big-data/21.3/gadbd/getting-started.html)

### Oracle GoldenGate Veridata REST API

API for Oracle GoldenGate Veridata to verify and compare data between source and target systems.

- **Human URL:** [https://docs.oracle.com/en/middleware/goldengate/veridata/](https://docs.oracle.com/en/middleware/goldengate/veridata/)
- **Base URL:** `https://<veridata-host>:<port>/veridata/v1`

#### Tags

- Comparison
- Data Quality
- Data Validation
- Data Verification

#### Properties

- [Documentation](https://docs.oracle.com/en/middleware/goldengate/veridata/12.2.1.4/gvdug/index.html)
- [API Reference](https://docs.oracle.com/en/middleware/goldengate/veridata/12.2.1.4/gvdra/index.html)
- [OpenAPI](openapi/oracle-goldengate-veridata-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/oracle-goldengate-veridata-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-goldengate-veridata-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.oracle.com/en/database/goldengate/veridata/26/)
- [Changelog](https://docs.oracle.com/en/database/goldengate/veridata/26/gvdrn/index.html)

### Oracle GoldenGate Cloud Service API

Oracle Cloud Infrastructure API for managing GoldenGate deployments in OCI.

- **Human URL:** [https://docs.oracle.com/en-us/iaas/goldengate/](https://docs.oracle.com/en-us/iaas/goldengate/)
- **Base URL:** `https://goldengate.{region}.oci.oraclecloud.com`

#### Tags

- Cloud
- Cloud Integration
- Database Migration
- OCI

#### Properties

- [Documentation](https://docs.oracle.com/en-us/iaas/api/#/en/goldengate/latest/)
- [OpenAPI](openapi/oracle-goldengate-cloud-service-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/oracle-goldengate-cloud-service-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-goldengate-cloud-service-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [SDK](https://docs.oracle.com/en-us/iaas/Content/API/Concepts/sdks.htm)
- [C L I](https://docs.oracle.com/en-us/iaas/Content/API/Concepts/cliconcepts.htm)
- [Getting Started](https://docs.oracle.com/en/cloud/paas/goldengate-service/index.html)
- [Authentication](https://docs.oracle.com/en-us/iaas/Content/API/Concepts/apisigningkey.htm)
- [Tutorials](https://docs.oracle.com/en/cloud/paas/goldengate-service/tutorials.html)
- [Changelog](https://docs.oracle.com/en-us/iaas/releasenotes/services/goldengate/)
- [SDK](https://docs.oracle.com/en-us/iaas/tools/python/latest/api/golden_gate.html)
- [API Reference](https://docs.oracle.com/en-us/iaas/goldengate/doc/using-rest-api.html)

### Oracle GoldenGate Stream Analytics REST API

REST API for managing Oracle GoldenGate Stream Analytics pipelines, enabling real-time event stream processing, monitoring, and dashboard creation.

- **Human URL:** [https://docs.oracle.com/en/database/goldengate/stream-analytics/index.html](https://docs.oracle.com/en/database/goldengate/stream-analytics/index.html)
- **Base URL:** `https://<ggsa-host>:<port>/osa`

#### Tags

- Dashboards
- Event Processing
- Real-Time Analytics
- Spark
- Stream Analytics

#### Properties

- [Documentation](https://docs.oracle.com/en/database/goldengate/stream-analytics/26/)
- [API Reference](https://docs.oracle.com/en/middleware/fusion-middleware/osa/19.1/ggsa-rest-api/quick-start.html)
- [OpenAPI](openapi/oracle-goldengate-stream-analytics-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/oracle-goldengate-stream-analytics-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-goldengate-stream-analytics-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Getting Started](https://docs.oracle.com/en/database/goldengate/stream-analytics/26/)
- [Changelog](https://docs.oracle.com/en/database/goldengate/stream-analytics/26/release-notes/release-notes-goldengate-stream-analytics.pdf)

### Oracle GoldenGate Data Streams REST API

REST API for distributing and managing Oracle GoldenGate data streams, enabling real-time data distribution to downstream consumers.

- **Human URL:** [https://docs.oracle.com/en/database/goldengate/core/26/coredoc/distribute-datastream-rest-api.html](https://docs.oracle.com/en/database/goldengate/core/26/coredoc/distribute-datastream-rest-api.html)
- **Base URL:** `https://<goldengate-host>:<port>/services/v2`

#### Tags

- Data Distribution
- Data Streams
- Real-Time
- Streaming

#### Properties

- [Documentation](https://docs.oracle.com/en/database/goldengate/core/26/coredoc/distribute-datastream-rest-api.html)
- [OpenAPI](openapi/oracle-goldengate-data-streams-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/oracle-goldengate-data-streams-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-goldengate-data-streams-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Getting Started](https://docs.oracle.com/en/database/goldengate/core/26/)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://www.oracle.com/integration/goldengate/)
- [Blog](https://blogs.oracle.com/dataintegration/)
- [Pricing](https://www.oracle.com/integration/goldengate/pricing/)
- [Getting Started](https://docs.oracle.com/en/middleware/goldengate/core/21.3/index.html)
- [Terms of Service](https://www.oracle.com/legal/terms.html)
- [Privacy Policy](https://www.oracle.com/legal/privacy/)
- [Documentation](https://docs.oracle.com/en/cloud/paas/goldengate-service/docs.html)
- [Sign Up](https://www.oracle.com/cloud/free/)
- [Login](https://cloud.oracle.com/)
- [Status Page](https://ocistatus.oraclecloud.com/)
- [Support](https://support.oracle.com)
- [Knowledge Center](https://www.oracle.com/integration/goldengate/knowledge-hub/)
- [GitHub Organization](https://github.com/oracle)
- [GitHub Repository](https://github.com/oracle/docker-images/tree/main/OracleGoldenGate)
- [Features](https://www.oracle.com/integration/goldengate/features/)
- [Use Cases](https://www.oracle.com/integration/goldengate/)
- [Integrations](https://www.oracle.com/integration/goldengate/)
- [Training](https://education.oracle.com/data-integration/goldengate/product_148)
- [Tutorials](https://docs.oracle.com/en/cloud/paas/goldengate-service/tutorials.html)
- [Release Notes](https://docs.oracle.com/en/database/goldengate/core/26/release-notes/)
- [JSON Schema](json-schema/oracle-goldengate-deployment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/oracle-goldengate-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
