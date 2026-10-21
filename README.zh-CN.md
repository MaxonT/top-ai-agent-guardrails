<div align="center">

<img src="banner.svg" width="100%" alt="AI Agent 安全护栏大全"/>

# AI Agent 安全护栏大全

<p><i>AI Agent 安全护栏：沙箱、人工审批、成本上限、提示注入防护与运行时行为核验，按 GitHub Stars 排名</i></p>

![Ranked by GitHub stars](https://img.shields.io/badge/ranked%20by-GitHub%20stars-orange?style=for-the-badge) ![GitHub stars](https://img.shields.io/badge/%E2%AD%90%20stars-repo-black?style=for-the-badge) ![License](https://img.shields.io/badge/license-CC0-0a7bbb?style=for-the-badge)

![条目](https://img.shields.io/badge/%E6%9D%A1%E7%9B%AE-60-blueviolet?style=for-the-badge) ![总 Stars](https://img.shields.io/badge/%E6%80%BB%20Stars-354.5k-gold?style=for-the-badge) ![更新于](https://img.shields.io/badge/%E6%9B%B4%E6%96%B0%E4%BA%8E-2026--10--21-brightgreen?style=for-the-badge)

[English](README.md) · **简体中文**

</div>

---

## 目录

- [🏆 精选 Top](#top-picks)
- [Guardrail Frameworks & Policy Engines](#sec-1) · 15
- [Agent Sandboxes](#sec-2) · 15
- [Prompt Injection & Runtime Security](#sec-3) · 15
- [Human Approval & Cost Limits](#sec-4) · 15
- [📖 关于本列表](#about)

<a id="top-picks"></a>

## 🏆 精选 Top

| # | 项目 | ⭐ Stars | 语言 | 更新 | 简介 |
|:-:|:--|--:|:-:|:-:|:--|
| 1 | [**BerriAI/litellm**](https://github.com/BerriAI/litellm) | 61.7k | Python | 2026-10-21 | The fastest, litest AI Gateway. Rust core with Python SDK. Call 100+ LLM APIs in OpenAI (or native) format wi… |
| 2 | [**ifixai-ai/iFixAi**](https://github.com/ifixai-ai/iFixAi) | 30.9k | Python | 2026-10-21 | Independent Auditing of AI Agents. Run by human or the agent itself, to answer the most crucial question in t… |
| 3 | [**wasmerio/wasmer**](https://github.com/wasmerio/wasmer) | 21.2k | Rust | 2026-10-20 | 🚀 Fast and lightweight sandboxes for your apps and AI agents |
| 4 | [**NVIDIA/SkillSpector**](https://github.com/NVIDIA/SkillSpector) | 20.8k | Python | 2026-10-21 | Security scanner for AI agent skills. Detect vulnerabilities, malicious patterns, security risks, prompt inje… |
| 5 | [**opensandbox-group/OpenSandbox**](https://github.com/opensandbox-group/OpenSandbox) | 16.0k | Python | 2026-10-21 | Secure, Fast, and Extensible Sandbox runtime for AI agents. |

<a id="sec-1"></a>

## Guardrail Frameworks & Policy Engines

| # | 项目 | ⭐ Stars | 语言 | 更新 | 简介 |
|:-:|:--|--:|:-:|:-:|:--|
| 1 | [**BerriAI/litellm**](https://github.com/BerriAI/litellm) | 61.7k | Python | 2026-10-21 | The fastest, litest AI Gateway. Rust core with Python SDK. Call 100+ LLM APIs in OpenAI (or native) format wi… |
| 2 | [**Portkey-AI/gateway**](https://github.com/Portkey-AI/gateway) | 13.2k | TypeScript | 2026-05-25 | A blazing fast AI Gateway with integrated guardrails. Route to 1,600+ LLMs, 50+ AI Guardrails with 1 fast & f… |
| 3 | [**data-privacy-stack/presidio**](https://github.com/data-privacy-stack/presidio) | 11.4k | Python | 2026-10-19 | An open-source framework for detecting, redacting, masking, and anonymizing sensitive data (PII) across text,… |
| 4 | [**maximhq/bifrost**](https://github.com/maximhq/bifrost) | 9.0k | Go | 2026-10-21 | Open-source, high-performance AI gateway that works as your LLM gateway, MCP gateway and agent gateway. One O… |
| 5 | [**NVIDIA-NeMo/Guardrails**](https://github.com/NVIDIA-NeMo/Guardrails) | 7.3k | Python | 2026-10-21 | NeMo Guardrails is an open-source toolkit for easily adding programmable guardrails to LLM-based conversation… |
| 6 | [**katanemo/plano**](https://github.com/katanemo/plano) | 7.1k | Rust | 2026-10-07 | Plano is an AI-native proxy server and data plane for agentic apps. Smart LLM routing, observability, agent o… |
| 7 | [**superagent-ai/superagent**](https://github.com/superagent-ai/superagent) | 6.8k | TypeScript | 2026-08-25 | Superagent protects your AI applications against prompt injections, data leaks, and harmful outputs. Embed sa… |
| 8 | [**FailproofAI/failproofai**](https://github.com/FailproofAI/failproofai) | 6.0k | TypeScript | 2026-10-21 | Observability and enforcement for AI agent harnesses. Capture every run and runtime reliability with policy e… |
| 9 | [**confident-ai/deepteam**](https://github.com/confident-ai/deepteam) | 3.0k | Python | 2026-10-20 | DeepTeam is a framework to red team LLMs and AI agents. |
| 10 | [**lennney/stop-that-shit**](https://github.com/lennney/stop-that-shit) | 2.9k | JavaScript | 2026-10-19 | Stop That Shit（别再造史了）｜面向 Codex/GPT 场景的多平台 Hook + Skill Guard：拦截 AI coding agent 无需求的哈希、校验和与任务范围膨胀。 A multi-pl… |

<details>
<summary>展开其余 5 项</summary>

| # | 项目 | ⭐ Stars | 语言 | 更新 | 简介 |
|:-:|:--|--:|:-:|:-:|:--|
| 11 | [**msoedov/agentic_security**](https://github.com/msoedov/agentic_security) | 2.0k | Python | 2026-10-19 | Agentic LLM Vulnerability Scanner / AI red teaming kit 🧪 |
| 12 | [**kenryu42/cc-safety-net**](https://github.com/kenryu42/cc-safety-net) | 1.7k | TypeScript | 2026-10-21 | A pre-execution guard for AI coding agents. It blocks destructive Git and file system commands, plus common a… |
| 13 | [**archestra-ai/OpenAPPA**](https://github.com/archestra-ai/OpenAPPA) | 1.6k | Rust | 2026-10-20 | Deterministic guardrails that don't break agents |
| 14 | [**akto-api-security/akto**](https://github.com/akto-api-security/akto) | 1.5k | Java | 2026-10-21 | Akto is the fastest growing AI Security platform for your teams to secure AI agents, MCPs, LLMs, Agent skills… |
| 15 | [**hoophq/hoop**](https://github.com/hoophq/hoop) | 831 | Go | 2026-10-20 | Open-source enforcement at runtime that masks sensitive data and blocks destructive commands from AI agents.… |

</details>

<a id="sec-2"></a>

## Agent Sandboxes

| # | 项目 | ⭐ Stars | 语言 | 更新 | 简介 |
|:-:|:--|--:|:-:|:-:|:--|
| 1 | [**wasmerio/wasmer**](https://github.com/wasmerio/wasmer) | 21.2k | Rust | 2026-10-20 | 🚀 Fast and lightweight sandboxes for your apps and AI agents |
| 2 | [**opensandbox-group/OpenSandbox**](https://github.com/opensandbox-group/OpenSandbox) | 16.0k | Python | 2026-10-21 | Secure, Fast, and Extensible Sandbox runtime for AI agents. |
| 3 | [**TencentCloud/CubeSandbox**](https://github.com/TencentCloud/CubeSandbox) | 13.0k | Go | 2026-10-21 | Instant, Concurrent, Secure & Lightweight Sandbox for AI Agents. |
| 4 | [**mattpocock/sandcastle**](https://github.com/mattpocock/sandcastle) | 8.6k | TypeScript | 2026-10-20 | Orchestrate sandboxed coding agents in TypeScript with sandcastle.run() |
| 5 | [**withastro/flue**](https://github.com/withastro/flue) | 8.5k | TypeScript | 2026-10-17 | The sandbox agent framework. |
| 6 | [**smol-machines/smolvm**](https://github.com/smol-machines/smolvm) | 6.8k | Rust | 2026-10-21 | An embeddable, portable, branchable virtual machine to safely run Agents locally. |
| 7 | [**microsoft/agent-governance-toolkit**](https://github.com/microsoft/agent-governance-toolkit) | 6.4k | Python | 2026-10-21 | AI Agent Governance Toolkit — Policy enforcement, zero-trust identity, execution sandboxing, and reliability… |
| 8 | [**agent-infra/sandbox**](https://github.com/agent-infra/sandbox) | 6.2k | Python | 2026-09-14 | All-in-One Sandbox for AI Agents that combines Browser, Shell, File, MCP and VSCode Server in a single Docker… |
| 9 | [**rivet-dev/agentos**](https://github.com/rivet-dev/agentos) | 4.8k | Rust | 2026-10-21 | Tiny, fast, Linux-compatible sandboxes. Powered by WebAssembly. |
| 10 | [**nolabs-ai/nono**](https://github.com/nolabs-ai/nono) | 4.6k | Rust | 2026-10-20 | agent runtime security - zero trust, zero setup, zero latency agent sandboxing |

<details>
<summary>展开其余 5 项</summary>

| # | 项目 | ⭐ Stars | 语言 | 更新 | 简介 |
|:-:|:--|--:|:-:|:-:|:--|
| 11 | [**kubernetes-sigs/agent-sandbox**](https://github.com/kubernetes-sigs/agent-sandbox) | 4.3k | Go | 2026-10-21 | agent-sandbox enables easy management of isolated, stateful, singleton workloads, ideal for use cases like AI… |
| 12 | [**arcboxlabs/arcbox**](https://github.com/arcboxlabs/arcbox) | 4.2k | Rust | 2026-10-20 | Run AI agents on real and isolated machines — own kernel, filesystem, and network — with <100ms boot. Local f… |
| 13 | [**onecli/onecli**](https://github.com/onecli/onecli) | 3.6k | TypeScript | 2026-10-14 | Open-source sandboxed agent harness for teams. Giving every employee a secured personal agent. |
| 14 | [**deeplethe/forkd**](https://github.com/deeplethe/forkd) | 2.9k | Rust | 2026-09-14 | Fork() for AI agent microVMs. Spawn 100 children in ~100ms from a warm parent; BRANCH a live VM in ~150ms. KV… |
| 15 | [**zerobootdev/zeroboot**](https://github.com/zerobootdev/zeroboot) | 2.5k | Rust | 2026-10-18 | Sub-millisecond VM sandboxes for AI agents via copy-on-write forking |

</details>

<a id="sec-3"></a>

## Prompt Injection & Runtime Security

| # | 项目 | ⭐ Stars | 语言 | 更新 | 简介 |
|:-:|:--|--:|:-:|:-:|:--|
| 1 | [**ifixai-ai/iFixAi**](https://github.com/ifixai-ai/iFixAi) | 30.9k | Python | 2026-10-21 | Independent Auditing of AI Agents. Run by human or the agent itself, to answer the most crucial question in t… |
| 2 | [**NVIDIA/SkillSpector**](https://github.com/NVIDIA/SkillSpector) | 20.8k | Python | 2026-10-21 | Security scanner for AI agent skills. Detect vulnerabilities, malicious patterns, security risks, prompt inje… |
| 3 | [**NVIDIA/garak**](https://github.com/NVIDIA/garak) | 9.6k | Python | 2026-10-20 | the LLM vulnerability scanner |
| 4 | [**Tencent/AI-Infra-Guard**](https://github.com/Tencent/AI-Infra-Guard) | 6.9k | Python | 2026-10-21 | A full-stack AI Red Teaming platform securing AI ecosystems via Agent Scan, Skills Scan, MCP scan, AI Infra s… |
| 5 | [**Giskard-AI/giskard-oss**](https://github.com/Giskard-AI/giskard-oss) | 5.9k | Python | 2026-10-20 | 🐢 Open-Source Evaluation & Testing library for LLM Agents |
| 6 | [**stacklok/toolhive**](https://github.com/stacklok/toolhive) | 2.3k | Go | 2026-10-21 | ToolHive is an enterprise-grade platform for running and managing Model Context Protocol (MCP) servers. |
| 7 | [**uber/ADR**](https://github.com/uber/ADR) | 2.1k | Python | 2026-10-19 | ADR secures enterprise AI agents through observability, security benchmarking, and threat detection. Deployed… |
| 8 | [**cyberark/FuzzyAI**](https://github.com/cyberark/FuzzyAI) | 1.6k | Jupyter Notebook | 2026-02-06 | A powerful tool for automated LLM fuzzing. It is designed to help developers and security researchers identif… |
| 9 | [**OWASP/www-project-top-10-for-large-language-model-applicati…**](https://github.com/OWASP/www-project-top-10-for-large-language-model-applications) | 1.5k | Python | 2026-08-05 | OWASP Top 10 for Large Language Model Apps (Part of the GenAI Security Project) |
| 10 | [**tophant-ai/aibeat**](https://github.com/tophant-ai/aibeat) | 1.4k | HTML | 2026-10-21 | Break your AI before they do. Join Discord: https://discord.gg/NXXz8JG74 |

<details>
<summary>展开其余 5 项</summary>

| # | 项目 | ⭐ Stars | 语言 | 更新 | 简介 |
|:-:|:--|--:|:-:|:-:|:--|
| 11 | [**utkusen/promptmap**](https://github.com/utkusen/promptmap) | 1.3k | Python | 2025-12-01 | a security scanner for custom LLM applications |
| 12 | [**splx-ai/agentic-radar**](https://github.com/splx-ai/agentic-radar) | 1.1k | Python | 2025-11-27 | A security scanner for your LLM agentic workflows |
| 13 | [**ZeroDayEvil/ai-security-tool**](https://github.com/ZeroDayEvil/ai-security-tool) | 1.0k | HTML | 2026-10-18 | 🛡️ Free open-source AI-powered security terminal & vulnerability scanner (CVE, SBOM). Supports SSH, SFTP, RDP… |
| 14 | [**Pantheon-Security/medusa**](https://github.com/Pantheon-Security/medusa) | 1.0k | Python | 2026-08-10 | AI-first security scanner. NEW in v2026.7: Claude Code compromise detection — vet .claude/ hooks, permissions… |
| 15 | [**whylabs/langkit**](https://github.com/whylabs/langkit) | 1.0k | Jupyter Notebook | 2024-11-22 | 🔍 LangKit: An open-source toolkit for monitoring Large Language Models (LLMs). 📚 Extracts signals from prompt… |

</details>

<a id="sec-4"></a>

## Human Approval & Cost Limits

| # | 项目 | ⭐ Stars | 语言 | 更新 | 简介 |
|:-:|:--|--:|:-:|:-:|:--|
| 1 | [**humanlayer/humanlayer**](https://github.com/humanlayer/humanlayer) | 11.7k | TypeScript | 2026-10-15 | The best way to get AI coding agents to solve hard problems in complex codebases. |
| 2 | [**ThinkWatchProject/ThinkWatch**](https://github.com/ThinkWatchProject/ThinkWatch) | 822 | Rust | 2026-10-20 | Self-hosted AI API and MCP gateway for organizations: SSO and RBAC, per-user identity for MCP tool calls, PII… |
| 3 | [**NadirRouter/NadirClaw**](https://github.com/NadirRouter/NadirClaw) | 661 | Python | 2026-10-21 | Source-available LLM router and AI cost optimizer. Routes simple prompts to cheap or local models and complex… |
| 4 | [**apache/casbin-gateway**](https://github.com/apache/casbin-gateway) | 643 | Go | 2026-10-21 | See what every AI coding agent on your machine is doing, and whether the API behind it is the one you paid fo… |
| 5 | [**Justin0504/Aegis**](https://github.com/Justin0504/Aegis) | 543 | TypeScript | 2026-10-09 | Runtime policy enforcement for AI agents. Cryptographic audit trail, human-in-the-loop approvals, kill switch… |
| 6 | [**cordum-io/cordum**](https://github.com/cordum-io/cordum) | 511 | Go | 2026-10-21 | The action firewall for AI agents. Enforce policy and human approval before risky tool calls, shell commands,… |
| 7 | [**clawvisor/clawvisor**](https://github.com/clawvisor/clawvisor) | 283 | Go | 2026-10-19 | API gateway for purpose-based authorization for AI agents. Human approval for tasks, AI-native enforcement fo… |
| 8 | [**ferro-labs/ai-gateway**](https://github.com/ferro-labs/ai-gateway) | 272 | Go | 2026-10-19 | Unified AI Gateway for 30+ LLMs (OpenAI, Anthropic, Bedrock, Azure etc) with Caching, Guardrails, A/B test &… |
| 9 | [**MaxInGaussian/pi-plans**](https://github.com/MaxInGaussian/pi-plans) | 239 | TypeScript | 2026-10-11 | Human-in-the-loop planning extension for the Pi coding agent. Turns rough change requests into versioned Mark… |
| 10 | [**edwinkys/phantasm**](https://github.com/edwinkys/phantasm) | 197 | Svelte | 2024-11-28 | Toolkits to create a human-in-the-loop approval layer to monitor and guide AI agents workflow in real-time. |

<details>
<summary>展开其余 5 项</summary>

| # | 项目 | ⭐ Stars | 语言 | 更新 | 简介 |
|:-:|:--|--:|:-:|:-:|:--|
| 11 | [**decionis/docker**](https://github.com/decionis/docker) | 165 | Go | 2026-08-25 | Govern consequential AI agent actions in Docker with deterministic policy, human approval, and signed Decisio… |
| 12 | [**spring-ai-community/spring-ai-playground**](https://github.com/spring-ai-community/spring-ai-playground) | 145 | Java | 2026-09-22 | Safe local execution layer for AI agent tools. Build and test-run MCP tools (no pass, no run), serve them fro… |
| 13 | [**BrightbeamAI/chap**](https://github.com/BrightbeamAI/chap) | 120 | HTML | 2026-10-20 | CHAP, the Collaborative Human Agent Protocol, is a MCP/A2A-compatible runtime for auditable human-agent work:… |
| 14 | [**preloop/preloop**](https://github.com/preloop/preloop) | 79 | Python | 2026-10-21 | The open-source AI agent control plane: MCP firewall, model gateway with budgets, human approvals, runtime ob… |
| 15 | [**als-apg/osprey**](https://github.com/als-apg/osprey) | 75 | Python | 2026-10-21 | An agentic interface and safety harness for safety-critical control systems |

</details>

<a id="about"></a>

## 📖 关于本列表

本列表从 GitHub 自动采集，经过去重、链接检查，按 Stars 排名（Stars 相同时按最近更新排序），并定时自动刷新，数据始终保持最新。

---

<div align="center">

<sub>自动生成 · 定时刷新 · 按 GitHub Stars 排名 · 2026-10-21</sub>

</div>
