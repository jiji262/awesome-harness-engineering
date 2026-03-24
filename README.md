# Awesome Harness Engineering

This repo is a curated resource collection about **Harness Engineering** and **AI Native Engineering**.
Sources are collected via public web and GitHub search, then filtered for practical engineering relevance.
Star counts are snapshots from GitHub API at generation time.

## 1) Articles (English First)

### Harness Engineering

- [AI/ML in the Harness Platform (Solution Brief)](https://go.harness.io/rs/924-CQO-224/images/AI-ML-in-the-Harness-Platform-Solution-Brief.pdf)  
  Explains how Harness combines CI/CD, automation, and ML capabilities to scale software delivery.
- [Building your Platform Engineering Team](https://go.harness.io/rs/924-CQO-224/images/Building-your-platform-engineering-team.pdf?version=0)  
  Details platform team structure, operating boundaries, and governance patterns for internal delivery platforms.
- [Next-Generation CI/CD for Dummies (Harness Special Edition)](https://go.harness.io/rs/924-CQO-224/images/Next-Generation-CI-CD-For-Dummies-Harness-Special-Edition-min.pdf?version=0)  
  Covers modern CI/CD operating expectations when AI and delivery automation are first-class.
- [CI/CD Buyers Guide](https://cms.harness.io/uploads/042021_e_Book_CICD_Buyers_Guide_1_bfbb94547d.pdf)  
  Practical comparison framework for selecting and governing delivery platforms.
- [Harness engineering: Leveraging Codex in an agent-first world](https://openai.com/index/harness-engineering/)  
  Long-form retrospective on agent-first engineering and how team process changed with AI-native workflows.

### AI Native Engineering

- [Towards AI-Native Software Engineering (SE 3.0): A Vision and a Challenge Roadmap](https://arxiv.org/abs/2410.06107)  
  Proposes a roadmap from assistant-level coding tools to AI-native software engineering.
- [The AI-Native Software Development Lifecycle: A Theoretical and Practical New Methodology](https://arxiv.org/abs/2408.03416)  
  Reframes planning, coding, testing, and delivery around AI-embedded lifecycle controls.
- [Towards the Next Generation of Software: AI-Native Applications Survey](https://arxiv.org/abs/2509.13144)  
  Reviews architecture and quality concerns that repeatedly appear in AI-native systems.
- [Building the AI-Native Platform: What Engineers Need to Scale Successfully](https://platformengineering.com/features/building-the-ai-native-platform-what-engineers-need-to-scale-successfully/)  
  Discusses platform teams moving from tool assembly to AI-first platform operations.
- [I Saw the Future of Platform Engineering — and It’s Called AI Native Dev](https://platformengineering.com/features/i-saw-the-future-of-platform-engineering-and-its-called-ai-native-dev/)  
  Describes how platform teams evolve process, policy, and ownership around AI-native delivery.
- [Compiler.next: A Search-Based Compiler to Power the AI-Native Future of Software Engineering](https://arxiv.org/abs/2510.24799)  
  Explores compiler-level synthesis and automation patterns for large-scale engineering systems.

## 2) Chinese Articles (selected)

- [人工智能PM系列文章（三）AI工程化的系统思维框架](https://www.woshipm.com/pmd/889402.html)  
  从需求、算法、治理三个层面解释 AI 工程化落地思路，适合作为中文背景对齐材料。
- [AI Native 时代的软件工程实践（中文）](https://aicoding.csdn.net/693fc9410800f3458b8280a2.html)  
  从国产生态与工具实践角度讨论 AI Native 与研发工作流变化，适合对比不同组织的落地路径。

## 3) Open Source Tools (GitHub)

### Harness / Platform Engineering

- [harness/harness](https://github.com/harness/harness) — **33,986 stars**  
  End-to-end platform product for CI/CD, feature management, and delivery controls.
- [argoproj/argo-cd](https://github.com/argoproj/argo-cd) — **22,420 stars**  
  GitOps-native CD system for Kubernetes-centric platform standardization.
- [bytebase/bytebase](https://github.com/bytebase/bytebase) — **13,847 stars**  
  Database change and review workflows for safer platform-driven schema operations.
- [opentofu/opentofu](https://github.com/opentofu/opentofu) — **28,203 stars**  
  Terraform-compatible IaC engine for reproducible environment lifecycle management.
- [backstage/backstage](https://github.com/backstage/backstage) — **32,887 stars**  
  Internal Developer Platform base layer for catalogs, templates, and tooling.
- [hashicorp/terraform](https://github.com/hashicorp/terraform) — **48,023 stars**  
  Core infrastructure abstraction layer for platform engineering delivery.
- [hashicorp/nomad](https://github.com/hashicorp/nomad) — **16,327 stars**  
  Workload orchestrator for predictable service fleet and runtime control.
- [KusionStack/kusion](https://github.com/KusionStack/kusion) — **1,284 stars**  
  IDP-oriented declarative orchestrator for platform intent and policies.
- [cnoe-io/ai-platform-engineering](https://github.com/cnoe-io/ai-platform-engineering) — **328 stars**  
  AI platform engineering reference implementation focused on agent workflow guardrails.

### AI Native Engineering

- [openai/openai-agents-python](https://github.com/openai/openai-agents-python) — **20,239 stars**  
  Lightweight Python framework for orchestrating structured multi-agent workflows.
- [langchain-ai/langchain](https://github.com/langchain-ai/langchain) — **130,777 stars**  
  Foundational LLM app framework with extensive tool and memory integration.
- [langchain-ai/langgraph](https://github.com/langchain-ai/langgraph) — **27,272 stars**  
  Graph-based orchestrator for durable, stateful AI workflows.
- [microsoft/autogen](https://github.com/microsoft/autogen) — **56,090 stars**  
  Multi-agent framework for planning, tool use, and memory-sharing patterns.
- [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) — **46,994 stars**  
  Role-driven agent framework for decomposition into reusable specialist workflows.
- [run-llama/llama_index](https://github.com/run-llama/llama_index) — **47,914 stars**  
  High-impact framework for retrieval, indexing, and context engineering.
- [ComposioHQ/composio](https://github.com/ComposioHQ/composio) — **27,484 stars**  
  Tooling layer to connect agents with external services under consistent auth/security patterns.
- [BerriAI/litellm](https://github.com/BerriAI/litellm) — **40,088 stars**  
  Multi-provider LLM gateway with routing, cost controls, guardrails, and observability hooks.
- [tensorzero/tensorzero](https://github.com/tensorzero/tensorzero) — **11,125 stars**  
  Unified LLMOps stack for inference routing, evaluation, and optimization feedback.
- [mlflow/mlflow](https://github.com/mlflow/mlflow) — **24,928 stars**  
  ML/LLM lifecycle platform for experimentation, packaging, and model observability.
- [qdrant/qdrant](https://github.com/qdrant/qdrant) — **29,801 stars**  
  Vector database core to AI-native retrieval and recommendation workloads.
- [chroma-core/chroma](https://github.com/chroma-core/chroma) — **26,791 stars**  
  Lightweight vector storage used in many RAG and AI-native application stacks.
- [langfuse/langfuse](https://github.com/langfuse/langfuse) — **23,619 stars**  
  Tracing/eval platform for production prompts, spans, and quality monitoring.

## How to Contribute

- Keep article entries English-first; add Chinese entries only if they are high value and tightly relevant.
- For every tool entry, keep GitHub link + current star count + a concrete applicability note.
- Prefer adding new items only after checking direct relevance to Harness Engineering or AI Native Engineering.
