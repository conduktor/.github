# Conduktor

We make Apache Kafka safe to share. Conduktor is the control plane platform teams put in front of their clusters: a Console to see what's happening, a Gateway to enforce rules in the data path, and a CLI to automate the rest. One place to give developers self-service access without handing them the keys to production.

[Website](https://conduktor.io) · [Docs](https://docs.conduktor.io) · [Learn Apache Kafka](https://conduktor.io/kafka) · [Kafka Glossary](https://conduktor.io/glossary)

## Point AI at your Kafka

Smarter AI, because you hold the context. Safer AI, because you hold the permissions.

AI on Kafka is only useful if it's smart, and only adoptable if it's safe. Conduktor is the self-hosted layer that delivers both, without ever taking ownership of your data. It gives an LLM the full picture: ownership, schemas, lineage, policies, apps, and monitoring across every cluster, so it knows who owns what, what's sensitive, and what changed. When something breaks, those signals sit in one place, so the model correlates lag, dead consumers, and schema breaks instead of guessing.

Every AI, MCP, and CLI action inherits the user's exact RBAC: read-only or read-write, per cluster and per team. The model runs inside the access rules you already trust.

- **Conduktor MCP** runs read-only inside Console for safe exploration.
- **[skills](https://github.com/conduktor/skills)** and the CLI give coding agents a larger, governed surface when it's time to act.

[Explore Conduktor MCP](https://conduktor.io/mcp) · [Set up with an AI agent](https://github.com/conduktor/skills)

## The Conduktor platform

- **[conduktor-platform](https://github.com/conduktor/conduktor-platform)** — the Apache Kafka operations platform: Console, Gateway, and the APIs that tie them together.
- **[passthrough-gateway-quickstart](https://github.com/conduktor/passthrough-gateway-quickstart)** — drop the Gateway in front of any cluster locally and see your traffic in minutes.

## Run Kafka in minutes

- **[kafka-stack-docker-compose](https://github.com/conduktor/kafka-stack-docker-compose)** — Docker Compose files for a full Kafka stack: single broker, multi-broker, Schema Registry, Kafka Connect. The fastest way to get a real cluster on your laptop.
- **[terraform-provider-conduktor](https://github.com/conduktor/terraform-provider-conduktor)** — provision Conduktor and your Kafka resources with Terraform.
- **[ctl](https://github.com/conduktor/ctl)** — the Conduktor CLI, for driving the platform from your terminal or CI.

## Learn Kafka

- **[Learn Apache Kafka](https://conduktor.io/kafka)** — our free, hands-on Kafka course: topics, producers, consumers, the CLI, and production internals.
- **[awesome-kafka](https://github.com/conduktor/awesome-kafka)** — a curated list of Kafka tools, libraries, blogs, and talks.

Browse [all our repositories](https://github.com/orgs/conduktor/repositories?type=source) for connectors, demos, and reference architectures.
