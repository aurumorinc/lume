# Changelog v1.1.0

## Features

### Structlog Telemetry Integration
*   Implemented a centralized, zero-config `structlog` proxy to unify logging, OpenTelemetry, Sentry, PostHog, and Langfuse, replacing legacy logging modules.
*   Added comprehensive unit tests covering initialization, idempotency, and processor logic to ensure stable telemetry delivery.
*   Introduced a new agent skill specifically designed to provide development support for `structlog` configurations.
*   Commits: [0615556](https://github.com/aurumorinc/lume-python/commit/0615556d), [e14e397](https://github.com/aurumorinc/lume-python/commit/e14e3979), [2ed31e6](https://github.com/aurumorinc/lume-python/commit/2ed31e67)
