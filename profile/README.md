<div align="center">
  <a href="https://theorvane.tech">
    <img src="./assets/theorvane-organization-banner.png" alt="Theorvane — open-source, community-driven developer tools" width="100%" />
  </a>
  
  <h1>Theorvane</h1>

  **Open-source developer tools for explicit contracts and inspectable systems.**

  <a href="https://theorvane.tech">Website</a>
  <span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>
  <a href="https://typemcp.theorvane.tech">TypeMCP</a>
  <span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>
  <a href="https://github.com/Theorvane">GitHub</a>
</div>

## Welcome

Theorvane builds focused, verifiable tools for developers and AI-native systems. We favor small public surfaces, typed contracts, transparent capability boundaries, and evidence-backed releases.

## Official repositories

| Repository | What it is | Status |
| --- | --- | --- |
| [**TypeMCP**](https://github.com/Theorvane/type-mcp) | Decorator-first TypeScript declarations and runtime tooling for Model Context Protocol (MCP) servers. | [`@theorvane/type-mcp@0.2.0`](https://www.npmjs.com/package/@theorvane/type-mcp) is public and provides definition validation, MCP SDK compilation, stdio, Streamable HTTP, and a tools-only LangChain adapter. Applications own hosting, authorization, and LangGraph composition. |
| [**website**](https://github.com/Theorvane/website) | The public sites for [Theorvane](https://theorvane.tech) and each product, including [TypeMCP](https://typemcp.theorvane.tech), [TypeChain](https://typechain.theorvane.tech), [OpenScene](https://openscene.app), [LabFox](https://labfox.theorvane.tech), [PlanGuard](https://planguard.theorvane.tech), and [Proxmox MCP](https://proxmox.theorvane.tech). | Public Next.js monorepo. |
| [**TypeChain**](https://github.com/Theorvane/type-chain) | Decorator-first, type-safe authoring layer for LangChain JS tools and agents. | [`@theorvane/type-chain@0.1.1`](https://www.npmjs.com/package/@theorvane/type-chain) is public on npm via GitHub Actions Trusted Publishing. Provides `@Tool()` / `@Agent()` / `@Policy()` decorators, LangChain Core adapters, and an in-process TypeMCP bridge. |
| [**OpenScene**](https://github.com/Theorvane/openscene) | A local-first desktop video editor with an AI agent that operates the timeline: reading a project, cutting clips, generating voice and video, and exporting through local FFmpeg. | Public Electron app in active development. Media stays on the machine, and model providers are opt-in — a local Ollama engine needs no account, while cloud providers are connected one key at a time. Runs from source; packaged installers and auto-updates are not yet available. Visit [openscene.app](https://openscene.app). |
| [**LabFox**](https://github.com/Theorvane/labfox) | A cross-platform GitLab workflow client (Flutter) for merge requests, code review, and CI/CD, with first-class self-hosted support on Android, iOS, Windows, and macOS. | Public repository in active development. Product site live at [labfox.theorvane.tech](https://labfox.theorvane.tech). |
| [**PlanGuard**](https://github.com/Theorvane/planguard) | An AI-assisted review platform for Terraform pull requests that surfaces the real risk in an infrastructure change before it merges, leaving the apply with your team. | Public repository in active development. Product site live at [planguard.theorvane.tech](https://planguard.theorvane.tech). |
| [**Proxmox MCP**](https://github.com/Theorvane/proxmox-mcp) | A safety-gated TypeMCP server for the Proxmox VE API that exposes virtualization operations behind explicit, auditable boundaries instead of raw access. | Public repository built on TypeMCP. Product site live at [proxmox.theorvane.tech](https://proxmox.theorvane.tech). |
| [**type-mcp-api-agent-skill**](https://github.com/Theorvane/type-mcp-api-agent-skill) | Hermes orchestration skill and deterministic CLI workspace for API-to-TypeMCP workflows. | Local OpenAPI/Swagger inspection is implemented; remote intake, generation, and the CLI package publication remain intentionally unshipped. |

## Open source, with clear boundaries

Open source should be usable and honest. Repository work may move ahead of a published package, so each project documents what is available today and what remains planned. Please rely on the package README and release notes for the current public API.

## Contributing

We welcome focused contributions:

1. Search existing Issues before starting work.
2. Open or update an Issue with the problem, scope, and acceptance criteria.
3. Keep pull requests small, tested, and aligned with the repository's `AGENTS.md`.
4. Do not include secrets, generated output, or unverified capability claims.

For a security concern, please follow our [security policy](../SECURITY.md) instead of creating a public Issue.

## Community

- Visit [theorvane.tech](https://theorvane.tech) for the studio and projects.
- Visit [typemcp.theorvane.tech](https://typemcp.theorvane.tech) for the TypeMCP product site.
- Use GitHub Issues in the relevant repository for reproducible bugs and scoped proposals.
