# Awesome Harness Engineering

本仓库聚焦 **Harness Engineering** 与 **AI Native Engineering** 的高相关英文与中文资料，并补充 GitHub 开源工具。
仅保留与平台工程、AI Native 工程实践直接相关的条目，工具均附带当时抓取的 GitHub star 数。

最近检索：2026-05-30（Asia/Shanghai）。

## 1）文章

### Harness Engineering 基础与方法论

- [Harness Engineering](https://openai.com/index/harness-engineering/)
  OpenAI 对 Harness Engineering 的定义性文章，说明上下文、工具、记忆、验证和执行边界为何是智能体成功的关键脚手架。

- [Unrolling the Codex Agent Loop](https://openai.com/index/unrolling-the-codex-agent-loop/)
  将编码智能体拆成 observe、plan、act、verify 四个阶段，适合理解 harness 在每一环的职责。

- [Building Effective Agents](https://www.anthropic.com/research/building-effective-agents)
  Anthropic 对 workflow、agent 与多步编排模式的系统化实践总结。

- [Harness Design for Long-Running Application Development](https://www.anthropic.com/engineering/harness-design-long-running-apps)
  讨论长任务、多 session 场景下如何保存进度、状态与可靠性。

- [Writing Effective Tools for Agents](https://www.anthropic.com/engineering/writing-effective-tools-for-agents)
  把工具命名、schema 设计和错误表面视为一等公民，强调“工具设计就是 agent UX”。

- [Harness Engineering](https://martinfowler.com/articles/exploring-gen-ai/harness-engineering.html)
  Martin Fowler 从上下文工程、架构约束和熵管理三个维度总结 harness 工程实践。

- [The Anatomy of an Agent Harness](https://blog.langchain.com/the-anatomy-of-an-agent-harness/)
  将 harness 结构化为文件系统、代码执行、沙箱、记忆和上下文管理五类原语。

- [Externalization in LLM Agents: A Unified Review of Memory, Skills, Protocols and Harness Engineering](https://arxiv.org/abs/2604.08224)
  一篇最新的系统综述，解释为什么 agent 能力越来越依赖记忆、skills、协议和 harness 这些外化组件，而不只是模型权重本身。

- [AI Harness Engineering: A Runtime Substrate for Foundation-Model Software Agents](https://arxiv.org/abs/2605.13357)
  将 harness 形式化为模型与环境之间的运行时基座，覆盖任务规格、上下文选择、工具、记忆、状态、可观测性、失败归因、验证、权限、熵审计和人工介入记录等职责。

- [Code as Agent Harness](https://arxiv.org/abs/2605.18747)
  将代码重新定义为 agent 推理、行动、环境建模、记忆、验证和多智能体协作的可执行基座。

### Harness / 平台工程实践

- [Harness AI 概览](https://developer.harness.io/docs/platform/harness-ai/overview/)
  介绍 Harness 在交付流水线、CI/CD 与治理中的 AI 落地能力。

- [Harness Agents](https://developer.harness.io/docs/platform/harness-ai/harness-agents/)
  讲解 Harness 内部的自治任务执行能力，含权限边界、模型接入与安全控制。

- [Harness AI 自动化测试](https://developer.harness.io/docs/ai-test-automation/)
  讨论生成式测试在质量保障、维护成本和交付效率上的工程化应用。

- [Harness 刷新 IDP，平台工程师可更精细控制平台](https://platformengineering.com/social-facebook/harness-revamps-idp-to-give-platform-engineers-more-granular-controls/)
  说明 Harness IDP 的平台权限、治理与自助式交付能力演进。

- [Harness engineering: Agent harnesses as critical infrastructure](https://www.techtarget.com/searchapparchitecture/tip/Harness-engineering-Agent-harnesses-as-critical-infrastructure)
  面向企业读者梳理 harness 的关键组件，包括编排、记忆、护栏、反馈回路、运行时可观测性和安全规模化。

- [构建 AI-Native 平台：平台工程师如何规模化交付](https://platformengineering.com/features/building-the-ai-native-platform-what-engineers-need-to-scale-successfully/)
  讲清楚平台团队在 AI-Native 时代从“工具拼接”转向“运营交付平台化”的关键变化。

- [Platform Engineering Becomes the Control Plane for Enterprise AI](https://platformengineering.com/features/platform-engineering-becomes-the-control-plane-for-enterprise-ai/)
  说明平台团队应提供受治理的工作流、RBAC、验证和 agent 专属授权模型，而不是让 agent 直接继承人的全部权限。

- [从云原生走向 AI-Native：平台工程为何成为企业 OS](https://platformengineering.com/features/from-cloud-native-to-ai-native-why-platform-engineering-is-becoming-the-enterprise-os/)
  关注 AI 时代平台工程在成本治理、能力边界和团队模式上的新要求。

- [Platform Engineering 中 AI 的机遇、瓶颈与路径](https://platformengineering.com/features/ai-in-platform-engineering-promise-plateau-and-the-path-forward/)
  讨论平台团队导入 AI 时的边界条件，避免“技术先行、治理滞后”的误区。

- [AI-Native 未来遇到的主要阻力是什么？](https://platformengineering.com/features/roadblocks-to-an-ai-native-future-whats-holding-platform-teams-back/)
  从治理、成本和交付质量角度解释平台团队推进 AI-Native 的现实限制。

- [刚成为平台工程师怎么办？](https://platformengineering.com/features/ive-just-been-made-a-platform-engineer-now-what/)
  提供平台工程师在 AI-Native 改造中的优先事项与落地起步清单。

### Harness 设计原语

- [Run Long-Horizon Tasks with Codex](https://developers.openai.com/blog/run-long-horizon-tasks-with-codex/)
  展示 `Plan.md`、`Implement.md` 这类计划工件如何成为长任务里的可复用 harness 状态。

- [The next evolution of the Agents SDK](https://openai.com/index/the-next-evolution-of-the-agents-sdk/)
  OpenAI 在 2026 年 4 月对 Agents SDK 的更新，强调 model-native harness、原生 sandbox、可配置记忆，以及对 MCP、skills 和 `AGENTS.md` 模式的内建支持。

- [Scaling Managed Agents: Decoupling the brain from the hands](https://www.anthropic.com/engineering/managed-agents)
  Anthropic 对托管式长任务智能体架构的总结，核心是把 session、harness 和 sandbox 解耦，提升恢复能力与基础设施适配性。

- [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629)
  几乎所有现代 agent harness 都会回到的经典推理-行动-观察循环论文。

- [Plan-and-Execute Agents](https://blog.langchain.com/plan-and-execute-agents/)
  将 planner 与 executor 拆开，适合长期任务分解与中途恢复。

- [Effective Harnesses for Long-Running Agents](https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents)
  详细讨论跨上下文窗口的进度保留、结构化交接和 session 复用方式。

- [Effective Context Engineering for AI Agents](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents)
  将“写 prompt”扩展为“设计系统提示、工具、历史和状态”的整体上下文工程问题。

- [Harness engineering and agent feedback: Exploring AI coding sensors](https://www.thoughtworks.com/en-us/insights/blog/generative-ai/harness-engineering-agent-feedback-exploring-ai-coding-sensors)
  将 feedback sensors 补进 skills 与 guardrails 之外的 harness 设计，强调测试、lint 和运行时检查这类确定性反馈信号。

- [Prompt Caching — Claude API Docs](https://docs.anthropic.com/en/docs/build-with-claude/prompt-caching)
  解释如何通过缓存系统提示、工具定义和长文档来降低 agent 成本与延迟。

- [LangGraph — Low Level Concepts](https://langchain-ai.github.io/langgraph/concepts/low_level/)
  用显式状态、图边、检查点和恢复机制来建模 agent loop。

- [Closing the Knowledge Gap with Agent Skills](https://developers.googleblog.com/closing-the-knowledge-gap-with-agent-skills/)
  说明 skill 如何作为可复用 harness 组件，缩小上下文与能力缺口。

- [Model Context Protocol Introduction](https://modelcontextprotocol.io/introduction)
  MCP 的入门说明，定义了外部工具和服务如何以一致方式暴露给智能体。

- [How Middleware Lets You Customize Your Agent Harness](https://blog.langchain.com/how-middleware-lets-you-customize-your-agent-harness/)
  说明权限、重试、fallback 和动态注入工具为何更适合放在 middleware，而不是放在提示词里。

- [LangGraph — Human-in-the-Loop Concepts](https://langchain-ai.github.io/langgraph/concepts/human_in_the_loop/)
  讲清楚中断、审批、断点与恢复这些 HITL 模式该怎么落在 agent loop 里。

### AI Native Engineering

- [AI-Native 软件开发生命周期：新的工程方法与理论框架](https://arxiv.org/abs/2408.03416)
  给出 AI 深度参与需求、实现、测试、发布的 SDLC 重设计框架。

- [AI-Native 软件的下一代形态研究：架构与调研综述](https://arxiv.org/abs/2509.13144)
  总结 AI-Native 系统在架构、质量和治理上的共同特征与常见问题。

- [AI-NativeBench：面向 AI-Native 系统的白盒代理基准](https://arxiv.org/abs/2601.09393)
  从工程流程和代理行为角度给出可复现的 AI-Native 评测方案。

- [Vibe Coding：语义与意图驱动的 AI-Native 编程范式](https://arxiv.org/abs/2510.17842)
  研究意图驱动编码方式对维护性、测试策略和工程协作的影响。

- [Compiler.next：面向 AI-Native 软件工程的检索式编译器](https://arxiv.org/abs/2510.24799)
  探索搜索式编译机制对 AI 辅助代码生成可扩展性和可追踪性的价值。

- [SemaClaw: A Step Towards General-Purpose Personal AI Agents through Harness Engineering](https://arxiv.org/abs/2604.11548)
  提出一个面向个人智能体的框架，结合 DAG 编排、PermissionBridge 安全系统、三层上下文管理和 agentic wiki skills。

- [Meta-Engineering Harnesses for AI-Native Software Production: A Contract-Driven Adversarial Verification Architecture with Early Deployment Report](https://arxiv.org/abs/2605.25665)
  提出面向持续软件生产的 meta-engineering harness，包含契约编译、角色化 agent、独立与对抗式验证、失败仲裁和外层校准机制。

- [平台工程的未来是 AI Native 开发](https://platformengineering.com/features/i-saw-the-future-of-platform-engineering-and-its-called-ai-native-dev/)
  强调平台团队如何重构流程边界以适配智能体和 AI 参与的交付链路。

## 2）中文与公众号

- [Gartner 2024 战略技术趋势中的平台工程与 AI（公众号）](https://mp.weixin.qq.com/s/aOmVfNoN4nCLbB0ebSRFwA)
  从企业 AI 转型的视角拆解平台工程的治理价值与组织影响。

- [KubeCon/CloudNativeCon 2023 平台工程专题视频合集（公众号）](https://mp.weixin.qq.com/s/HRo7AY8uzlu4KwFkNkRSAQ)
  汇总与平台工程、AI 能力建设相关的公开分享内容。

- [AI Agent 与 LLM 开发实践](https://mp.weixin.qq.com/s/RBIlsqdkN7CNDuGWxhoxGQ)
  探讨 AI Native 前后端协作开发中的工程实践要点。

- [AI Native 软件工程（公众号）](https://mp.weixin.qq.com/s/UM3nBcX6JpYtnchSCdrxOA)
  讨论 AI Native 落地时需求定义、实现和测试的协作节奏。

- [大模型堆到天花板，Agent 激烈竞争](https://developer.aliyun.com/article/1700752)
  从平台化运维与交付稳定性的角度分析 AI Native 场景中的现实挑战。

- [AI Native 软件工程（知乎）](https://zhuanlan.zhihu.com/p/1997606218785654100)
  提供开源协作背景下的 AI Native 团队实践与方法论思路。

## 3）参考实现与开源工具（GitHub）

### 教程与拆解

- [anthropics/claude-cookbooks](https://github.com/anthropics/claude-cookbooks) — **37,517 星**
  Anthropic 官方 notebook 集合，覆盖 orchestrator-worker、tool use、context compaction 与 Agent SDK 模式。

- [huggingface/smolagents](https://github.com/huggingface/smolagents) — **26,463 星**
  体量很小但结构完整，适合快速读懂工具、记忆和沙箱是怎样组合成一个 harness 的。

- [shareAI-lab/learn-claude-code](https://github.com/shareAI-lab/learn-claude-code) — **48,944 星**
  对 Claude Code harness 的逐步拆解，适合学习 loop、skills 与 context 管理的落地方式。

### 编码与智能体 Harness

- [OpenHands/OpenHands](https://github.com/OpenHands/OpenHands) — **70,670 星**
  生产级编码智能体架构，包含 runtime 隔离、事件流和控制器分层，值得研究。

- [browser-use/browser-use](https://github.com/browser-use/browser-use) — **86,220 星**
  一个结构清晰的浏览器 agent harness，展示 DOM 状态、动作与重试如何组合成最小闭环。

- [SWE-agent/SWE-agent](https://github.com/SWE-agent/SWE-agent) — **18,933 星**
  通过任务定制的 agent-computer interface 来完成搜索、编辑和受控修复。

- [Aider-AI/aider](https://github.com/Aider-AI/aider) — **42,897 星**
  多文件编辑、planner/coder 分层和 git-aware 工作流方面的优秀参考。

- [google/adk-python](https://github.com/google/adk-python) — **18,777 星**
  Google 的 agent 框架，覆盖多智能体编排、工具注册、session 与评测流水线。

- [pydantic/pydantic-ai](https://github.com/pydantic/pydantic-ai) — **16,124 星**
  用类型和 schema 把工具契约、结构化输出和上下文边界显式化。

- [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) — **83,065 星**
  MCP Server 的核心参考实现集合，适合研究外部能力怎样接入 agent。

- [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) — **30,349 星**
  典型的浏览器自动化 MCP Server，展示 GUI / Web 能力如何安全暴露给 agent。

- [looptroop-ai/LoopTroop](https://github.com/looptroop-ai/LoopTroop) — **20 星**
  本地优先的 GUI 编码智能体 harness，支持多模型委员会规划、Git 隔离工作区中的原子任务执行与 Ralph-Loop 失败自动恢复。

### Harness / 平台工程

- [harness/harness](https://github.com/harness/harness) — **33,987 星**
  CI/CD、发布治理与安全策略一体化平台，适合构建统一交付能力。

- [argoproj/argo-cd](https://github.com/argoproj/argo-cd) — **22,420 星**
  Kubernetes GitOps 控制平面，适用于平台化交付一致性治理。

- [backstage/backstage](https://github.com/backstage/backstage) — **32,887 星**
  内部开发者平台核心，支持服务目录、模板和自助化工作流。

- [hashicorp/terraform](https://github.com/hashicorp/terraform) — **48,024 星**
  行业主流 IaC 工具，用于环境基线与交付标准化。

- [opentofu/opentofu](https://github.com/opentofu/opentofu) — **28,203 星**
  Terraform 兼容的开源实现，适合平台化治理偏好透明的团队。

- [pulumi/pulumi](https://github.com/pulumi/pulumi) — **24,947 星**
  多语言基础设施平台，支持策略化、可编程的资源交付模型。

- [bytebase/bytebase](https://github.com/bytebase/bytebase) — **13,847 星**
  数据库变更审核与审批工作流，适合平台级数据库治理。

- [crossplane/crossplane](https://github.com/crossplane/crossplane) — **11,525 星**
  云原生资源控制器编排框架，支持平台能力的意图化管理。

- [tektoncd/pipeline](https://github.com/tektoncd/pipeline) — **8,919 星**
  Kubernetes 原生 CI/CD 流水线，用于统一构建与交付链路。

- [keptn/keptn](https://github.com/keptn/keptn) — **1,778 星**
  事件驱动应用生命周期自动化框架，适配指标驱动的交付闭环。

- [kubernetes-sigs/cluster-api](https://github.com/kubernetes-sigs/cluster-api) — **4,146 星**
  平台化集群生命周期管理体系，适合多集群治理。

- [loft-sh/vcluster](https://github.com/loft-sh/vcluster) — **11,062 星**
  虚拟集群解决方案，支持租户隔离与环境扩展。

- [open-feature/flagd](https://github.com/open-feature/flagd) — **887 星**
  特性开关治理服务，支持灰度发布与风险隔离。

- [KusionStack/kusion](https://github.com/KusionStack/kusion) — **1,284 星**
  平台意图与资源编排能力，适用于统一标准化交付。

- [KusionStack/karpor](https://github.com/KusionStack/karpor) — **1,685 星**
  Kubernetes 可观测与资产治理组件，适合平台团队资产洞察。

- [seal-io/walrus](https://github.com/seal-io/walrus) — **440 星**
  平台级自助模板与策略模块化实现。

- [projectsveltos/addon-controller](https://github.com/projectsveltos/addon-controller) — **493 星**
  多集群插件与策略下发控制器，适合平台能力的自动装配。

- [briefercloud/layerform](https://github.com/briefercloud/layerform) — **1,207 星**
  分层 IaC 方案，支持团队间可复用环境模板。

- [open-policy-agent/conftest](https://github.com/open-policy-agent/conftest) — **3,146 星**
  在 CI/CD 中复用策略测试的轻量方案，适配平台合规入口。

- [cnoe-io/ai-platform-engineering](https://github.com/cnoe-io/ai-platform-engineering) — **328 星**
  AI 平台工程参考实现，强调工作流控制与治理边界。

- [kbst/terraform-kubestack](https://github.com/kbst/terraform-kubestack) — **707 星**
  针对 Kubernetes 平台的一套可复用 IaC 组件和编排思路。

### AI Native 工具

- [openai/openai-agents-python](https://github.com/openai/openai-agents-python) — **20,243 星**
  可复用智能体编排框架，关注工程可测试性。

- [langchain-ai/langchain](https://github.com/langchain-ai/langchain) — **130,796 星**
  工具与上下文管理框架，适合构建 LLM 应用骨架。

- [langchain-ai/langgraph](https://github.com/langchain-ai/langgraph) — **27,282 星**
  支持持久化状态和可恢复流程的图式智能体框架。

- [microsoft/autogen](https://github.com/microsoft/autogen) — **56,096 星**
  多智能体协作框架，支持任务分解与记忆共享。

- [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) — **47,012 星**
  通过角色化协作组织复杂任务链。

- [run-llama/llama_index](https://github.com/run-llama/llama_index) — **47,918 星**
  面向 RAG 的检索增强与上下文工程基础设施。

- [ComposioHQ/composio](https://github.com/ComposioHQ/composio) — **27,483 星**
  模型与外部工具的接入与权限治理层。

- [BerriAI/litellm](https://github.com/BerriAI/litellm) — **40,092 星**
  统一 LLM 网关，兼顾路由、计费和成本控制。

- [tensorzero/tensorzero](https://github.com/tensorzero/tensorzero) — **11,125 星**
  AI 推理路由、评估和优化栈，适用于生产 LLMOps。

- [qdrant/qdrant](https://github.com/qdrant/qdrant) — **29,802 星**
  向量数据库，支持语义检索与智能体应用。

- [chroma-core/chroma](https://github.com/chroma-core/chroma) — **26,792 星**
  轻量级向量存储方案，适合快速构建 RAG 应用。

- [langfuse/langfuse](https://github.com/langfuse/langfuse) — **23,622 星**
  LLM 可观测平台，覆盖提示词跟踪和质量归因。

- [n8n-io/n8n](https://github.com/n8n-io/n8n) — **180,729 星**
  AI-native 自动化工作流引擎，支持自建部署与集成。

- [ToolJet/ToolJet](https://github.com/ToolJet/ToolJet) — **37,642 星**
  AI-native 内部工具开发框架，便于快速搭建流程化应用。

- [alibaba/higress](https://github.com/alibaba/higress) — **7,891 星**
  兼顾 AI 网关能力的云原生网关方案。

- [open-gitagent/gitagent](https://github.com/open-gitagent/gitagent) — **1,056 星**
  智能体定义和标准化接口的实验性开源项目。

- [phodal/auto-dev](https://github.com/phodal/auto-dev) — **4,406 星**
  覆盖软件生命周期多个阶段的 AI-native 开发方案。

- [TaskingAI/TaskingAI](https://github.com/TaskingAI/TaskingAI) — **5,378 星**
  AI-native 应用和编排平台的开源实现。

- [OpenBMB/IoA](https://github.com/OpenBMB/IoA) — **812 星**
  中国开源生态中的 AI-native 架构与模型协作实践集合。

- [Voltagent/voltagent](https://github.com/Voltagent/voltagent) — **6,935 星**
  重视生产场景下智能体执行稳定性的框架。

- [AGI-Eval-Official/CATArena](https://github.com/AGI-Eval-Official/CATArena) — **62 星**
  面向工程任务的 Agentic 评测数据与评测框架。

- [ServiceNow/AgentLab](https://github.com/ServiceNow/AgentLab) — **541 星**
  以企业级任务为入口评估智能体工作流可行性。

### 评测框架与 Agent Benchmarks

- [openai/evals](https://github.com/openai/evals) — **18,536 星**
  OpenAI 的 LLM 与 LLM 系统评测框架和 benchmark registry，也支持面向私有工作流的自定义 eval。

- [UKGovernmentBEIS/inspect_ai](https://github.com/UKGovernmentBEIS/inspect_ai) — **2,127 星**
  UK AI Security Institute 的评测框架，内建工具调用、多轮对话、prompt engineering 和 model-graded scoring 支持。

- [EleutherAI/lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness) — **12,698 星**
  广泛使用的模型评测 harness，覆盖大量 benchmark task，适合作为 agent-specific eval 之前的基线层。

- [stanford-crfm/helm](https://github.com/stanford-crfm/helm) — **2,800 星**
  Stanford CRFM 的 holistic evaluation 框架，重视可复现、透明的模型与多模态评测。

- [SWE-bench/SWE-bench](https://github.com/SWE-bench/SWE-bench) — **5,015 星**
  代码智能体领域最核心的仓库级 issue 修复 benchmark 与执行 harness。

- [microsoft/SWE-bench-Live](https://github.com/microsoft/SWE-bench-Live) — **192 星**
  持续更新的 SWE-bench-like benchmark，包含月度任务更新、MultiLang 与 Windows 任务，用于降低污染和过期问题。

- [harbor-framework/terminal-bench](https://github.com/harbor-framework/terminal-bench) — **2,264 星**
  面向终端智能体的困难任务 benchmark，覆盖软件工程、机器学习、安全、数据科学等 shell 工作流。

- [EuniAI/TerminalWorld](https://github.com/EuniAI/TerminalWorld) — **12 星**
  2026 年 5 月的新 benchmark 和数据引擎，来自真实终端录制，适合跟踪真实 shell 工作流评测方向。

- [sierra-research/tau-bench](https://github.com/sierra-research/tau-bench) — **1,246 星**
  面向多轮企业客服场景的 Tool-Agent-User benchmark，强调 API 调用和业务策略约束。

- [sierra-research/tau2-bench](https://github.com/sierra-research/tau2-bench) — **1,237 星**
  当前 tau-bench 家族主仓，已加入 knowledge、voice、任务质量修复和更丰富的 tool-user simulation 模式。

- [ServiceNow/BrowserGym](https://github.com/ServiceNow/BrowserGym) — **1,229 星**
  面向 Web agent 的 Gym-style 环境，内置 MiniWoB、WebArena、VisualWebArena、WorkArena、AssistantBench、OpenApps 和 TimeWarp。

- [xlang-ai/OSWorld](https://github.com/xlang-ai/OSWorld) — **2,875 星**
  在真实操作系统环境中评测多模态 computer-use agent，适合桌面智能体与 GUI 自动化 harness 设计。

- [claw-bench/claw-bench](https://github.com/claw-bench/claw-bench) — **171 星**
  新的 agent benchmark，使用 pytest verifier 和多领域任务，适合作为 harness-oriented benchmark 的新实验观察对象。

### 沙箱、可观测与评测

- [e2b-dev/E2B](https://github.com/e2b-dev/E2B) — **11,594 星**
  面向 agent 工具调用的 microVM 沙箱，适合隔离代码执行与宿主环境。

- [daytonaio/daytona](https://github.com/daytonaio/daytona) — **71,416 星**
  提供持久化 workspace 与沙箱基础设施，适合长任务或有状态 agent 运行。

- [promptfoo/promptfoo](https://github.com/promptfoo/promptfoo) — **19,587 星**
  用 YAML 和断言配置做 LLM / agent 回归测试，接入 CI 很方便。

- [confident-ai/deepeval](https://github.com/confident-ai/deepeval) — **14,534 星**
  提供 RAG 正确性、agent 质量与 tool 行为等多类评测指标。

- [traceloop/openllmetry](https://github.com/traceloop/openllmetry) — **6,981 星**
  基于 OpenTelemetry 的 LLM / agent 调用链追踪方案。

- [Arize-ai/phoenix](https://github.com/Arize-ai/phoenix) — **9,182 星**
  可自托管的 tracing 与 eval 界面，方便回放和排查 agent 工作流。

## 4）安全、评测与相关列表

### 安全与权限

- [Beyond Permission Prompts](https://www.anthropic.com/engineering/beyond-permission-prompts)
  说明为什么不能只靠自然语言权限提示，而应把授权做成结构化系统。

- [Trustworthy agents in practice](https://www.anthropic.com/research/trustworthy-agents)
  用 model、harness、tools、environment 四层模型解释 agent 风险，并把“可信智能体”原则落到具体产品控制点上。

- [How we contain Claude across products](https://www.anthropic.com/engineering/how-we-contain-claude)
  Anthropic 总结 Claude.ai、Claude Code 与 Claude Cowork 的 containment 经验，重点是环境边界、沙箱 / VM、出站流量控制和工具输出检查。

- [Designing AI agents to resist prompt injection](https://openai.com/index/designing-agents-to-resist-prompt-injection/)
  把 prompt injection 重新定义为社会工程问题，强调 source-sink 控制、确认机制和沙箱边界，而不是只做输入过滤。

- [Model Context Protocol — Authorization](https://modelcontextprotocol.io/specification/2025-11-05/basic/authorization)
  MCP 中关于 OAuth 式外部服务访问的授权规范。

- [Claude Code auto mode: a safer way to skip permissions](https://www.anthropic.com/engineering/claude-code-auto-mode)
  介绍 Claude Code auto mode 的双层防线：输入侧的 prompt-injection probe，加上动作侧的分类器审批，用更低打断成本替代完全跳过权限。

- [Prompt Injection — Simon Willison's Series](https://simonwillison.net/series/prompt-injection/)
  系统解释间接提示词注入为何会在工具型 agent 中形成真实攻击面。

- [OWASP LLM01:2025 — Prompt Injection](https://genai.owasp.org/llmrisk/llm01-prompt-injection/)
  适合做 prompt injection 威胁建模和安全审查基线的精简规范。

- [tldrsec/prompt-injection-defenses](https://github.com/tldrsec/prompt-injection-defenses) — **670 星**
  收录输入过滤、输出净化、隔离和信任边界加固等实战防护手段。

### 评测与验证

- [Workspace-Bench 1.0: Benchmarking AI Agents on Workspace Tasks with Large-Scale File Dependencies](https://arxiv.org/abs/2605.03596)
  2026 年 5 月发布的 workspace-level agent benchmark，重点考察大规模文件依赖图、跨文件检索、上下文推理和自适应决策。

- [TerminalWorld: Benchmarking Agents on Real-World Terminal Tasks](https://arxiv.org/abs/2605.22535)
  2026 年 5 月发布的终端 agent benchmark，任务来自真实终端录制，可补充专家手工设计类 Terminal-Bench 的覆盖面。

- [SWE-Skills-Bench: Do Agent Skills Actually Help in Real-World Software Engineering?](https://arxiv.org/abs/2603.15401)
  用 paired runs 与执行型验证评估注入 agent skills 是否真的能提升真实软件工程任务表现。

- [Demystifying Evals for AI Agents](https://www.anthropic.com/engineering/demystifying-evals-for-ai-agents)
  解释 outcome、process 与 trajectory 评测该怎样设计，才能贴近真实 agent 行为。

- [Testing Agent Skills Systematically with Evals](https://developers.openai.com/blog/eval-skills)
  OpenAI 关于 skill 回归测试、trace 检查和分层确定性验证的实战指南。

- [Agent Evaluation Readiness Checklist](https://blog.langchain.com/agent-evaluation-readiness-checklist/)
  一份实用检查表，帮助判断 agent 系统是否真的具备稳定进入 CI 与发布门禁的条件。

- [Evaluating Skills](https://blog.langchain.com/evaluating-skills/)
  说明 skill 的质量如何显著改变 agent 结果，以及应如何做对比评测。

- [Quantifying Infrastructure Noise in Agentic Coding Evals](https://www.anthropic.com/engineering/infrastructure-noise)
  证明基础设施配置本身就会显著影响编码 agent 基准结果。

- [Towards a Science of AI Agent Reliability](https://arxiv.org/abs/2602.16666)
  提出一组将模型能力与运行可靠性拆开衡量的 agent 可靠性指标。

- [VeRO: An Evaluation Harness for Agents to Optimize Agents](https://arxiv.org/abs/2602.22480)
  针对“agent 优化 agent”这一新型工作流提出专用评测 harness，包含版本化快照、预算控制运行和结构化 trace。

### 相关 Awesome 列表

- [Meirtz/Awesome-Context-Engineering](https://github.com/Meirtz/Awesome-Context-Engineering) — **3,030 星**
  更广义的 context engineering 清单，覆盖 RAG、prompt shaping 和上下文窗口设计。

- [hesreallyhim/awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) — **36,874 星**
  聚焦 Claude Code 生态、工作流、工具与资源。

- [appcypher/awesome-mcp-servers](https://github.com/appcypher/awesome-mcp-servers) — **5,370 星**
  适合作为 MCP Server 生态入口，补充外部能力接入视角。

- [e2b-dev/awesome-ai-agents](https://github.com/e2b-dev/awesome-ai-agents) — **27,086 星**
  比本仓库范围更宽的 agent 项目与框架综述，方便做全景式检索。
