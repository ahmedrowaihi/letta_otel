# Letta OpenTelemetry (`letta_otel`)

A community-driven repository for OpenTelemetry Collector configuration and a full-featured Grafana dashboard for monitoring **Letta** with **ClickHouse** and other supported backends.

## Features

| Feature                 | Description                                                             |
-------------------- | ----------------------------------------------------------------------- |
| OpenTelemetry Collector | Setup scripts and configuration files for collecting observability data |
| Grafana Dashboard       | JSON model for visualizing Letta telemetry metrics and logs             |
| ClickHouse Integration  | Optimized setup for ClickHouse as a backend                             |

## Getting Started

### Import the Grafana Dashboar
| Step | Instruction                                                           |
| ---- | --------------------------------------------------------------------- |
| 1    | Open Grafana                                                          |
| 2    | Navigate to **Dashboards → Import**                                   |
| 3    | Upload or paste the contents of `basic_dashboard.json`                |
| 4    | Select your **ClickHouse datasource** from the dropdown when prompted |


## Files Overview

| File Name              | Des
| ---------------------- | -------------------------------------------------------------------------------------------------------- |
| `basic_dashboard.json` | Grafana dashboard definition for Letta                                                                   |
|                        | ![Dashboard Screenshot](https://github.com/user-attachments/assets/0d1d471b-2d0d-4567-9f82-42bac87973a9) |

---

## Useful Links

| Resource                | URL                                                                                  |
| ----------------------- | ------------------------------------------------------------------------------------ |
| OpenTelemetry Collector | [https://opentelemetry.io/docs/collector/](https://opentelemetry.io/docs/collector/) |
| Grafana                 | [https://grafana.com/](https://grafana.com/)                                         |
| ClickHouse              | [https://clickhouse.com/](https://clickhouse.com/)                                   |

## Contributing

Contributions, issues, and feature requests are welcome.
To contribute, open an issue or submit a pull request through GitHub.
