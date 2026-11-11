<div align="center">

<img src="banner.svg" width="100%" alt="Top AI Agent Guardrails"/>

# Top AI Agent Guardrails

<p><i>Guardrails for AI agents: sandboxes, human-in-the-loop approval, cost and budget limits, prompt-injection defenses and runtime policy checks, ranked by GitHub stars</i></p>

![Ranked by GitHub stars](https://img.shields.io/badge/ranked%20by-GitHub%20stars-orange?style=for-the-badge) ![GitHub stars](https://img.shields.io/badge/%E2%AD%90%20stars-repo-black?style=for-the-badge) ![License](https://img.shields.io/badge/license-CC0-0a7bbb?style=for-the-badge)

![entries](https://img.shields.io/badge/entries-60-blueviolet?style=for-the-badge) ![total stars](https://img.shields.io/badge/total%20stars-528.8k-gold?style=for-the-badge) ![updated](https://img.shields.io/badge/updated-2026--11--11-brightgreen?style=for-the-badge)

**English** · [简体中文](README.zh-CN.md)

</div>

---

## Contents

- [🏆 Top Picks](#top-picks)
- [Human Approval & Cost Limits](#sec-1) · 15
- [Guardrail Frameworks & Policy Engines](#sec-2) · 15
- [Agent Sandboxes](#sec-3) · 15
- [Prompt Injection & Runtime Security](#sec-4) · 15
- [📖 About this list](#about)

<a id="top-picks"></a>

## 🏆 Top Picks

| # | Project | ⭐ Stars | Language | Updated | Description |
|:-:|:--|--:|:-:|:-:|:--|
| 1 | [**cheaper-inference/OmniRoute**](https://github.com/cheaper-inference/OmniRoute) | 86.4k | TypeScript | 2026-11-11 | Never stop coding. Free MIT AI gateway: one endpoint, 375 providers (150+ free), 1,400+ models Kimi, Claude,… |
| 2 | [**BerriAI/litellm**](https://github.com/BerriAI/litellm) | 63.1k | Python | 2026-11-11 | The fastest, litest AI Gateway. Rust core with Python SDK. Call 100+ LLM APIs in OpenAI (or native) format wi… |
| 3 | [**QuantumNous/new-api**](https://github.com/QuantumNous/new-api) | 51.7k | Go | 2026-11-11 | Open-source AI gateway. Self-hosted LLM gateway with OpenAI-, Claude- and Gemini-compatible APIs, model routi… |
| 4 | [**ifixai-ai/iFixAi**](https://github.com/ifixai-ai/iFixAi) | 44.8k | Python | 2026-11-09 | Independent Auditing of AI Agents. Run by human or the agent itself, to answer the most crucial question in t… |
| 5 | [**NVIDIA/SkillSpector**](https://github.com/NVIDIA/SkillSpector) | 25.3k | Python | 2026-11-11 | Security scanner for AI agent skills. Detect vulnerabilities, malicious patterns, security risks, prompt inje… |

<a id="sec-1"></a>

## Human Approval & Cost Limits

| # | Project | ⭐ Stars | Language | Updated | Description |
|:-:|:--|--:|:-:|:-:|:--|
| 1 | [**cheaper-inference/OmniRoute**](https://github.com/cheaper-inference/OmniRoute) | 86.4k | TypeScript | 2026-11-11 | Never stop coding. Free MIT AI gateway: one endpoint, 375 providers (150+ free), 1,400+ models Kimi, Claude,… |
| 2 | [**QuantumNous/new-api**](https://github.com/QuantumNous/new-api) | 51.7k | Go | 2026-11-11 | Open-source AI gateway. Self-hosted LLM gateway with OpenAI-, Claude- and Gemini-compatible APIs, model routi… |
| 3 | [**humanlayer/humanlayer**](https://github.com/humanlayer/humanlayer) | 12.9k | TypeScript | 2026-11-05 | The best way to get AI coding agents to solve hard problems in complex codebases. |
| 4 | [**ThinkWatchProject/ThinkWatch**](https://github.com/ThinkWatchProject/ThinkWatch) | 817 | Rust | 2026-11-11 | Self-hosted AI API and MCP gateway for organizations: SSO and RBAC, per-user identity for MCP tool calls, PII… |
| 5 | [**respanai/respan-gateway**](https://github.com/respanai/respan-gateway) | 699 | Rust | 2026-11-11 | Open-source LLM gateway in Rust. One endpoint for OpenAI, Anthropic, Gemini and every other vendor. Any SDK,… |
| 6 | [**NadirRouter/NadirClaw**](https://github.com/NadirRouter/NadirClaw) | 665 | Python | 2026-11-10 | Source-available LLM router and AI cost optimizer. Routes simple prompts to cheap or local models and complex… |
| 7 | [**apache/casbin-gateway**](https://github.com/apache/casbin-gateway) | 649 | Go | 2026-10-31 | See what every AI coding agent on your machine is doing, and whether the API behind it is the one you paid fo… |
| 8 | [**Justin0504/Aegis**](https://github.com/Justin0504/Aegis) | 523 | TypeScript | 2026-10-31 | Runtime policy enforcement for AI agents. Cryptographic audit trail, human-in-the-loop approvals, kill switch… |
| 9 | [**cordum-io/cordum**](https://github.com/cordum-io/cordum) | 510 | Go | 2026-11-11 | The action firewall for AI agents. Enforce policy and human approval before risky tool calls, shell commands,… |
| 10 | [**eliasbiondo/antirion**](https://github.com/eliasbiondo/antirion) | 457 | Rust | 2026-11-07 | 🕷️ The fastest open-source AI Gateway and LLM Gateway — one binary with built-in console to route, secure, bu… |

<details>
<summary>Show 5 more</summary>

| # | Project | ⭐ Stars | Language | Updated | Description |
|:-:|:--|--:|:-:|:-:|:--|
| 11 | [**clawvisor/clawvisor**](https://github.com/clawvisor/clawvisor) | 286 | Go | 2026-10-31 | API gateway for purpose-based authorization for AI agents. Human approval for tasks, AI-native enforcement fo… |
| 12 | [**Tencent/LoopForge**](https://github.com/Tencent/LoopForge) | 271 | Go | 2026-11-11 | Self-hosted workflows for coding-agent delivery. Orchestrate CodeBuddy, Codex and Claude Code with scripts an… |
| 13 | [**MaxInGaussian/pi-plans**](https://github.com/MaxInGaussian/pi-plans) | 239 | TypeScript | 2026-10-11 | Human-in-the-loop planning extension for the Pi coding agent. Turns rough change requests into versioned Mark… |
| 14 | [**edwinkys/phantasm**](https://github.com/edwinkys/phantasm) | 196 | Svelte | 2024-11-28 | Toolkits to create a human-in-the-loop approval layer to monitor and guide AI agents workflow in real-time. |
| 15 | [**decionis/docker**](https://github.com/decionis/docker) | 148 | Go | 2026-08-25 | Govern consequential AI agent actions in Docker with deterministic policy, human approval, and signed Decisio… |

</details>

<a id="sec-2"></a>

## Guardrail Frameworks & Policy Engines

| # | Project | ⭐ Stars | Language | Updated | Description |
|:-:|:--|--:|:-:|:-:|:--|
| 1 | [**BerriAI/litellm**](https://github.com/BerriAI/litellm) | 63.1k | Python | 2026-11-11 | The fastest, litest AI Gateway. Rust core with Python SDK. Call 100+ LLM APIs in OpenAI (or native) format wi… |
| 2 | [**Portkey-AI/gateway**](https://github.com/Portkey-AI/gateway) | 13.4k | TypeScript | 2026-05-25 | A blazing fast AI Gateway with integrated guardrails. Route to 1,600+ LLMs, 50+ AI Guardrails with 1 fast & f… |
| 3 | [**data-privacy-stack/presidio**](https://github.com/data-privacy-stack/presidio) | 11.8k | Python | 2026-11-10 | An open-source framework for detecting, redacting, masking, and anonymizing sensitive data (PII) across text,… |
| 4 | [**maximhq/bifrost**](https://github.com/maximhq/bifrost) | 9.5k | Go | 2026-11-11 | Open-source, high-performance AI gateway that works as your LLM gateway, MCP gateway and agent gateway. One O… |
| 5 | [**FailproofAI/failproofai**](https://github.com/FailproofAI/failproofai) | 8.4k | TypeScript | 2026-11-10 | Observability and enforcement for AI agent harnesses. Capture every run and runtime reliability with policy e… |
| 6 | [**NVIDIA-NeMo/Guardrails**](https://github.com/NVIDIA-NeMo/Guardrails) | 7.5k | Python | 2026-11-11 | NeMo Guardrails is an open-source toolkit for easily adding programmable guardrails to LLM-based conversation… |
| 7 | [**katanemo/plano**](https://github.com/katanemo/plano) | 7.1k | Rust | 2026-10-24 | Plano is an AI-native proxy server and data plane for agentic apps. Smart LLM routing, observability, agent o… |
| 8 | [**superagent-ai/superagent**](https://github.com/superagent-ai/superagent) | 6.9k | TypeScript | 2026-08-25 | Superagent protects your AI applications against prompt injections, data leaks, and harmful outputs. Embed sa… |
| 9 | [**lennney/stop-that-shit**](https://github.com/lennney/stop-that-shit) | 3.8k | JavaScript | 2026-11-10 | Chinese-language project; see the repo for details |
| 10 | [**confident-ai/deepteam**](https://github.com/confident-ai/deepteam) | 3.1k | Python | 2026-10-23 | DeepTeam is a framework to red team LLMs and AI agents. |

<details>
<summary>Show 5 more</summary>

| # | Project | ⭐ Stars | Language | Updated | Description |
|:-:|:--|--:|:-:|:-:|:--|
| 11 | [**msoedov/agentic_security**](https://github.com/msoedov/agentic_security) | 2.0k | Python | 2026-11-04 | Agentic LLM Vulnerability Scanner / AI red teaming kit 🧪 |
| 12 | [**kenryu42/cc-safety-net**](https://github.com/kenryu42/cc-safety-net) | 2.0k | TypeScript | 2026-11-11 | A pre-execution guard for AI coding agents. It blocks destructive Git and file system commands, plus common a… |
| 13 | [**archestra-ai/OpenAPPA**](https://github.com/archestra-ai/OpenAPPA) | 1.6k | Rust | 2026-11-11 | Deterministic guardrails that don't break agents |
| 14 | [**akto-api-security/akto**](https://github.com/akto-api-security/akto) | 1.5k | Java | 2026-11-11 | Akto is the fastest growing AI Security platform for your teams to secure AI agents, MCPs, LLMs, Agent skills… |
| 15 | [**hoophq/hoop**](https://github.com/hoophq/hoop) | 854 | Go | 2026-11-11 | Open-source enforcement at runtime that masks sensitive data and blocks destructive commands from AI agents.… |

</details>

<a id="sec-3"></a>

## Agent Sandboxes

| # | Project | ⭐ Stars | Language | Updated | Description |
|:-:|:--|--:|:-:|:-:|:--|
| 1 | [**wasmerio/wasmer**](https://github.com/wasmerio/wasmer) | 21.2k | Rust | 2026-11-10 | 🚀 Fast and lightweight sandboxes for your apps and AI agents |
| 2 | [**opensandbox-group/OpenSandbox**](https://github.com/opensandbox-group/OpenSandbox) | 17.2k | Go | 2026-11-11 | Secure, Fast, and Extensible Sandbox runtime for AI agents. |
| 3 | [**TencentCloud/CubeSandbox**](https://github.com/TencentCloud/CubeSandbox) | 13.2k | Go | 2026-11-11 | Instant, Concurrent, Secure & Lightweight Sandbox for AI Agents. |
| 4 | [**mattpocock/sandcastle**](https://github.com/mattpocock/sandcastle) | 9.0k | TypeScript | 2026-11-11 | Orchestrate sandboxed coding agents in TypeScript with sandcastle.run() |
| 5 | [**withastro/flue**](https://github.com/withastro/flue) | 8.6k | TypeScript | 2026-11-07 | The sandbox agent framework. |
| 6 | [**smol-machines/smolvm**](https://github.com/smol-machines/smolvm) | 7.1k | Rust | 2026-11-10 | An embeddable, portable, branchable virtual machine to safely run Agents locally. |
| 7 | [**microsoft/agent-governance-toolkit**](https://github.com/microsoft/agent-governance-toolkit) | 6.6k | Python | 2026-11-10 | AI Agent Governance Toolkit — Policy enforcement, zero-trust identity, execution sandboxing, and reliability… |
| 8 | [**agent-infra/sandbox**](https://github.com/agent-infra/sandbox) | 6.3k | Python | 2026-09-14 | All-in-One Sandbox for AI Agents that combines Browser, Shell, File, MCP and VSCode Server in a single Docker… |
| 9 | [**deeplethe/sandstorm**](https://github.com/deeplethe/sandstorm) | 6.1k | Rust | 2026-11-01 | Run thousands of AI agent sandboxes on the cheapest machines. |
| 10 | [**nolabs-ai/nono**](https://github.com/nolabs-ai/nono) | 4.9k | Rust | 2026-11-10 | agent runtime security - zero trust, zero setup, zero latency agent sandboxing |

<details>
<summary>Show 5 more</summary>

| # | Project | ⭐ Stars | Language | Updated | Description |
|:-:|:--|--:|:-:|:-:|:--|
| 11 | [**rivet-dev/agentos**](https://github.com/rivet-dev/agentos) | 4.9k | Rust | 2026-11-11 | Tiny, fast, Linux-compatible sandboxes. Powered by WebAssembly. |
| 12 | [**kubernetes-sigs/agent-sandbox**](https://github.com/kubernetes-sigs/agent-sandbox) | 4.6k | Go | 2026-11-11 | agent-sandbox enables easy management of isolated, stateful, singleton workloads, ideal for use cases like AI… |
| 13 | [**sandbox-quantum/switch**](https://github.com/sandbox-quantum/switch) | 4.4k | Python | 2026-11-11 | Open-source AI teammates in Slack, Teams, Discord, Telegram and Mattermost. Self-host it, with any agent harn… |
| 14 | [**arcboxlabs/arcbox**](https://github.com/arcboxlabs/arcbox) | 4.3k | Rust | 2026-11-09 | Run AI agents on real and isolated machines — own kernel, filesystem, and network — with <100ms boot. Local f… |
| 15 | [**onecli/onecli**](https://github.com/onecli/onecli) | 3.6k | TypeScript | 2026-11-09 | Open-source sandboxed agent harness for teams. Giving every employee a secured personal agent. |

</details>

<a id="sec-4"></a>

## Prompt Injection & Runtime Security

| # | Project | ⭐ Stars | Language | Updated | Description |
|:-:|:--|--:|:-:|:-:|:--|
| 1 | [**ifixai-ai/iFixAi**](https://github.com/ifixai-ai/iFixAi) | 44.8k | Python | 2026-11-09 | Independent Auditing of AI Agents. Run by human or the agent itself, to answer the most crucial question in t… |
| 2 | [**NVIDIA/SkillSpector**](https://github.com/NVIDIA/SkillSpector) | 25.3k | Python | 2026-11-11 | Security scanner for AI agent skills. Detect vulnerabilities, malicious patterns, security risks, prompt inje… |
| 3 | [**NVIDIA/garak**](https://github.com/NVIDIA/garak) | 10.0k | Python | 2026-11-06 | the LLM vulnerability scanner |
| 4 | [**Tencent/AI-Infra-Guard**](https://github.com/Tencent/AI-Infra-Guard) | 7.5k | Python | 2026-11-11 | A full-stack AI Red Teaming platform securing AI ecosystems via Agent Scan, Skills Scan, MCP scan, AI Infra s… |
| 5 | [**Giskard-AI/giskard-oss**](https://github.com/Giskard-AI/giskard-oss) | 5.9k | Python | 2026-11-10 | 🐢 Open-Source Evaluation & Testing library for LLM Agents |
| 6 | [**stacklok/toolhive**](https://github.com/stacklok/toolhive) | 2.3k | Go | 2026-11-11 | ToolHive is an enterprise-grade platform for running and managing Model Context Protocol (MCP) servers. |
| 7 | [**uber/ADR**](https://github.com/uber/ADR) | 2.1k | Python | 2026-10-31 | ADR secures enterprise AI agents through observability, security benchmarking, and threat detection. Deployed… |
| 8 | [**cyberark/FuzzyAI**](https://github.com/cyberark/FuzzyAI) | 1.6k | Jupyter Notebook | 2026-02-06 | A powerful tool for automated LLM fuzzing. It is designed to help developers and security researchers identif… |
| 9 | [**OWASP/www-project-top-10-for-large-language-model-applicati…**](https://github.com/OWASP/www-project-top-10-for-large-language-model-applications) | 1.5k | Python | 2026-08-05 | OWASP Top 10 for Large Language Model Apps (Part of the GenAI Security Project) |
| 10 | [**tophant-ai/aibeat**](https://github.com/tophant-ai/aibeat) | 1.4k | HTML | 2026-10-21 | Break your AI before they do. Join Discord: https://discord.gg/n22d9s3xM |

<details>
<summary>Show 5 more</summary>

| # | Project | ⭐ Stars | Language | Updated | Description |
|:-:|:--|--:|:-:|:-:|:--|
| 11 | [**utkusen/promptmap**](https://github.com/utkusen/promptmap) | 1.3k | Python | 2025-12-01 | a security scanner for custom LLM applications |
| 12 | [**hashgraph-online/hol-guard**](https://github.com/hashgraph-online/hol-guard) | 1.1k | Rust | 2026-11-11 | Open-source antivirus and firewall for AI agents: block risky tools, secret access, prompt injection, malicio… |
| 13 | [**splx-ai/agentic-radar**](https://github.com/splx-ai/agentic-radar) | 1.1k | Python | 2025-11-27 | A security scanner for your LLM agentic workflows |
| 14 | [**Pantheon-Security/medusa**](https://github.com/Pantheon-Security/medusa) | 1.0k | Python | 2026-08-10 | AI-first security scanner. NEW in v2026.7: Claude Code compromise detection — vet .claude/ hooks, permissions… |
| 15 | [**whylabs/langkit**](https://github.com/whylabs/langkit) | 1.0k | Jupyter Notebook | 2024-11-22 | 🔍 LangKit: An open-source toolkit for monitoring Large Language Models (LLMs). 📚 Extracts signals from prompt… |

</details>

<a id="about"></a>

## 📖 About this list

This list is collected from GitHub, deduplicated, link-checked and ranked by stars (recency breaks ties). It is regenerated automatically on a schedule, so numbers stay fresh.

---

<div align="center">

<sub>Auto-generated · refreshed on a schedule · ranked by GitHub stars · 2026-11-11</sub>

</div>
