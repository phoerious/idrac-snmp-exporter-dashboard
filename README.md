# iDrac SNMP Dashboard for Grafana (Prometheus)

Grafana dashboard with iDrac SNMP metrics for Prometheus monitoring.

The dashboard is loosely based on the original Telegraf / InfluxDB-based dashboard by [@ilovepancakes95](https://github.com/ilovepancakes95/idrac_snmp-grafana).

![Dashboard Screenshot](screenshot.png)

## Requirements

- Prometheus [snmp_exporter](https://github.com/prometheus/snmp_exporter) instance
- Grafana with Prometheus Datasource

## Files

This repository includes the dashboard JSON, the generated snmp-exporter config and the original generator config. iDRAC MIBs are not included.

- `dashboard.json` - The dashboard
- `snmp.yaml` - The snmp_exporter config (auto-generated)
- `generator.yml` - snmp_exporter config generator config ([see here](https://github.com/prometheus/snmp_exporter/tree/main/generator))

