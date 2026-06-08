# Conduktor

We make Apache Kafka safe to share. Conduktor is the control plane platform teams put in front of their clusters: a Console to see what's happening, a Gateway to enforce rules in the data path, and a CLI to automate the rest. One place to give developers self-service access without handing them the keys to production.

[Website](https://conduktor.io) · [Docs](https://docs.conduktor.io) · [Learn Apache Kafka](https://conduktor.io/kafka) · [Kafka Glossary](https://conduktor.io/glossary)

## The Conduktor platform

- **[conduktor-platform](https://github.com/conduktor/conduktor-platform)** — the Apache Kafka operations platform: Console, Gateway, and the APIs that tie them together.
- **[conduktor-gateway-demos](https://github.com/conduktor/conduktor-gateway-demos)** — the Gateway in action. Field-level encryption, multi-tenancy, chaos testing, and other interceptors you can run yourself.
- **[passthrough-gateway-quickstart](https://github.com/conduktor/passthrough-gateway-quickstart)** — drop the Gateway in front of any cluster locally and see your traffic in minutes.
- **[skills](https://github.com/conduktor/skills)** — open-source agent skills that teach Claude, Cursor, and other AI assistants how Conduktor and Kafka actually work.

## Run Kafka in minutes

- **[kafka-stack-docker-compose](https://github.com/conduktor/kafka-stack-docker-compose)** — Docker Compose files for a full Kafka stack: single broker, multi-broker, Schema Registry, Kafka Connect. The fastest way to get a real cluster on your laptop.
- **[kafka-security-manager](https://github.com/conduktor/kafka-security-manager)** — manage Kafka ACLs as code, version-controlled and applied at scale instead of by hand.
- **[terraform-provider-conduktor](https://github.com/conduktor/terraform-provider-conduktor)** — provision Conduktor and your Kafka resources with Terraform.
- **[ctl](https://github.com/conduktor/ctl)** — the Conduktor CLI, for driving the platform from your terminal or CI.

## Learn Kafka

- **[Learn Apache Kafka](https://conduktor.io/kafka)** — our free, hands-on Kafka course: topics, producers, consumers, the CLI, and production internals.
- **[awesome-kafka](https://github.com/conduktor/awesome-kafka)** — a curated list of Kafka tools, libraries, blogs, and talks.

Browse [all our repositories](https://github.com/orgs/conduktor/repositories?type=source) for connectors, demos, and reference architectures.
