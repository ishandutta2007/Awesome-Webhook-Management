# Awesome-Webhook-Management

## Top Webhook Management Tools Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Reliable Webhook Delivery, Event Gateways, Retries, Observability & Developer Experience*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Webhook Management**. These tools handle outbound webhook delivery (sending events to customers), inbound webhook ingestion/proxying, retries, rate limiting, transformations, replay, multi-tenant portals, signatures, and observability for event-driven architectures.

**Examples** include Svix, Hookdeck, Convoy, Integrate.io Webhooks, Pipedream, Trigger.dev, Webhook Relay, Latenode, Webhook.site Enterprise, and Hook0 (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, full source access, and open webhook infrastructure — ideal for platform teams, SaaS builders, and developers who need reliable, auditable webhook delivery without vendor lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing | Free Tier Limit |
| :--- | :--- | :--- | :--- |
| **[Svix](https://www.svix.com/)** | Enterprise-ready webhooks-as-a-service platform focused on outbound delivery, with embeddable customer portals, retries, transformations, FIFO, throttling, and high reliability. | $490/month | 50,000 messages/month |
| **[Hookdeck](https://hookdeck.com/)** | Event gateway specializing in inbound webhook reliability (Event Gateway) and outbound destinations (Outpost), with queuing, transformations, replay, and observability. | $39/month | 10,000 events/month |
| **[Convoy](https://getconvoy.io/)** | Source-available webhook delivery server supporting both inbound and outbound events, retries, circuit breaking, and customer dashboards. | $99/month | 14-day free trial |
| **[Integrate.io Webhooks](https://www.integrate.io/)** | Webhook and data integration capabilities within the Integrate.io platform for reliable event handling and pipeline orchestration. | $1,999/month | 14-day free trial |
| **[Pipedream](https://pipedream.com/)** | Workflow automation and event-driven platform that includes robust webhook ingestion, processing, and delivery features. | $29/month | 100 credits/month |
| **[Trigger.dev](https://trigger.dev/)** | Open-source background jobs and workflow platform (with managed offering) well-suited for long-running event-driven and webhook-triggered tasks. | $10/month | $5 monthly credits |
| **[Webhook Relay](https://webhookrelay.com/)** | Developer-focused webhook forwarding, tunneling, and proxying tool for local development and reliable delivery. | $4.90/month | 25,000 events/month |
| **[Latenode](https://latenode.com/)** | Low-code / no-code automation platform with strong webhook support for connecting services and building event-driven flows. | $5/month | 10,000 CPU seconds/month |
| **[Webhook.site Enterprise](https://webhook.site/)** | Advanced version of the popular webhook testing and inspection tool, offering enterprise features for teams. | $69/month | 50 requests/URL (Expires in 7 days) |
| **[Hook0](https://www.hook0.com/)** | Open-source (SSPL) and managed webhook platform focused on outbound delivery, with full feature parity between cloud and self-hosted editions. | €59/month | 100 events/day |

## Open-Source GitHub Projects
- **[Svix (Open Source Server)](https://github.com/svix/svix-webhooks)**  
  MIT-licensed open-source webhook server (written in Rust) that powers the Svix platform; supports self-hosting with high compatibility to the managed service.

- **[Hookdeck Outpost](https://github.com/hookdeck/outpost)**  
  Apache 2.0 open-source outbound webhooks and event destinations infrastructure with multi-tenant support, retries, and portal capabilities.

- **[Hook0](https://github.com/hook0/hook0)**  
  Fully open-source (SSPL) webhook-as-a-service platform built in Rust, offering complete feature parity between self-hosted and cloud versions.

- **[Convoy](https://github.com/frain-dev/convoy)**  
  Open-source (source-available) webhook gateway for sending and receiving events, with retries, transformations, and multi-tenant features.

- **[Trigger.dev](https://github.com/triggerdotdev/trigger.dev)**  
  Open-source framework for background jobs and durable workflows that integrates well with webhook-triggered and event-driven architectures.

- **[n8n](https://github.com/n8n-io/n8n)**  
  Fair-code workflow automation platform with extensive webhook nodes for receiving and sending events in self-hosted environments.

- **[Webhook.site (community tools)](https://github.com/webhooksite)**  
  Related open tools and extensions around the popular webhook testing and inspection service.

- **[Boomerang / delayed delivery tools](https://github.com/)**  
  Lightweight open-source utilities for delayed or scheduled webhook delivery.

- **[hookee / local development tools](https://github.com/)**  
  CLI and local tools for receiving, inspecting, and reacting to webhooks during development.

- **[HookCatcher & similar debuggers](https://github.com/)**  
  Open-source webhook testing, debugging, and real-time streaming tools for development and troubleshooting.

### Additional Strong Open-Source Options
- Community **ngrok alternatives** and tunnel tools for local webhook development.
- **Apache Kafka / Redis / RabbitMQ** based custom webhook dispatchers.
- Many **HMAC signing**, **retry**, and **dead-letter queue** libraries in various languages.
- Event-driven frameworks (Inngest open components, Temporal, etc.) that can underpin webhook systems.
- Simple open-source webhook receivers and forwarders for specific platforms (GitHub, Stripe, etc.).

**Frameworks for building custom systems**: Use the **Svix open-source server** or **Hook0** as the core delivery engine, **Hookdeck Outpost** for outbound destinations, combine with **Redis/PostgreSQL** for durability, add **OpenTelemetry** for observability, and layer **n8n** or **Trigger.dev** for complex workflow orchestration. Local LLMs can assist with payload transformation logic and anomaly detection in delivery failures.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Webhook systems often carry sensitive payloads and must implement proper authentication (HMAC signatures), rate limiting, retries, and security best practices.
- Self-hosted open-source solutions require careful attention to scalability, durability, monitoring, and compliance (especially for multi-tenant or customer-facing portals).

---
**Made for platform engineers, SaaS builders, backend developers, and teams building reliable event-driven systems.**
Let's make webhook infrastructure more open, reliable, and developer-friendly.
