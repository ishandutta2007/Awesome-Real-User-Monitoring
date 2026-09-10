# Awesome-Real-User-Monitoring

## Top Real User Monitoring (RUM) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Browser & Frontend Performance, Core Web Vitals, Session Experience, Error Tracking, User Journeys & Full-Stack Correlation*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Real User Monitoring (RUM)**. These tools collect performance, error, and behavioral data directly from real users’ browsers and devices to help teams understand actual user experience, diagnose frontend issues, and correlate with backend traces.

**Examples** include Datadog RUM, New Relic Browser, Dynatrace RUM, Elastic RUM, Sentry Performance / Browser, Raygun, AppDynamics Browser, Sematext Experience, Instana, Smartbear AlertSite, Grafana Faro, and Azure Application Insights (the category leaders).

**Open-source emphasis**: While many leading RUM solutions are commercial, there is a strong open-source ecosystem led by **Grafana Faro**, OpenTelemetry browser instrumentation, classic libraries such as Boomerang, and open APM backends that accept RUM data. This section is expanded with every major active project.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Datadog RUM](https://www.datadoghq.com/product/real-user-monitoring/)**  
  Full-featured real user monitoring integrated with Datadog’s APM, logs, and session replay for end-to-end observability and rapid troubleshooting.

- **[New Relic Browser](https://newrelic.com/platform/browser-monitoring)**  
  Browser and frontend monitoring with strong querying (NRQL), Core Web Vitals, session insights, and correlation to backend services.

- **[Dynatrace RUM](https://www.dynatrace.com/)**  
  AI-powered real user monitoring within the Dynatrace platform, offering automatic dependency mapping, anomaly detection, and deep user-experience analytics.

- **[Elastic RUM](https://www.elastic.co/observability)**  
  Real user monitoring as part of Elastic Observability, ingesting frontend data into the Elastic Stack for search, visualization, and correlation.

- **[Sentry (Performance + Browser / Session Replay)](https://sentry.io/)**  
  Error tracking and performance monitoring with strong frontend support, distributed tracing, and session replay capabilities.

- **[Grafana Cloud / Faro (managed)](https://grafana.com/)**  
  Managed frontend observability built on the open-source Grafana Faro SDK, tightly integrated with the LGTM stack.

- **[Raygun, AppDynamics Browser, Instana, Sematext Experience](https://raygun.com/)**  
  Specialized or platform RUM offerings focused on crash reporting, user experience, and application performance.

- **[Azure Application Insights & SmartBear AlertSite](https://azure.microsoft.com/)**  
  Cloud-native and synthetic + RUM solutions from major vendors for application and digital experience monitoring.

- **[Other RUM & digital experience platforms](https://www.datadoghq.com/)**  
  Additional commercial tools covering mobile RUM, synthetic monitoring, and full digital experience management.

## Open-Source GitHub Projects

- **[Grafana Faro Web SDK](https://github.com/grafana/faro-web-sdk)**  
  Leading open-source web SDK for real user monitoring. Captures performance metrics, errors, events, logs, and traces from browser applications and integrates with the Grafana LGTM stack or custom backends.

- **[OpenTelemetry JavaScript / Browser](https://github.com/open-telemetry/opentelemetry-js)**  
  OpenTelemetry instrumentation for browser and JavaScript applications, enabling standards-based collection of traces, metrics, and RUM-style signals that can be exported to any compatible backend.

- **[Boomerang](https://github.com/akamai/boomerang)**  
  Classic, widely deployed open-source JavaScript library for real user monitoring and performance beaconing (still influential and used in many environments).

- **[Uptrace](https://github.com/uptrace/uptrace)**  
  Open-source APM that supports OpenTelemetry traces, metrics, and logs; can serve as a backend for frontend/RUM data in self-hosted setups.

- **[OpenReplay (session-focused)](https://github.com/openreplay/openreplay)**  
  Open-source session replay and analytics platform that complements RUM with detailed user session reconstruction (often used alongside performance monitoring).

- **[web-vitals & Core Web Vitals libraries](https://github.com/GoogleChrome/web-vitals)**  
  Official and community libraries for measuring Core Web Vitals and key browser performance metrics in real user sessions.

- **[Other RUM & frontend observability agents](https://github.com/search?q=real+user+monitoring+OR+RUM+SDK+OR+browser+performance)**  
  Additional open-source agents, beacons, and collectors for capturing page load, resource timing, errors, and user interactions.

- **[Self-hosted observability stacks](https://github.com/grafana/grafana)**  
  Grafana, Loki, Tempo, Mimir and related projects that form complete open-source backends for RUM and full-stack telemetry.

### Additional Strong Open-Source Options

- **Session & error tracking**: Open-source alternatives or complements to commercial session replay.
- **Performance observers & Timing APIs**: Native browser APIs wrapped by open libraries for custom RUM collection.
- **Privacy-aware collectors**: Tools that emphasize data minimization and consent-friendly instrumentation.
- **Mobile RUM foundations**: Open instrumentation for React Native, Flutter, or native mobile (where available).
- **Alerting & SLOs**: Open-source rules engines and Prometheus-style alerting on frontend performance signals.
- Integration examples connecting Faro or OpenTelemetry browser data to Jaeger, Zipkin, or ClickHouse-based backends.

**Frameworks for building custom systems**:  
The strongest open-source path is **Grafana Faro** (or OpenTelemetry browser instrumentation) collecting data into a self-hosted **Grafana LGTM** stack or another OpenTelemetry-compatible backend (Uptrace, etc.).  
This provides performance metrics, errors, traces, and correlation without vendor lock-in.  
Commercial RUM platforms (Datadog, New Relic, Dynatrace, Elastic, Sentry, etc.) add polished session replay, advanced analytics, AI-assisted insights, global scale, and lower operational overhead.  
Many teams run open-source instrumentation (Faro / OTel) while sending data to a commercial backend, or fully self-host for cost and data-control reasons.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Real User Monitoring collects data from end-user browsers and devices. Privacy, consent (GDPR, CCPA, etc.), data minimization, and secure transmission are essential responsibilities of the operator.
- Open-source RUM SDKs and backends offer transparency and flexibility but require proper configuration, scaling, retention policies, and security hardening. Evaluate total cost of ownership and compliance needs carefully.

---

**Made for frontend engineers, SREs, performance teams, observability practitioners, and digital experience owners.**  
Let's make real-user performance data open, correlatable, and actionable—whether through managed platforms or fully open-source stacks.
