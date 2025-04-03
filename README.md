Welcome to the **Gofiggy Organization**!

We are dedicated to simplifying dynamic configuration management by embracing **GitOps** principles. Gofiggy provides a cohesive ecosystem featuring:

*   A central server (`gofiggy-server`)
*   A Go client library (`pkg/gofiggy`)
*   A Command-Line Interface tool (`gofiggy`)

This system leverages your existing Git repository as the canonical source of truth for application configurations. By monitoring your repository for changes across multiple common formats (YAML, JSON, TOML, INI, etc.), the `gofiggy-server` delivers these updates in **real-time** to subscribed clients using efficient **Server-Sent Events (SSE)**.

Our goal is to provide developers and operators with a robust, auditable, and easy-to-use system for managing and distributing configuration dynamically, minimizing operational complexity and enabling faster iteration.
