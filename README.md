# 🔭 The "BE" Ecosystem

### **What is to "BE" in observability**

At **Observantio**, we build the tools that turn raw noise into actionable intelligence. We are dedicated to simplifying the modern observability stack (LGTM but not limited to that) by providing high-performance orchestration, AI-driven analysis, and seamless incident collaboration and a full stack observability tool for anyone to use

---

## 🏛 The Ecosystem

We believe that observability shouldn't be a collection of disconnected tabs. Our projects work together to form a unified "Control Plane" on top of your telemetry data that sees it all for free

### 🛰 [Be Observant](https://github.com/observantio/beobservant)

**The Unified Control Plane.** The entry point for your entire stack. It secures and unifies metrics, logs, traces, AiOps and alerts into a single, RBAC-protected interface. Built for the LGTM stack, it eliminates context-switching and provides a true "Single Pane of Glass."

### 🧠 [Be Certain](https://github.com/observantio/becertain)

**The AI Reasoning Engine.** Stop guessing. **Be Certain** uses custom-built analytics to perform Root Cause Analysis (RCA), anomaly detection, and predictive forecasting. It correlates signals across Loki, Tempo, and Mimir to tell you exactly where the "smoking gun" is.

### 🔔 [Be Notified](https://github.com/observantio/benotified)

**The Incident Hub.** Alerting is only half the battle. **Be Notified** manages the human side—incident lifecycle, team collaboration, Jira syncing, and intelligent alert routing. It ensures the right people get the right data at the right time.

---

## 🛠 Our Technology Stack

We build for performance, security, and scale. Our tools are native to the modern cloud-native landscape.

* **Core:** Python (FastAPI), OpenTelemetry (OTLP), Envoy, NGINX and Postgres
* **Storage and Other Tools** Prometheus/Mimir, Grafana/Loki, Tempo, VictoriaMetrics.
* **Security:** Asymmetric JWT (RS256), MFA/TOTP, OIDC/Keycloak, HashiCorp Vault Support
* **Delivery:** Docker Compose, Kubernetes (Coming soon), CI/CD gated with comprehensive Pytest suites.

---

## 🤝 Philosophy & Contributions

> **"Observability is not about more data; it's about more answers."**

We are an open-core organization focused on building tools that SREs actually enjoy using. We follow a "Security-First" and "Automation-Always" philosophy for teams of any sizes

### Want to contribute?

We welcome engineers who are passionate about distributed systems, causal analysis, and backend architecture.

1. **Explore:** Check out our "Help Wanted" or "Good First Issue" labels.
2. **Standardize:** We use strict pre-commit hooks and testing gates across all repos.
3. **Collaborate:** Join our discussions on incident orchestration and AI-driven RCA.

---

## 📄 License & Legal

All Observantio projects are licensed under the **Apache License 2.0**. We believe in the freedom to innovate while maintaining clear attribution and a strong disclaimer of liability.

*Note: Observantio is an independent organization created by Stefan Kumarasinghe. We are not affiliated with, sponsored by, or endorsed by the official Grafana or Prometheus projects or Victoria Metrics, though we love and build upon their amazing foundations.*
