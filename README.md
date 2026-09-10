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

| Platform | Description & Focus | Starting Pricing | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Datadog RUM](https://www.datadoghq.com/product/real-user-monitoring/)** | Full-featured real user monitoring integrated with APM, logs, Core Web Vitals, and session replay for end-to-end troubleshooting. | Starts at **$1.50 / 1,000 sessions/month** (annual) or $2.20/1k on-demand ($0.15/1k for RUM Measure; Session Replay add-on starts at $2.50/1k sessions) | **14-day free trial** with full platform access (all RUM features, APM, and logs; no credit card required) |
| **[New Relic Browser](https://newrelic.com/platform/browser-monitoring)** | Browser and frontend monitoring with NRQL querying, Core Web Vitals, session insights, and correlation to backend distributed traces. | **$0/month** (included in free tier); overages beyond 100 GB start at **$0.40 / GB** data ingested (Standard) + $49/user/mo for additional Core users | **Free Forever Plan**: **100 GB/month** data ingest across all telemetry (shared across RUM, APM, and logs), 1 Full Platform user, unlimited basic users, 8+ days retention |
| **[Dynatrace RUM](https://www.dynatrace.com/platform/real-user-monitoring/)** | AI-powered real user monitoring with Davis AI root-cause analysis, automatic dependency mapping, and user experience analytics. | Starts at **$0.00225 / session** ($2.25 per 1,000 sessions); **$0.0045 / session** ($4.50 per 1,000 sessions) including Session Replay under DPS model | **15-day free trial** with full platform access to RUM, APM, and Davis AI engine (no credit card required) + live sandbox playground |
| **[Elastic RUM](https://www.elastic.co/observability)** | Frontend performance and error telemetry ingested into the Elastic Stack for Elasticsearch querying, Kibana dashboards, and full APM correlation. | Serverless starts at **$0.09 / GB ingested** + **$0.019 / GB retained/month**; hosted Elastic Cloud clusters start at **$95 / month** (Standard tier) | **14-day free trial** on Elastic Cloud with full access to Elastic Observability features and up to $300 in usage credits (no credit card required) |
| **[Sentry (Performance & Replay)](https://sentry.io/)** | Error tracking and frontend performance monitoring, Core Web Vitals, distributed tracing across spans, and session replay. | Developer tier is **$0/month**; Team plan starts at **$26 / month** (billed annually) or $29/mo (monthly); Business starts at $80/mo (annual) | **Free Forever Plan (Developer)**: **10,000 performance spans/month**, **50 session replays/month**, **5,000 errors/month**, 1 GB attachments for 1 user; **14-day free trial** for Business tier |
| **[Grafana Cloud Frontend Observability](https://grafana.com/products/cloud/frontend-observability/)** | Managed frontend monitoring built on the open-source Grafana Faro SDK, tightly integrated with Grafana, Loki, Tempo, and Mimir (LGTM). | **$0/month** for up to 50k sessions; Pro plan starts at **$19 / month** base fee + **$0.75 per 1,000 sessions** beyond free limits | **Free Forever Plan**: **50,000 sessions/month** for Frontend Observability, 10k series metrics, 50 GB logs, 50 GB traces, 3 users, and 14-day data retention |
| **[Raygun Real User Monitoring](https://raygun.com/platform/real-user-monitoring)** | User experience monitoring, Core Web Vitals, page load waterfalls, single-page application tracking, and detailed user session journey insights. | Starts at **$8 / month** for 10,000 sessions (or **$40 / month** for 50,000 sessions, billed annually); volume discounts available | **14-day free trial** with full feature access and unlimited tracked sessions and applications during the trial (no credit card required) |
| **[Cisco AppDynamics Browser RUM](https://www.appdynamics.com/product/end-user-monitoring/browser-monitoring)** | End-user monitoring tracking browser performance, page rendering, AJAX requests, JavaScript errors, and business transaction correlation. | Starts at **$0.06 per 1,000 RUM tokens/month** (1 pageview = 1 token, billed annually); core APM with RUM starts at **$60 / CPU core/month** | **15-day free trial** (extendable up to 30 days) with full access to Browser RUM, APM, and analytics across all agents (no credit card required) |
| **[IBM Instana](https://www.ibm.com/products/instana)** | Automated real-time website monitoring (EUM), page performance, JS errors, and 1-second metric resolution linked to microservice traces. | Essentials starts at **$21 / host (MVS)/month** ($0.03/hr pay-per-use); Standard tier (full APM + EUM) starts at **$75 / host (MVS)/month** ($0.12/hr) | **14-day free trial** with unrestricted access to website monitoring, distributed tracing, and APM (no credit card required) + 2-minute sandbox demo |
| **[Sematext Experience](https://sematext.com/experience/)** | Dedicated real user monitoring for Core Web Vitals, page speed distribution, UI interactions, API call latency, and Apdex satisfaction scores. | Starts at **$9 / month** for 25,000 page views (7-day data retention); scales to **$29 / month** for 100,000 page views | **14-day free trial** with full platform capabilities and unlimited page views/applications during the trial (no credit card required) |
| **[Azure Application Insights](https://azure.microsoft.com/products/monitor/)** | Cloud-native APM with browser JavaScript SDK for page views, user timings, AJAX calls, and full-stack distributed tracing. | **$0/month** for first 5 GB; pay-as-you-go ingestion starts at **$2.30 per GB** ingested (Analytics Logs, East US) with 90 days retention included | **Free Forever Plan**: **5 GB/month** data ingestion free per billing account with 90 days retention; plus Azure Free Account provides $200 credits for 30 days |
| **[SmartBear AlertSite](https://smartbear.com/product/alertsite/)** | Combined real user and synthetic monitoring platform verifying web performance, transaction flows, and APIs from 350+ global nodes. | Entry-level packages start at **$99 / month** (scaling up to $199/mo depending on monitor frequency, check steps, and location count) | **30-day free trial** with full access to global monitoring nodes, synthetic and real user monitors, and alerting (no credit card required) |
| **[SpeedCurve](https://www.speedcurve.com/)** | Frontend performance monitoring with LUX (Live User Experience) RUM, tracking Core Web Vitals, user engagement, and bounce rate correlations. | Starter tier starts at **$90 / month** (billed annually, or $113/mo monthly) for 100,000 RUM pageviews and 20,000 synthetic checks | **30-day free trial** with full access to LUX RUM and synthetic performance monitoring (no credit card required) |
| **[LogRocket](https://logrocket.com/)** | Frontend observability combining session replay, Core Web Vitals & performance monitoring, JS error tracking, and product analytics. | Developer tier is **$0/month**; Core paid tier starts at **$69 / month** (billed annually) for 10,000 sessions/month | **Free Forever Plan (Developer)**: **1,000 sessions/month**, 3 team seats, and 1-month data retention; **14-day free trial** for paid plans |
| **[SolarWinds Pingdom](https://www.pingdom.com/)** | Real user monitoring paired with synthetic uptime and transaction checks, measuring load times, geographies, and browser platforms. | Starts at **$18 / month** for 100,000 RUM pageviews/month (billed annually, or $19.50/mo monthly) | **30-day free trial** with full access to Real User Monitoring and Synthetic Monitoring (no credit card required) |
| **[Cloudflare Web Analytics](https://www.cloudflare.com/web-analytics/)** | Lightweight, privacy-first real user monitoring without cookies, tracking Core Web Vitals (LCP, INP, CLS) and page load timings from Cloudflare edge. | **100% Free** ($0/month with no paid tier required) | **Free Forever Plan with Unlimited Usage**: Unlimited pageviews and sessions across unlimited sites for any Cloudflare account (no volume cap or credit card needed) |

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
