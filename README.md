# Awesome Harness Engineering

This repository is a curated resource list for **Harness Engineering** and **AI Native Engineering**.
Entries are filtered for direct relevance. GitHub projects include star counts at collection time.

<b> Special Thanks to </b> [linux.do](https://linux.do)

Last researched: 2026-05-30 (Asia/Shanghai).

## 1) Articles

### Harness Engineering Foundations

- [Harness Engineering](https://openai.com/index/harness-engineering/)
  OpenAI's framing of harness engineering as the scaffolding layer around agents: context, tools, memory, verification, and execution boundaries.

- [Unrolling the Codex Agent Loop](https://openai.com/index/unrolling-the-codex-agent-loop/)
  Breaks the coding-agent loop into observe, plan, act, and verify stages, making harness responsibilities explicit.

- [Building Effective Agents](https://www.anthropic.com/research/building-effective-agents)
  Anthropic's practical guide to choosing workflows, agents, and multi-step compositions for production systems.

- [Harness Design for Long-Running Application Development](https://www.anthropic.com/engineering/harness-design-long-running-apps)
  Focuses on how to preserve progress, state, and reliability across long-running or multi-session agent tasks.

- [Writing Effective Tools for Agents](https://www.anthropic.com/engineering/writing-effective-tools-for-agents)
  Treats tool schemas, error surfaces, and naming as first-class agent UX and harness design.

- [Harness Engineering](https://martinfowler.com/articles/exploring-gen-ai/harness-engineering.html)
  Martin Fowler's synthesis of context engineering, architectural constraints, and entropy management as a single engineering discipline.

- [The Anatomy of an Agent Harness](https://blog.langchain.com/the-anatomy-of-an-agent-harness/)
  Organizes harness design into filesystem, code execution, sandboxing, memory, and context management primitives.

- [Externalization in LLM Agents: A Unified Review of Memory, Skills, Protocols and Harness Engineering](https://arxiv.org/abs/2604.08224)
  A fresh systems review of why agent capability is increasingly externalized into memory, skills, protocols, and harnesses rather than model weights alone.

- [AI Harness Engineering: A Runtime Substrate for Foundation-Model Software Agents](https://arxiv.org/abs/2605.13357)
  Formalizes harness as the runtime substrate between model and environment, with responsibilities spanning task specification, context selection, tools, memory, state, observability, failure attribution, verification, permissions, entropy auditing, and intervention records.

- [Code as Agent Harness](https://arxiv.org/abs/2605.18747)
  Frames code as the executable substrate for agent reasoning, action, environment modeling, memory, verification, and multi-agent coordination.

### Harness / Platform Engineering in Practice

- [Harness AI Overview](https://developer.harness.io/docs/platform/harness-ai/overview/)
  Explains how Harness applies AI in CI/CD, release governance, and secure automation.

- [Harness Agents](https://developer.harness.io/docs/platform/harness-ai/harness-agents/)
  Describes autonomous pipeline workers, RBAC boundaries, and integration patterns.

- [AI Test Automation](https://developer.harness.io/docs/ai-test-automation/)
  Covers AI-assisted testing workflows and how they reduce maintenance overhead.

- [Harness Revamps IDP to Give Platform Engineers More Granular Controls](https://platformengineering.com/social-facebook/harness-revamps-idp-to-give-platform-engineers-more-granular-controls/)
  Describes ownership and governance updates in Harness Internal Developer Portal.

- [Harness engineering: Agent harnesses as critical infrastructure](https://www.techtarget.com/searchapparchitecture/tip/Harness-engineering-Agent-harnesses-as-critical-infrastructure)
  Enterprise-facing overview of harness components such as orchestration, memory, guardrails, feedback loops, runtime observability, and safe scale-out.

- [Building the AI-Native Platform: What Engineers Need to Scale Successfully](https://platformengineering.com/features/building-the-ai-native-platform-what-engineers-need-to-scale-successfully/)
  Explains how platform teams shift from tool stitching to AI-native operating models.

- [Platform Engineering Becomes the Control Plane for Enterprise AI](https://platformengineering.com/features/platform-engineering-becomes-the-control-plane-for-enterprise-ai/)
  Argues that platform teams should expose governed workflows, RBAC, validation, and agent-specific authorization instead of giving agents raw human privileges.

- [From Cloud-Native to AI-Native: Why Platform Engineering Is Becoming the Enterprise OS](https://platformengineering.com/features/from-cloud-native-to-ai-native-why-platform-engineering-is-becoming-the-enterprise-os/)
  Shows why platform control, cost governance, and reliability become more critical with AI workloads.

- [AI in Platform Engineering: Promise, Plateau and the Path Forward](https://platformengineering.com/features/ai-in-platform-engineering-promise-plateau-and-the-path-forward/)
  Discusses practical limits, risks, and control points for steady AI adoption in platform teams.

- [Roadblocks to an AI-Native Future: What’s Holding Platform Teams Back](https://platformengineering.com/features/roadblocks-to-an-ai-native-future-whats-holding-platform-teams-back/)
  Identifies constraints around policy design, cost, and quality in AI-native operations.

- [I’ve Just Been Made a Platform Engineer: Now What?](https://platformengineering.com/features/ive-just-been-made-a-platform-engineer-now-what/)
  Provides pragmatic onboarding guidance for platform engineers moving to AI-native modernization.

### Harness Design Primitives

- [Run Long-Horizon Tasks with Codex](https://developers.openai.com/blog/run-long-horizon-tasks-with-codex/)
  Shows how planning artifacts such as `Plan.md` and `Implement.md` become reusable harness state for long-running work.

- [The next evolution of the Agents SDK](https://openai.com/index/the-next-evolution-of-the-agents-sdk/)
  OpenAI's April 2026 update to the Agents SDK: model-native harness, native sandbox execution, configurable memory, filesystem tools, and built-in support for MCP, skills, and `AGENTS.md` patterns.

- [Scaling Managed Agents: Decoupling the brain from the hands](https://www.anthropic.com/engineering/managed-agents)
  Anthropic's architecture note on separating session, harness, and sandbox so long-horizon agents can recover from failures and run across changing infrastructure.

- [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629)
  The canonical reasoning-action-observation loop paper behind most modern agent harness designs.

- [Plan-and-Execute Agents](https://blog.langchain.com/plan-and-execute-agents/)
  Separates planner and executor layers so long-horizon tasks can be decomposed and resumed more reliably.

- [Effective Harnesses for Long-Running Agents](https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents)
  Details structured handoff patterns, persistent progress tracking, and session reuse for tasks that exceed one context window.

- [Effective Context Engineering for AI Agents](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents)
  Reframes prompt design as a broader context-shaping problem across system prompts, tools, history, and state.

- [Harness engineering and agent feedback: Exploring AI coding sensors](https://www.thoughtworks.com/en-us/insights/blog/generative-ai/harness-engineering-agent-feedback-exploring-ai-coding-sensors)
  Adds feedback sensors to feed-forward skills and guardrails, emphasizing deterministic signals such as tests, linters, and runtime checks.

- [Prompt Caching — Claude API Docs](https://docs.anthropic.com/en/docs/build-with-claude/prompt-caching)
  Documents one of the most practical harness-level optimizations for reducing agent cost and latency.

- [LangGraph — Low Level Concepts](https://langchain-ai.github.io/langgraph/concepts/low_level/)
  Models loop control explicitly with typed state, graph edges, checkpoints, and resumable execution.

- [Closing the Knowledge Gap with Agent Skills](https://developers.googleblog.com/closing-the-knowledge-gap-with-agent-skills/)
  Explains how reusable skills act as durable harness components for reducing context and capability gaps.

- [Model Context Protocol Introduction](https://modelcontextprotocol.io/introduction)
  Defines the interoperability layer for exposing external tools and services to agents in a consistent way.

- [How Middleware Lets You Customize Your Agent Harness](https://blog.langchain.com/how-middleware-lets-you-customize-your-agent-harness/)
  Shows how policy enforcement, retries, fallbacks, and dynamic tool injection can live in harness middleware instead of prompt text.

- [LangGraph — Human-in-the-Loop Concepts](https://langchain-ai.github.io/langgraph/concepts/human_in_the_loop/)
  Covers interrupts, breakpoints, approvals, and resumption patterns for human-gated agent workflows.

### AI Native Engineering

- [The AI-Native Software Development Lifecycle: A Theoretical and Practical New Methodology](https://arxiv.org/abs/2408.03416)
  Defines AI-native SDLC design where planning, coding, testing, and release are AI-participatory by default.

- [Towards the Next Generation of Software: Survey on AI-Native Applications](https://arxiv.org/abs/2509.13144)
  Summarizes architecture and quality constraints seen in large AI-native software systems.

- [AI-NativeBench: A White-Box Agentic Benchmark for AI-Native Systems](https://arxiv.org/abs/2601.09393)
  Evaluates agent behavior, control flow, and engineering governance beyond model-level metrics.

- [Vibe Coding: Toward a Semantic and Intent-Driven AI-Native Paradigm](https://arxiv.org/abs/2510.17842)
  Examines intent-first AI coding and its impact on maintainability and testing approaches.

- [Compiler.next: A Search-Based Compiler to Power the AI-Native Future of Software Engineering](https://arxiv.org/abs/2510.24799)
  Explores compiler-level composition for scale, traceability, and quality control in AI-assisted coding.

- [SemaClaw: A Step Towards General-Purpose Personal AI Agents through Harness Engineering](https://arxiv.org/abs/2604.11548)
  Presents a personal-agent framework with DAG orchestration, PermissionBridge safety, three-tier context management, and agentic wiki skills.

- [Meta-Engineering Harnesses for AI-Native Software Production: A Contract-Driven Adversarial Verification Architecture with Early Deployment Report](https://arxiv.org/abs/2605.25665)
  Introduces contract compilation, role-specialized agents, independent and adversarial verification, failure arbitration, and outer-loop calibration for ongoing software production.

- [I Saw the Future of Platform Engineering — and It’s Called AI Native Dev](https://platformengineering.com/features/i-saw-the-future-of-platform-engineering-and-its-called-ai-native-dev/)
  Explains how platform operations and handoff patterns change when teams adopt AI-native workflows.

## 2) Chinese & WeChat Articles

- [Gartner 2024 Strategic Technology Trends: Platform Engineering and AI](https://mp.weixin.qq.com/s/aOmVfNoN4nCLbB0ebSRFwA)
  Official-style Chinese article discussing enterprise AI transformation, governance, and organization.

- [KubeCon/CloudNativeCon 2023 Platform Engineering Sessions (WeChat Collection)](https://mp.weixin.qq.com/s/HRo7AY8uzlu4KwFkNkRSAQ)
  Collection of platform and AI engineering talks, including implementation insights.

- [AI Agent and LLM Development Perspective](https://mp.weixin.qq.com/s/RBIlsqdkN7CNDuGWxhoxGQ)
  Shares front-end and back-end engineering considerations in AI-native development.

- [AI Native Software Engineering](https://mp.weixin.qq.com/s/UM3nBcX6JpYtnchSCdrxOA)
  Practical notes on requirement flow, implementation, testing, and collaboration rhythm for AI-native teams.

- [AI Native Is Becoming Mainstream: Performance and Cost Tradeoffs](https://developer.aliyun.com/article/1700752)
  Discusses platform stability, delivery consistency, and governance in AI-native delivery.

- [AI Native Software Engineering (ZhiHu)](https://zhuanlan.zhihu.com/p/1997606218785654100)
  Article-level discussion of team workflow and process design for AI-native teams.

## 3) Reference Implementations & Open Source Tools

### Tutorials & Educational

- [anthropics/claude-cookbooks](https://github.com/anthropics/claude-cookbooks) — **37,517 stars**
  Anthropic's official notebooks covering orchestrator-worker, tool use, context compaction, and Agent SDK patterns.

- [huggingface/smolagents](https://github.com/huggingface/smolagents) — **26,463 stars**
  A deliberately small codebase for understanding the full harness surface, including tools, memory, and sandbox integration.

- [shareAI-lab/learn-claude-code](https://github.com/shareAI-lab/learn-claude-code) — **48,944 stars**
  Step-by-step deconstruction of Claude Code's harness, useful for learning loop design, skills, and context management.

### Coding & Agent Harnesses

- [OpenHands/OpenHands](https://github.com/OpenHands/OpenHands) — **70,670 stars**
  A production-grade coding agent architecture with runtime isolation, event streaming, and controller layers worth studying.

- [sandbaseai/sandbase-harness](https://github.com/sandbaseai/sandbase-harness) — **638 stars**
  A local-first, self-hosted agent runtime with persistent sessions, MCP tool boundaries, permissions, audit/replay, and local or containerized deployment paths.

- [browser-use/browser-use](https://github.com/browser-use/browser-use) — **86,220 stars**
  A clean browser-agent harness showing how DOM state, actions, and retries fit into a minimal loop.

- [SWE-agent/SWE-agent](https://github.com/SWE-agent/SWE-agent) — **18,933 stars**
  Demonstrates task-specific agent-computer interfaces for file search, editing, and controlled software repair.

- [Aider-AI/aider](https://github.com/Aider-AI/aider) — **42,897 stars**
  A strong reference for multi-file editing, planner/coder separation, and git-aware coding workflows.

- [google/adk-python](https://github.com/google/adk-python) — **18,777 stars**
  Google's agent framework for multi-agent orchestration, tool registration, sessions, and evaluation pipelines.

- [pydantic/pydantic-ai](https://github.com/pydantic/pydantic-ai) — **16,124 stars**
  Type-safe agent framework that turns tool contracts and structured outputs into explicit schema-level boundaries.

- [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) — **83,065 stars**
  The main reference implementation set for MCP servers and external capability wiring.

- [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) — **30,349 stars**
  A browser automation MCP server that shows how GUI/web tooling can be exposed safely to agents.

### Harness / Platform Engineering

- [harness/harness](https://github.com/harness/harness) — **33,987 stars**
  Unified delivery platform with CI/CD, release governance, and policy-aware automation.

- [argoproj/argo-cd](https://github.com/argoproj/argo-cd) — **22,420 stars**
  GitOps control plane for standardized Kubernetes deployment governance.

- [backstage/backstage](https://github.com/backstage/backstage) — **32,887 stars**
  Internal Developer Platform core with catalogs, templates, and self-service workflows.

- [hashicorp/terraform](https://github.com/hashicorp/terraform) — **48,024 stars**
  Industry-standard Infrastructure as Code for environment standardization.

- [opentofu/opentofu](https://github.com/opentofu/opentofu) — **28,203 stars**
  Terraform-compatible IaC implementation with open governance orientation.

- [pulumi/pulumi](https://github.com/pulumi/pulumi) — **24,947 stars**
  Multi-language infrastructure platform with policy-friendly abstractions.

- [bytebase/bytebase](https://github.com/bytebase/bytebase) — **13,847 stars**
  Database change workflow with approvals and review-oriented safety controls.

- [crossplane/crossplane](https://github.com/crossplane/crossplane) — **11,525 stars**
  Controller-driven cloud resource abstraction layer for platform teams.

- [tektoncd/pipeline](https://github.com/tektoncd/pipeline) — **8,919 stars**
  Kubernetes-native CI/CD pipeline platform for repeatable build/deploy flows.

- [keptn/keptn](https://github.com/keptn/keptn) — **1,778 stars**
  Event-driven application lifecycle automation with policy hooks.

- [kubernetes-sigs/cluster-api](https://github.com/kubernetes-sigs/cluster-api) — **4,146 stars**
  Declarative cluster lifecycle APIs for platform-scale operations.

- [loft-sh/vcluster](https://github.com/loft-sh/vcluster) — **11,062 stars**
  Virtual cluster approach for tenant isolation and environment scaling.

- [open-feature/flagd](https://github.com/open-feature/flagd) — **887 stars**
  Feature flag service for progressive delivery and risk gating.

- [KusionStack/kusion](https://github.com/KusionStack/kusion) — **1,284 stars**
  Platform-oriented intent and resource orchestration for unified delivery.

- [KusionStack/karpor](https://github.com/KusionStack/karpor) — **1,685 stars**
  Kubernetes observability toolkit for complex platform estates.

- [seal-io/walrus](https://github.com/seal-io/walrus) — **440 stars**
  Self-service platform building blocks with templates and policy modules.

- [projectsveltos/addon-controller](https://github.com/projectsveltos/addon-controller) — **493 stars**
  Multi-cluster add-on orchestration and policy synchronization.

- [briefercloud/layerform](https://github.com/briefercloud/layerform) — **1,207 stars**
  Layered IaC platform pattern for environment and template governance.

- [open-policy-agent/conftest](https://github.com/open-policy-agent/conftest) — **3,146 stars**
  Reusable policy testing in CI/CD for platform-level compliance gates.

- [cnoe-io/ai-platform-engineering](https://github.com/cnoe-io/ai-platform-engineering) — **328 stars**
  AI platform engineering reference implementation with workflow guardrails.

- [kbst/terraform-kubestack](https://github.com/kbst/terraform-kubestack) — **707 stars**
  Modular Terraform toolkit for Kubernetes platform stack standardization.

### AI Native Engineering Tools

- [openai/openai-agents-python](https://github.com/openai/openai-agents-python) — **20,243 stars**
  Standardized orchestration framework for building reproducible AI agents.

- [langchain-ai/langchain](https://github.com/langchain-ai/langchain) — **130,796 stars**
  Core LLM orchestration framework with broad tooling and context integration.

- [langchain-ai/langgraph](https://github.com/langchain-ai/langgraph) — **27,282 stars**
  Graph-based orchestration for durable and stateful agent workflows.

- [microsoft/autogen](https://github.com/microsoft/autogen) — **56,096 stars**
  Multi-agent framework for planning, delegation, and shared context.

- [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) — **47,012 stars**
  Role-based agent orchestration suited for cross-functional workflow decomposition.

- [run-llama/llama_index](https://github.com/run-llama/llama_index) — **47,918 stars**
  Retrieval-augmented generation and context engineering foundation project.

- [ComposioHQ/composio](https://github.com/ComposioHQ/composio) — **27,483 stars**
  Secure model-to-tool integration layer with strong connector coverage.

- [BerriAI/litellm](https://github.com/BerriAI/litellm) — **40,092 stars**
  LLM gateway for provider normalization, routing, and cost governance.

- [tensorzero/tensorzero](https://github.com/tensorzero/tensorzero) — **11,125 stars**
  AI operations stack for inference routing, eval, and optimization feedback.

- [qdrant/qdrant](https://github.com/qdrant/qdrant) — **29,802 stars**
  High-performance vector database for semantic retrieval in AI-native applications.

- [chroma-core/chroma](https://github.com/chroma-core/chroma) — **26,792 stars**
  Lightweight vector store for RAG workloads and prototype iteration.

- [langfuse/langfuse](https://github.com/langfuse/langfuse) — **23,622 stars**
  LLM observability and tracing for prompts, spans, and quality metrics.

- [n8n-io/n8n](https://github.com/n8n-io/n8n) — **180,729 stars**
  AI-native workflow engine for visual automation and self-hosted deployment.

- [ToolJet/ToolJet](https://github.com/ToolJet/ToolJet) — **37,642 stars**
  Internal-tool platform for AI-native internal applications and data workflows.

- [alibaba/higress](https://github.com/alibaba/higress) — **7,891 stars**
  Cloud-native gateway with AI gateway and traffic management features.

- [open-gitagent/gitagent](https://github.com/open-gitagent/gitagent) — **1,056 stars**
  Standardization-focused experiment for interoperable AI agent definitions.

- [phodal/auto-dev](https://github.com/phodal/auto-dev) — **4,406 stars**
  AI-native development framework covering the full software lifecycle.

- [TaskingAI/TaskingAI](https://github.com/TaskingAI/TaskingAI) — **5,378 stars**
  Open-source platform for building AI-native applications and operations layers.

- [OpenBMB/IoA](https://github.com/OpenBMB/IoA) — **812 stars**
  A Chinese-oriented collection around AI-native architecture and AI-native workflow experiments.

- [Voltagent/voltagent](https://github.com/Voltagent/voltagent) — **6,935 stars**
  Reliable AI agent execution framework for iterative production workflows.

- [AGI-Eval-Official/CATArena](https://github.com/AGI-Eval-Official/CATArena) — **62 stars**
  Agentic benchmark dataset and evaluation tooling for engineering tasks.

- [ServiceNow/AgentLab](https://github.com/ServiceNow/AgentLab) — **541 stars**
  Evaluation-oriented platform for testing agent workflows in realistic enterprise tasks.

### Evaluation Frameworks & Agent Benchmarks

- [openai/evals](https://github.com/openai/evals) — **18,536 stars**
  OpenAI's framework and registry for evaluating LLMs and LLM systems, including private workflow-specific evals.

- [UKGovernmentBEIS/inspect_ai](https://github.com/UKGovernmentBEIS/inspect_ai) — **2,127 stars**
  UK AI Security Institute's eval framework with built-in support for tool use, multi-turn dialog, prompt engineering, and model-graded scoring.

- [EleutherAI/lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness) — **12,698 stars**
  Widely used model evaluation harness with many benchmark task implementations, useful as a baseline layer before agent-specific evals.

- [stanford-crfm/helm](https://github.com/stanford-crfm/helm) — **2,800 stars**
  Stanford CRFM's holistic evaluation framework for reproducible and transparent model and multimodal evaluation.

- [SWE-bench/SWE-bench](https://github.com/SWE-bench/SWE-bench) — **5,015 stars**
  Canonical repository-level issue-resolution benchmark and execution harness for coding agents.

- [microsoft/SWE-bench-Live](https://github.com/microsoft/SWE-bench-Live) — **192 stars**
  Continuously updated SWE-bench-style benchmark with monthly curation, MultiLang, and Windows task variants to reduce contamination and staleness.

- [harbor-framework/terminal-bench](https://github.com/harbor-framework/terminal-bench) — **2,264 stars**
  Terminal agent benchmark for hard shell tasks across software engineering, machine learning, security, data science, and related workflows.

- [EuniAI/TerminalWorld](https://github.com/EuniAI/TerminalWorld) — **12 stars**
  New May 2026 benchmark and data engine derived from real terminal recordings; useful for tracking authentic shell-workflow evaluation.

- [sierra-research/tau-bench](https://github.com/sierra-research/tau-bench) — **1,246 stars**
  Tool-Agent-User benchmark for multi-turn enterprise customer-service workflows with APIs and policy constraints.

- [sierra-research/tau2-bench](https://github.com/sierra-research/tau2-bench) — **1,237 stars**
  Current tau-bench family repo, now including knowledge, voice, task-quality fixes, and richer tool-user simulation modes.

- [ServiceNow/BrowserGym](https://github.com/ServiceNow/BrowserGym) — **1,229 stars**
  Gym-style environment for web agents, bundling MiniWoB, WebArena, VisualWebArena, WorkArena, AssistantBench, OpenApps, and TimeWarp.

- [xlang-ai/OSWorld](https://github.com/xlang-ai/OSWorld) — **2,875 stars**
  Multimodal computer-use benchmark in real OS environments, useful for desktop-agent harness and GUI automation evaluation.

- [claw-bench/claw-bench](https://github.com/claw-bench/claw-bench) — **171 stars**
  New agent benchmark with pytest-based verifiers and broad task domains; useful to watch as a fresh harness-oriented benchmark experiment.

### Sandboxing, Observability & Evaluation

- [e2b-dev/E2B](https://github.com/e2b-dev/E2B) — **11,594 stars**
  MicroVM sandboxes for agent tool loops, useful when code execution must be isolated from the host environment.

- [daytonaio/daytona](https://github.com/daytonaio/daytona) — **71,416 stars**
  Persistent workspace and sandbox infrastructure for longer-running or stateful agent tasks.

- [promptfoo/promptfoo](https://github.com/promptfoo/promptfoo) — **19,587 stars**
  Practical LLM and agent regression testing with YAML configs, assertions, and CI integration.

- [confident-ai/deepeval](https://github.com/confident-ai/deepeval) — **14,534 stars**
  Open-source evaluation framework with built-in metrics for agent quality, RAG correctness, and tool behavior.

- [traceloop/openllmetry](https://github.com/traceloop/openllmetry) — **6,981 stars**
  OpenTelemetry-based instrumentation for tracing LLM calls, agent steps, and tool execution.

- [Arize-ai/phoenix](https://github.com/Arize-ai/phoenix) — **9,182 stars**
  Self-hostable tracing and evaluation UI for inspecting and replaying agent workflows.

## 4) Security, Evals & Related Lists

### Security & Permissions

- [Beyond Permission Prompts](https://www.anthropic.com/engineering/beyond-permission-prompts)
  Argues for structured authorization systems instead of relying on free-form natural-language permission prompts.

- [Trustworthy agents in practice](https://www.anthropic.com/research/trustworthy-agents)
  Explains agent risk through the four-layer model of model, harness, tools, and environment, then maps trustworthy-agent principles to concrete product controls.

- [How we contain Claude across products](https://www.anthropic.com/engineering/how-we-contain-claude)
  Anthropic's containment lessons across Claude.ai, Claude Code, and Claude Cowork, emphasizing environment boundaries, sandbox and VM patterns, egress controls, and tool-output inspection.

- [Designing AI agents to resist prompt injection](https://openai.com/index/designing-agents-to-resist-prompt-injection/)
  Reframes prompt injection as a social-engineering problem and argues for source-sink controls, confirmations, and sandboxed action boundaries instead of input filtering alone.

- [Model Context Protocol — Authorization](https://modelcontextprotocol.io/specification/2025-11-05/basic/authorization)
  The MCP authorization spec for OAuth-style external service access in agent environments.

- [Claude Code auto mode: a safer way to skip permissions](https://www.anthropic.com/engineering/claude-code-auto-mode)
  Details a dual-layer defense using prompt-injection probes and action classifiers to reduce approval fatigue without falling back to fully unsafe no-permission mode.

- [Prompt Injection — Simon Willison's Series](https://simonwillison.net/series/prompt-injection/)
  A practical, field-tested explanation of indirect prompt injection risk in tool-using agents.

- [OWASP LLM01:2025 — Prompt Injection](https://genai.owasp.org/llmrisk/llm01-prompt-injection/)
  A concise security taxonomy for defining prompt-injection threat models and review checklists.

- [tldrsec/prompt-injection-defenses](https://github.com/tldrsec/prompt-injection-defenses) — **670 stars**
  A defense catalog covering input filtering, output sanitization, isolation, and trust-boundary hardening.

### Evals & Verification

- [Workspace-Bench 1.0: Benchmarking AI Agents on Workspace Tasks with Large-Scale File Dependencies](https://arxiv.org/abs/2605.03596)
  May 2026 benchmark for workspace-level agents, stressing large file dependency graphs, cross-file retrieval, contextual reasoning, and adaptive decision-making.

- [TerminalWorld: Benchmarking Agents on Real-World Terminal Tasks](https://arxiv.org/abs/2605.22535)
  May 2026 benchmark generated from in-the-wild terminal recordings, complementing expert-curated terminal benchmarks with authentic shell workflows.

- [SWE-Skills-Bench: Do Agent Skills Actually Help in Real-World Software Engineering?](https://arxiv.org/abs/2603.15401)
  Evaluates whether injected agent skills materially improve real software engineering tasks, with paired runs and execution-based verification.

- [Demystifying Evals for AI Agents](https://www.anthropic.com/engineering/demystifying-evals-for-ai-agents)
  Explains how to design outcome, process, and trajectory evaluations that match real agent behavior.

- [Testing Agent Skills Systematically with Evals](https://developers.openai.com/blog/eval-skills)
  OpenAI's practical guide to regression testing for skills, trace checks, and layered deterministic validation.

- [Agent Evaluation Readiness Checklist](https://blog.langchain.com/agent-evaluation-readiness-checklist/)
  A useful checklist for deciding whether an agent system is ready for stable CI and release gating.

- [Evaluating Skills](https://blog.langchain.com/evaluating-skills/)
  Shows how curated skills materially change agent outcomes and how to benchmark those gains.

- [Quantifying Infrastructure Noise in Agentic Coding Evals](https://www.anthropic.com/engineering/infrastructure-noise)
  Demonstrates that infrastructure configuration alone can swing coding-agent benchmark results materially.

- [Towards a Science of AI Agent Reliability](https://arxiv.org/abs/2602.16666)
  Proposes reliability metrics that separate capability gains from true operational robustness.

- [VeRO: An Evaluation Harness for Agents to Optimize Agents](https://arxiv.org/abs/2602.22480)
  Introduces a dedicated evaluation harness for agent-optimizing-agent workflows with versioned snapshots, budget-controlled runs, and structured traces.

### Related Awesome Lists

- [Meirtz/Awesome-Context-Engineering](https://github.com/Meirtz/Awesome-Context-Engineering) — **3,030 stars**
  A broader survey focused on context engineering, RAG, prompt shaping, and context-window design.

- [hesreallyhim/awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) — **36,874 stars**
  A focused collection of Claude Code resources, workflows, tools, and ecosystem projects.

- [appcypher/awesome-mcp-servers](https://github.com/appcypher/awesome-mcp-servers) — **5,370 stars**
  A useful companion list for discovering MCP servers that expose external tools and services to agents.

- [e2b-dev/awesome-ai-agents](https://github.com/e2b-dev/awesome-ai-agents) — **27,086 stars**
  A wider landscape survey of agent projects and frameworks beyond harness-specific concerns.
