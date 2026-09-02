<div align="center">

<!-- title -->

<!--lint ignore no-dead-urls-->

# Awesome API-as-a-Business [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![lint](https://github.com/spekulatius/awesome-api-as-a-business/actions/workflows/lint.yaml/badge.svg)](https://github.com/spekulatius/awesome-api-as-a-business/actions/workflows/lint.yaml)

<!-- subtitle -->

A curated list of resources for building, running, and growing an API as a business.

</div>

<!-- TOC -->

## Contents

- [Marketplaces & Directories](#marketplaces--directories)
  - [Regional & Niche Marketplaces](#regional--niche-marketplaces)
- [API Gateways & Management](#api-gateways--management)
- [Monetization & Billing](#monetization--billing)

<!-- CONTENT -->

## Marketplaces & Directories

- [RapidAPI Hub](https://rapidapi.com/hub) - The largest API marketplace for discovering, testing, and monetizing APIs.
- [Postman API Network](https://www.postman.com/explore) - Discovery and collaboration network for public APIs, built into Postman.
- [APIs.guru](https://apis.guru/) - Open source, community-curated directory of OpenAPI/Swagger definitions for thousands of public APIs.
- [Public APIs](https://github.com/public-apis/public-apis) - Open source, collaborative list of free public APIs for software and web development.
- [APILayer Marketplace](https://apilayer.com/) - Curated marketplace of first- and third-party APIs focused on data, validation, and utility services.

### Regional & Niche Marketplaces

- [Zyla API Hub](https://zylalabs.com/) - Global marketplace with 8,000+ APIs, positioned as a smaller-scale RapidAPI alternative.
- [ApyHub](https://apyhub.com/) - Global marketplace bundling a wide range of utility APIs under a single subscription.
- [Apify Store](https://apify.com/store) - Global marketplace of ready-made web scraping and automation APIs ("Actors"), with European roots.
- [API Market](https://api.market/) - Global marketplace focused on AI, data, and MCP server APIs.
- [Juhe Data (JuheAPI)](https://www.juhe.cn/) - China's largest basic data API service provider, with an international arm covering overseas payments, logistics, and communications APIs.
- [API Setu](https://apisetu.gov.in/) - India's government-run open API platform and marketplace, run by the Ministry of Electronics and IT.
- [OpenAPIHub (FabriXAPI)](https://www.openapihub.com/) - Hong Kong-based API hub and portal platform serving the Asia-Pacific developer community.
- [APIBrasil](https://www.apibrasil.com.br/) - Brazil-focused marketplace of local APIs, including CPF/CNPJ lookups, WhatsApp, and postal code services.

## API Gateways & Management

- [Kong Gateway](https://github.com/Kong/kong) - The most widely deployed open source API gateway, with a large plugin ecosystem.
- [Apache APISIX](https://apisix.apache.org/) - Fully Apache-2.0 licensed gateway with 100+ plugins and a built-in dashboard.
- [Tyk Gateway](https://github.com/TykTechnologies/tyk) - Open source gateway core with GraphQL federation and multi-language plugins; dashboard and portal are paid add-ons.
- [KrakenD](https://www.krakend.io/) - Stateless, high-performance gateway with a free, open source Community Edition.
- [Gravitee](https://www.gravitee.io/) - Open source gateway supporting both REST and event-driven APIs (Kafka, MQTT, WebSocket), with plugin-based billing.
- [Fusio](https://www.fusio-project.org/) - Open source API management platform with a built-in developer portal and monetization support out of the box.
- [WSO2 API Manager](https://wso2.com/api-manager/) - Full API lifecycle management platform, open source under Apache-2.0.
- [Envoy Gateway](https://gateway.envoyproxy.io/) - CNCF project providing a vendor-neutral, Kubernetes-native implementation of the Gateway API on top of Envoy Proxy.

## Monetization & Billing

Case studies of API-first businesses billing customers directly through a payment gateway like Stripe, rather than bolting on a separate metering platform - including where that approach holds up and where it starts to break down.

- [Supabase: usage-based billing on Stripe](https://stripe.com/customers/supabase) - Supabase calculates usage and fees itself, then forwards the final amount straight to Stripe's Payments API for processing.
- [Stripe Sync Engine](https://github.com/stripe/sync-engine) - Open source (Apache-2.0) webhook-driven tool, originally built and open sourced by Supabase, now maintained by Stripe, that mirrors Stripe billing objects into Postgres for anyone billing natively on Stripe.
- [How we built it: Usage-based billing](https://stripe.com/blog/how-we-built-it-usage-based-billing) - Stripe's own engineering write-up on building a high-throughput, low-latency metering and revenue-ledger pipeline for billing on raw usage events.
- [Why Stripe bought Metronome](https://sacra.com/research/why-stripe-bought-metronome/) - Analysis of why AI/API companies such as OpenAI, Anthropic, Databricks, and Nvidia chose a dedicated metering layer over billing usage on Stripe natively, and what that reveals about the limits of native gateway billing at very high event volumes.
- [Why Stripe usage-based billing is fundamentally broken for AI products](https://hackernoon.com/why-stripe-usage-based-billing-is-fundamentally-broken-for-ai-products) - A practitioner's critique of the timing and reconciliation problems that surface when metering AI/API usage directly against Stripe's billing meters.

<!-- END CONTENT -->

## Contributing

[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors

[Thanks goes to these contributors](https://github.com/spekulatius/awesome-api-as-a-business/graphs/contributors)!
