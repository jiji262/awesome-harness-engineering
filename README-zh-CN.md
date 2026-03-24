# Awesome Harness Engineering

本仓库整理与 **Harness Engineering** 与 **AI Native Engineering** 高度相关的公开资源。

- 聚焦平台交付治理、内部开发者平台（IDP）、GitOps 与 AI Native 工程实践。
- 工具条目来自 GitHub 开源项目，并附带 `2026-03-24` 时点的 star 数。

## 1）文章

### Harness Engineering

- [Harness the Power of Platform Engineering](https://www.harness.io/blog/harness-the-power-of-platform-engineering)  
  说明平台工程如何通过标准化交付接口和工作流提升规模化交付能力。
- [Platform Engineering: Beyond the Trough of Disillusionment](https://www.harness.io/blog/platform-engineering-beyond-the-trough-of-disillusionment)  
  讲解平台项目从启动期到稳定期的常见失速点与修复策略。
- [What is Platform Engineering?](https://www.harness.io/harness-devops-academy/what-is-platform-engineering)  
  定义平台工程团队职责、服务边界和组织模式。
- [What is GitOps?](https://www.harness.io/harness-devops-academy/what-is-gitops)  
  说明 Git 作为事实源后，发布、审计和回滚链路如何变化。
- [Harness GitOps for Continuous Delivery](https://www.harness.io/learn/use-cases/gitops)  
  讲解策略、门禁与 GitOps 规则如何接入持续交付。
- [Harness Policy as Code](https://www.harness.io/blog/harness-policy-as-code)  
  分享在发布治理中落地 policy-as-code 的执行范式。
- [What is Policy as Code?](https://www.harness.io/harness-devops-academy/what-is-policy-as-code)  
  介绍策略编写、评审和持续执行闭环。
- [How to Build AI-Native Security Resilience](https://www.harness.io/blog/how-to-build-ai-native-security-resilience-and-finally-get-developers-and-security-on-the-same-team)  
  讨论 AI 参与交付链路后，安全治理模型如何重构。
- [Harness AI: AI for Every Stage of the SDLC](https://www.harness.io/blog/announcing-harness-ai)  
  说明 AI 在计划、编码、测试、运维各阶段的协同方式。
- [AI-Driven Delivery Needs a Rethink](https://www.harness.io/blog/ai-driven-delivery-needs-a-rethink)  
  强调 AI 落地的本质问题在于治理与指标，而非单点工具替换。
- [Internal Developer Portal | Harness](https://developer.harness.io/docs/internal-developer-portal)  
  官方文档：如何在 Harness 中建设和运营 IDP。
- [Harness Platform Documentation](https://developer.harness.io/docs/platform)  
  平台交付与 SDLC 治理的核心官方文档入口。
- [Harness Continuous Delivery](https://developer.harness.io/docs/continuous-delivery)  
  持续交付流程、审批与发布机制的官方实践指南。
- [Deliver More Software Faster Without Hiring More](https://go.harness.io/rs/924-CQO-224/images/Deliver-More-Software-Faster-Without-Hiring-More.pdf)  
  用数据视角说明在交付规模化场景下的治理和组织实践。
- [AI/ML in the Harness Platform](https://go.harness.io/rs/924-CQO-224/images/AI-ML-in-the-Harness-Platform-Solution-Brief.pdf)  
  解析 Harness 场景下机器学习落地机会与实践方向。
- [Next-Generation CI/CD Model](https://go.harness.io/rs/924-CQO-224/images/Next-Generation-CI-CD-For-Dummies-Harness-Special-Edition-min.pdf?version=0)  
  用控制环视角重述 CI/CD 与治理反馈机制。
- [Data Governance Best Practices for Software Delivery](https://go.harness.io/rs/924-CQO-224/images/Data-Governance-Best%20Practices-for-Software%20Delivery-min.pdf)  
  面向大规模交付的合规和一致性实践清单。

### AI Native Engineering

- [Towards AI-Native Software Engineering (SE 3.0)](https://arxiv.org/abs/2410.06107)  
  将 AI 助手式开发升级为 AI Native 组织方式的框架讨论。
- [The Rise of AI Teammates in Software Engineering (SE 3.0)](https://arxiv.org/abs/2507.15003)  
  分析人机协同团队中的角色划分与协作模型。
- [The AI-Native Software Development Lifecycle](https://arxiv.org/abs/2408.03416)  
  讨论当 AI 成为生产执行者后 SDLC 如何重构。
- [AI-Native Bench: Towards Standardized Evaluation of AI-Native Engineering Practices](https://arxiv.org/abs/2601.09393)  
  提出评估 AI Native 工程质量的指标化思路。
- [MASAI: Modular Architecture for Software-engineering AI Agents](https://arxiv.org/abs/2406.11638)  
  生产级 AI Agent 系统的模块化架构实践。
- [SyncMind: Measuring Agent Out-of-Sync Recovery in Collaborative Software Engineering](https://arxiv.org/abs/2502.06994)  
  人机协作偏差检测与恢复能力度量。
- [Agentsway -- Software Development Methodology for AI Agents-based Teams](https://arxiv.org/abs/2510.23664)  
  针对 AI Agent 团队的组织方法和角色边界。
- [Compiler.next: A Search-Based Compiler to Power the AI-Native Future of Software Engineering](https://arxiv.org/abs/2510.24799)  
  用搜索驱动生成提升工程结果可控性的方向。
- [Reconsidering Requirements Engineering for Human-AI Collaboration](https://arxiv.org/abs/2510.04380)  
  AI 参与设计与实现后，需求工程的约束和流程变更。
- [The AI-Native Applications Survey](https://arxiv.org/abs/2509.13144)  
  对 AI Native 系统架构与运维模式的综合调研。
- [Vibe Coding in Practice](https://arxiv.org/abs/2510.00328)  
  讨论 AI 代码生产放量后的治理与质量风险。
- [How to Build Reliable AI Workflows with Agentic Primitives and Context Engineering](https://github.blog/ai-and-ml/how-to-build-reliable-ai-workflows-with-agentic-primitives-and-context-engineering/)  
  记忆边界、上下文压缩与编排可靠性建议。
- [How Anthropic Writes Tools for Agents](https://www.anthropic.com/engineering/writing-tools-for-agents)  
  工具契约、参数约束和执行可追溯性的实践原则。
- [Model Context Protocol (MCP): Announced](https://www.anthropic.com/news/model-context-protocol)  
  MCP 成为模型与工具互通标准的动机和边界。
- [MCP Introduction](https://modelcontextprotocol.io/introduction)  
  MCP 协议的使用场景与应用框架简介。
- [Anthropic Tool Use Documentation](https://docs.anthropic.com/en/docs/build-with-claude/tool-use)  
  Claude 的工具调用与结构化输出实施说明。
- [Anthropic Agents Documentation](https://docs.anthropic.com/en/docs/agents)  
  Agent 流程、上下文和权限设计指引。
- [LangChain Docs](https://docs.langchain.com/)  
  面向生产系统的 LLM 与工具编排文档。
- [Semantic Kernel Docs](https://learn.microsoft.com/en-us/semantic-kernel/overview/)  
  规划-执行的 Agent 应用框架与企业接入实践。
- [Google ADK 文档](https://google.github.io/adk-docs/get-started/python/)  
  Google 的 Agent 开发框架与示例集合。

### 微信公众号文章

- [AI时代背景下的平台工程之路](https://mp.weixin.qq.com/s/dZPNpyLSfKrg455xsIPcyA)  
  讨论 AI 时代下将平台工程作为组织产品能力的治理逻辑。
- [AI时代下平台工程与交付效率的协同思考](https://mp.weixin.qq.com/s/FNszInjKdILm8lErIqkoUg)  
  兼顾交付速度与治理一致性的组织权衡。
- [AI Native in 2026: 团队与交付治理实践](https://mp.weixin.qq.com/s/H8e6scM-HQteS0MBQ8zgYw)  
  探讨 AI Native 场景下团队角色与治理节奏。
- [AI 原生开发者平台与 AI 治理关系思考](https://mp.weixin.qq.com/s/aOmVfNoN4nCLbB0ebSRFwA)  
  分析平台能力边界与合规责任分配。
- [平台工程专题回顾与议题内容（公众号）](https://mp.weixin.qq.com/s/HRo7AY8uzlu4KwFkNkRSAQ)  
  归纳平台工程在可靠性、自动化、可观测性的关键议题。
- [字节化数据库变更与 GitOps 实践](https://mp.weixin.qq.com/s/ZJFc-J77R9ETXgl5tq8eKA)  
  分享数据库交付中的 GitOps 落地路径。
- [AI Native 与平台工程的协同范式：从工具到治理](https://mp.weixin.qq.com/s/3iQ0V4k8QYJXhQfLQbS7hA)  
  讨论平台治理、服务所有权与 AI 工作流的整合。
- [平台工程在 AI 时代的落地路径（运营视角）](https://mp.weixin.qq.com/s/8D8i8qQvW0o8k5vYfVf8mQ)  
  从运营序列视角拆解平台能力建设步骤。

## 2）开源工具（GitHub）

### Harness / 平台工程

- [harness/harness](https://github.com/harness/harness)（**33,989 星**）  
  全栈交付平台，覆盖 CI/CD、策略治理与发布治理。
- [harness/terraform-provider-harness](https://github.com/harness/terraform-provider-harness)（**43 星**）  
  通过 Terraform 进行 Harness 资源的声明式管理。
- [harness/harness-go-sdk](https://github.com/harness/harness-go-sdk)（**15 星**）  
  Go 侧 SDK，用于自动化接入 Harness 能力。
- [harness/mcp-server](https://github.com/harness/mcp-server)（**30 星**）  
  将 Harness 能力通过 MCP 接入 AI 工作流。
- [harness/developer-hub](https://github.com/harness/developer-hub)（**70 星**）  
  官方文档、示例和平台实践资料集合。
- [harness/harness-cd-community](https://github.com/harness/harness-cd-community)（**207 星**）  
  Harness CD 的社区实现与参考实践。
- [harness-community/harness-gitops-workshop](https://github.com/harness-community/harness-gitops-workshop)（**9 星**）  
  GitOps 研讨与演练示例。
- [cnoe-io/idpbuilder](https://github.com/cnoe-io/idpbuilder)（**319 星**）  
  Docker 化内部开发者平台起步套件。
- [cnoe-io/ai-platform-engineering](https://github.com/cnoe-io/ai-platform-engineering)（**328 星**）  
  面向 AI 平台的参考架构。
- [platform-engineering-labs/formae](https://github.com/platform-engineering-labs/formae)（**707 星**）  
  声明式控制面构建与平台服务治理。
- [rigdev/rig](https://github.com/rigdev/rig)（**1,062 星**）  
  强调开发者自助服务的 IDP 工具。
- [argoproj/argo-cd](https://github.com/argoproj/argo-cd)（**22,420 星**）  
  Kubernetes 场景下持续同步与漂移纠正的 GitOps 控制器。
- [argoproj/argo-workflows](https://github.com/argoproj/argo-workflows)（**16,557 星**）  
  交付/质量流程编排工作流引擎。
- [argoproj/argo-rollouts](https://github.com/argoproj/argo-rollouts)（**3,409 星**）  
  支持渐进式发布的灰度能力库。
- [argoproj/argo-events](https://github.com/argoproj/argo-events)（**2,631 星**）  
  事件驱动 GitOps 自动化入口层。
- [fluxcd/flux2](https://github.com/fluxcd/flux2)（**7,972 星**）  
  GitOps 同步与策略执行引擎。
- [crossplane/crossplane](https://github.com/crossplane/crossplane)（**11,525 星**）  
  API 驱动的基础设施编排与抽象层。
- [open-policy-agent/opa](https://github.com/open-policy-agent/opa)（**11,365 星**）  
  通用策略执行引擎，覆盖发布与运行时治理。
- [open-feature/flagd](https://github.com/open-feature/flagd)（**887 星**）  
  特性开关运行时服务，支持能力灰度控制。
- [bytebase/bytebase](https://github.com/bytebase/bytebase)（**13,847 星**）  
  数据库变更评审、审批与回滚平台。
- [runatlantis/atlantis](https://github.com/runatlantis/atlantis)（**8,927 星**）  
  PR 驱动的 Terraform 执行与协同控制。
- [KusionStack/kusion](https://github.com/KusionStack/kusion)（**1,284 星**）  
  多云平台的意图驱动编排框架。
- [KusionStack/karpor](https://github.com/KusionStack/karpor)（**1,685 星**）  
  Kubernetes 资源拓扑与可观测能力。
- [kptdev/kpt](https://github.com/kptdev/kpt)（**1,863 星**）  
  Kubernetes 平台中的配置包管理与模板化实践。
- [kubernetes-sigs/kustomize](https://github.com/kubernetes-sigs/kustomize)（**11,981 星**）  
  Kubernetes 声明式配置管理与定制工具。
- [kubernetes-sigs/kubebuilder](https://github.com/kubernetes-sigs/kubebuilder)（**9,040 星**）  
  用于构建 Kubernetes Operator 的平台开发框架。
- [tektoncd/pipeline](https://github.com/tektoncd/pipeline)（**8,919 星**）  
  云原生 CI/CD 流水线与任务编排。
- [tektoncd/catalog](https://github.com/tektoncd/catalog)（**719 星**）  
  可复用的 Tekton task 与 pipeline 模板。
- [backstage/backstage](https://github.com/backstage/backstage)（**32,887 星**）  
  企业级内部开发者门户基础设施。

### AI Native 工具

- [openai/openai-agents-python](https://github.com/openai/openai-agents-python)（**20,244 星**）  
  轻量化多 Agent 编排 SDK。
- [google/adk-python](https://github.com/google/adk-python)（**18,554 星**）  
  支持工具调用、记忆与结构化流程的 Agent 开发套件。
- [microsoft/autogen](https://github.com/microsoft/autogen)（**56,096 星**）  
  成熟的多 Agent 协作和规划执行框架。
- [microsoft/semantic-kernel](https://github.com/microsoft/semantic-kernel)（**27,533 星**）  
  企业级语义应用与 Agent 编排基础设施。
- [microsoft/TaskWeaver](https://github.com/microsoft/TaskWeaver)（**6,132 星**）  
  侧重长链任务分解与执行的框架。
- [langchain-ai/langchain](https://github.com/langchain-ai/langchain)（**130,809 星**）  
  大规模 LLM 应用与工具链的主流生产框架。
- [langchain-ai/langgraph](https://github.com/langchain-ai/langgraph)（**27,285 星**）  
  用有状态图执行引擎实现复杂 agent 工作流。
- [stanfordnlp/dspy](https://github.com/stanfordnlp/dspy)（**33,090 星**）  
  通过 prompt 优化提升模型决策与稳定性。
- [ag2ai/ag2](https://github.com/ag2ai/ag2)（**4,304 星**）  
  侧重角色、记忆和协作能力的多 Agent 框架。
- [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI)（**47,014 星**）  
  角色驱动的任务协作 Agent 系统。
- [FoundationAgents/MetaGPT](https://github.com/FoundationAgents/MetaGPT)（**65,965 星**）  
  以软件工程工件为核心的多角色协作框架。
- [OpenHands/OpenHands](https://github.com/OpenHands/OpenHands)（**69,622 星**）  
  支持执行-复核闭环的开源自主编码代理。
- [SWE-agent/SWE-agent](https://github.com/SWE-agent/SWE-agent)（**18,824 星**）  
  面向 Issue/PR 的工程自动化代理。
- [aider-ai/aider](https://github.com/aider-ai/aider)（**42,300 星**）  
  Git 友好的 AI 编码助手，强调差异审查。
- [SWE-bench/SWE-bench](https://github.com/SWE-bench/SWE-bench)（**4,543 星**）  
  真实 SWE 任务的 AI 能力评测基准。
- [pydantic/pydantic-ai](https://github.com/pydantic/pydantic-ai)（**15,719 星**）  
  用类型系统强化工具参数契约与接口安全。
- [a2aproject/A2A](https://github.com/a2aproject/A2A)（**22,754 星**）  
  早期 Agent 互操作协议研究。
- [ComposioHQ/composio](https://github.com/ComposioHQ/composio)（**27,483 星**）  
  可控工具接入与权限治理层。
- [BerriAI/litellm](https://github.com/BerriAI/litellm)（**40,096 星**）  
  统一 LLM 网关，覆盖路由与成本控制。
- [mem0ai/mem0](https://github.com/mem0ai/mem0)（**50,843 星**）  
  面向长时上下文的持久化记忆服务。
- [tensorzero/tensorzero](https://github.com/tensorzero/tensorzero)（**11,125 星**）  
  LLM 评测、路由与结果度量平台。
- [langfuse/langfuse](https://github.com/langfuse/langfuse)（**23,624 星**）  
  LLM 调用追踪、提示与成本治理。
- [qdrant/qdrant](https://github.com/qdrant/qdrant)（**29,804 星**）  
  高性能向量数据库，支撑检索增强与上下文。
- [chroma-core/chroma](https://github.com/chroma-core/chroma)（**26,792 星**）  
  轻量化向量库，适用于 RAG 与 Agent 上下文。
- [agno-agi/agno](https://github.com/agno-agi/agno)（**38,888 星**）  
  偏向生产部署的多代理执行框架。
- [n8n-io/n8n](https://github.com/n8n-io/n8n)（**180,736 星**）  
  AI 与外部系统编排自动化的低代码平台。
- [FlowiseAI/Flowise](https://github.com/FlowiseAI/Flowise)（**51,021 星**）  
  可视化 LLM/Agent 工作流构建工具。
- [modelcontextprotocol/modelcontextprotocol](https://github.com/modelcontextprotocol/modelcontextprotocol)（**7,598 星**）  
  模型与工具互操作的协议标准。
- [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers)（**81,883 星**）  
  MCP 服务端与生态示例集合。
- [modelcontextprotocol/python-sdk](https://github.com/modelcontextprotocol/python-sdk)（**22,276 星**）  
  Python MCP 客户端/服务端开发工具。
- [modelcontextprotocol/typescript-sdk](https://github.com/modelcontextprotocol/typescript-sdk)（**11,937 星**）  
  TypeScript 生态的 MCP 实现与扩展。
- [mcp-use/mcp-use](https://github.com/mcp-use/mcp-use)（**9,480 星**）  
  MCP 与 LLM 工具调用接入辅助库。
- [lastmile-ai/mcp-agent](https://github.com/lastmile-ai/mcp-agent)（**8,123 星**）  
  MCP 原生的多 Agent 编排实践。
- [openlit/openlit](https://github.com/openlit/openlit)（**2,313 星**）  
  针对模型与工具调用的可观测性采集库。
- [openai/swarm](https://github.com/openai/swarm)（**21,211 星**）  
  OpenAI 的轻量级实验性多 Agent 框架。
- [browser-use/browser-use](https://github.com/browser-use/browser-use)（**83,756 星**）  
  面向 Agentic 流程的浏览器自动化工具。
- [microsoft/agent-framework](https://github.com/microsoft/agent-framework)（**8,157 星**）  
  Microsoft 的实验性 Agent 框架。
- [huggingface/trl](https://github.com/huggingface/trl)（**17,765 星**）  
  Agent/对齐与强化学习训练相关工具链。
- [milvus-io/milvus](https://github.com/milvus-io/milvus)（**43,473 星**）  
  面向 AI 应用的向量检索数据库。
- [ollama/ollama](https://github.com/ollama/ollama)（**165,986 星**）  
  本地模型运行时，常用于 AI-native 开发与评测。
