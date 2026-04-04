<div align="center">

# Observantio

  <img src="wolf.png" alt="Observantio wolf icon" width="170" />

  <p>
    <img src="https://img.shields.io/badge/Focus-Open%20Observability-1f2937?style=flat-square" alt="Focus" />
    <img src="https://img.shields.io/badge/Stack-LGTM%20%2B%20Control%20Plane-0f766e?style=flat-square" alt="Stack" />
    <img src="https://img.shields.io/badge/Model-Self%20Hosted%20%7C%20Multi%20Tenant-0ea5e9?style=flat-square" alt="Model" />
  </p>
</div>

Observantio builds practical, self-hosted observability products on top of open-source foundations.
Our goal is simple: make logs, traces, metrics, alerts, and incident response easier to operate as one system.

## Ecosystem Repositories

- [Watchdog - Control Plane](https://github.com/observantio/watchdog)  
  Unified control plane for auth, tenancy, API keys, observability workflows, integrations, and RCA orchestration.

- [Resolver - RCA Engine](https://github.com/observantio/resolver)  
  RCA and analysis engine for anomaly detection, signal correlation, and investigation support.

- [Notifier - Incident & Alerting Hub](https://github.com/observantio/notifier)  
  Alerting and incident workflow service with channel management and Jira-aware operations.

- [Ojo - Lightweight Agent](https://github.com/observantio/ojo)  
  Lightweight telemetry agent for Windows and Linux environments.

## What You Can Expect

- Open, auditable architecture built around OSS observability components.
- Security-first service boundaries (RBAC, tenancy context, scoped ingest).
- Clear developer workflows with tests, static analysis, and contract testing.
- Documentation that maps product behavior to real operational tasks.

## Contributing

1. Open an issue for bugs, questions, or feature requests.
2. Submit pull requests with clear scope and context.
3. Keep docs aligned with behavior changes.

## License

All core repositories are Apache 2.0 licensed.  
Observantio is an independent organization and is not affiliated with or endorsed by Grafana, Prometheus, or VictoriaMetrics.
