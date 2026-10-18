---
title: HVE Core
description: Agentic SDLC framework for context management, governance, shift-left engineering, reusable organizational knowledge, and consistent practices across teams
author: Microsoft
ms.date: 2026-10-02
ms.topic: overview
keywords:
  - hypervelocity engineering
  - github copilot
  - ai workflows
  - custom agents
  - copilot instructions
  - rpi methodology
estimated_reading_time: 3
---

## Hypervelocity Engineering (HVE) Core

<!-- markdownlint-disable MD013 -->
[![CI Status](https://github.com/microsoft/hve-core/actions/workflows/release-stable.yml/badge.svg)](https://github.com/microsoft/hve-core/actions/workflows/release-stable.yml)
[![CodeQL](https://github.com/microsoft/hve-core/actions/workflows/codeql-analysis.yml/badge.svg)](https://github.com/microsoft/hve-core/actions/workflows/codeql-analysis.yml)
[![OpenSSF Scorecard](https://api.scorecard.dev/projects/github.com/microsoft/hve-core/badge)](https://scorecard.dev/viewer/?uri=github.com/microsoft/hve-core)
[![OpenSSF Best Practices](https://www.bestpractices.dev/projects/11795/badge)](https://www.bestpractices.dev/projects/11795)
[![License](https://img.shields.io/github/license/microsoft/hve-core)](./LICENSE)
[![Documentation](https://img.shields.io/badge/docs-microsoft.github.io%2Fhve--core-blue)](https://microsoft.github.io/hve-core/)
<!-- markdownlint-enable MD013 -->

HVE Core helps teams ship faster with GitHub Copilot by combining specialized agents, reusable prompts, coding instructions, and validated skills into one workflow system.

Use HVE Core when you want AI-assisted work to be repeatable, standards-aligned, and scalable across individuals and teams. HVE Core provides structured AI workflow building blocks:

* Agents for specialized tasks such as research, planning, implementation, and review
* Prompts for repeatable workflow entry points
* Instructions that apply coding standards automatically
* Skills that add reusable tool capabilities

> [!CAUTION]
> HVE Core is a rapidly evolving agentic SDLC framework. It is a source of patterns and learning. You would need to develop further enhancements to deploy for production.
>
> As the technology landscape evolves, workflows, interfaces, architecture, and recommended practices may change substantially, including in ways that are not backward compatible. Evaluate all materials for your own requirements and risk tolerance.
>
> The HVE Builder skill (use with `/hve-builder`) and GitHub Copilot can help you adapt or copy relevant patterns into an agentic SDLC that you own and maintain independently.
>
> To build an independent implementation, start with [Forking and Extending HVE Core](docs/customization/forking.md) and review the [HVE Core documentation](docs/README.md) before adopting any component.

## Quick Start

<!-- markdownlint-disable MD013 -->
[![Install HVE Core](https://img.shields.io/badge/VS%20Code-Install%20HVE%20Core-007ACC?logo=visualstudiocode&logoColor=white)](https://marketplace.visualstudio.com/items?itemName=ise-hve-essentials.hve-core)
<!-- markdownlint-enable MD036 -->

1. Install the [HVE Core extension](https://marketplace.visualstudio.com/items?itemName=ise-hve-essentials.hve-core) from the VS Code Marketplace.
2. Open any project and launch GitHub Copilot Chat (`Ctrl+Alt+I`).
3. Select **RPI Agent** from the agent picker, then describe the task you want to complete.

> [!TIP]
> Using GitHub Copilot CLI? Register the consolidated HVE Core marketplace and
> install its plugin:
>
> ```bash
> copilot plugin marketplace add microsoft/hve-core
> copilot plugin install hve-core@hve-core
> ```
>
> Duplicate same-name registration behavior can vary by Copilot CLI version. See
> [CLI Plugins](docs/getting-started/methods/cli-plugins.md) for details.

## Choose Your Path

* New to HVE-Core: Start with [Start Here](docs/getting-started/README.md) to complete your first workflow quickly.
* Microsoft Partner Workshop: Follow the [Getting Started with HVE Partner Workshop](docs/getting-started/README.md) for workshop-specific onboarding.
* Leading a team: Use the [Team Adoption Guide](docs/customization/team-adoption.md) to roll out standards and onboarding.
* Contributing to this repo: Follow the [Contributing Guide](CONTRIBUTING.md) to add or improve agents, prompts, instructions, and skills.

## Navigate This Repository

|------------------------------|--------------------------------------------------------------------|
| Start with the partner workshop | [docs/getting-started/README.md](docs/getting-started/README.md)   |
| Understand all setup options | [docs/getting-started/install.md](docs/getting-started/install.md) |
| Learn the core methodology   | [docs/rpi/README.md](docs/rpi/README.md)                           |
| Browse docs by topic         | [docs/README.md](docs/README.md)                                   |
| Explore agents               | [.github/CUSTOM-AGENTS.md](.github/CUSTOM-AGENTS.md)               |
| Explore instructions         | [.github/instructions/README.md](.github/instructions/README.md)   |
| Explore skills               | [.github/skills/](.github/skills/)                                 |

## Documentation

Full documentation is available at **<https://microsoft.github.io/hve-core/>**.

| Guide                                                            | Description                                      |
|------------------------------------------------------------------|--------------------------------------------------|
| [Getting Started](docs/getting-started/README.md)                | Setup and first workflow tutorial                |
| [HVE Core Identity](docs/getting-started/packages.md)            | Distribution channels and lifecycle disclosure   |
| [Plugin Inventory](docs/plugins/hve-core.md)                     | One-plugin identity and included capabilities    |
| [Package Migration](docs/getting-started/package-migration.md)   | Move from retired distribution identities        |
| [RPI Workflow](docs/rpi/README.md)                               | Deep dive into Research, Plan, Implement, Review |
| [Contributing](docs/contributing/README.md)                      | Create custom agents, instructions, and prompts  |
| [Agents Reference](.github/CUSTOM-AGENTS.md)                     | All available agents                             |
| [Instructions Reference](.github/instructions/README.md)         | All coding instructions                          |
| [AI Artifacts Architecture](docs/architecture/ai-artifacts.md)   | Prompt engineering framework and artifact types  |
| [Validation Standards](docs/contributing/ai-artifacts-common.md) | CI/CD validation pipeline and quality gates      |

## Contributing

We appreciate contributions! Whether you're fixing typos or adding new components:

1. Read our [Contributing Guide](CONTRIBUTING.md).
2. Check out [open issues](https://github.com/microsoft/hve-core/issues).
3. Join the [discussion](https://github.com/microsoft/hve-core/discussions).

## Responsible AI

Microsoft encourages customers to review its Responsible AI Standard when developing AI-enabled systems to ensure ethical, safe, and inclusive AI practices. Learn more at [Microsoft's Responsible AI](https://www.microsoft.com/ai/responsible-ai).

---

<!-- markdownlint-disable MD036 -->
*🤖 Crafted with precision by ✨Copilot following brilliant human instruction,
then carefully refined by our team of discerning human reviewers.*
<!-- markdownlint-enable MD036 -->
