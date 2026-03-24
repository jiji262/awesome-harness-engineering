# Awesome Harness Engineering

本仓库是 **Harness Engineering** 与 **AI Native Engineering** 的中英文双语资料整理，聚焦可落地的工程实践与开源工具。
资料来源于公开 web 与 GitHub 检索，工具均来自 GitHub 开源仓库，星标以当前抓取时刻为准。

## 1）文章（英文优先）

### Harness Engineering

- [AI/ML in the Harness Platform（Solution Brief）](https://go.harness.io/rs/924-CQO-224/images/AI-ML-in-the-Harness-Platform-Solution-Brief.pdf)  
  说明 Harness 如何把 CI/CD、自动化和机器学习能力融合到交付平台中。
- [Building your Platform Engineering Team](https://go.harness.io/rs/924-CQO-224/images/Building-your-platform-engineering-team.pdf?version=0)  
  讨论平台工程团队组织、职责边界、治理约束与落地机制。
- [Next-Generation CI/CD for Dummies（Harness Special Edition）](https://go.harness.io/rs/924-CQO-224/images/Next-Generation-CI-CD-For-Dummies-Harness-Special-Edition-min.pdf?version=0)  
  以平台交付视角讲解 AI 与自动化并行演进下的 CI/CD 转型方向。
- [CI/CD Buyers Guide](https://cms.harness.io/uploads/042021_e_Book_CICD_Buyers_Guide_1_bfbb94547d.pdf)  
  面向团队评估的交付平台与治理能力对比框架。
- [Harness engineering: Leveraging Codex in an agent-first world](https://openai.com/index/harness-engineering/)  
  OpenAI 对 agent-first 工程的复盘，聚焦仓库语境、协同流程与 CI 机制变更。

### AI Native Engineering

- [Towards AI-Native Software Engineering (SE 3.0): A Vision and a Challenge Roadmap](https://arxiv.org/abs/2410.06107)  
  从助手工具向 AI 原生工程演进的路线图，强调流程重构与验证机制。
- [The AI-Native Software Development Lifecycle: A Theoretical and Practical New Methodology](https://arxiv.org/abs/2408.03416)  
  将 SDLC 按 AI 参与度重构为规划、实现、测试、发布的闭环模型。
- [Towards the Next Generation of Software: AI-Native Applications Survey](https://arxiv.org/abs/2509.13144)  
  从应用实践中提炼 AI Native 的架构、质量与治理模式。
- [Building the AI-Native Platform: What Engineers Need to Scale Successfully](https://platformengineering.com/features/building-the-ai-native-platform-what-engineers-need-to-scale-successfully/)  
  平台视角下如何把 AI 能力下沉为开发基础设施能力，而非叠加式工具。
- [I Saw the Future of Platform Engineering — and It’s Called AI Native Dev](https://platformengineering.com/features/i-saw-the-future-of-platform-engineering-and-its-called-ai-native-dev/)  
  平台团队如何从工具拼接走向 AI-native 流程治理。
- [Compiler.next: A Search-Based Compiler to Power the AI-Native Future of Software Engineering](https://arxiv.org/abs/2510.24799)  
  探索“可搜索、可组合”的编译式自动化在工程规模化中的作用。

## 2）中文文章（精选）

- [人工智能PM系列文章（三）AI工程化的系统思维框架](https://www.woshipm.com/pmd/889402.html)  
  从需求、算法、治理视角梳理 AI 工程化与组织协同。
- [AI Native 软件工具与工程实践（中文）](https://aicoding.csdn.net/693fc9410800f3458b8280a2.html)  
  比对 AI Native 研发方式与传统开发流程，适合中文团队做方法对齐。

## 3）开源工具（GitHub）

### Harness / 平台工程

- [harness/harness](https://github.com/harness/harness)（**33,986 星**）  
  全栈交付平台，覆盖 CI/CD、制品、特性开关与平台治理。
- [argoproj/argo-cd](https://github.com/argoproj/argo-cd)（**22,420 星**）  
  Kubernetes 场景的 GitOps CD 栈，适合统一发布与策略。
- [bytebase/bytebase](https://github.com/bytebase/bytebase)（**13,847 星**）  
  数据库变更治理与审批流程，适合平台化 DBA 与变更控制。
- [opentofu/opentofu](https://github.com/opentofu/opentofu)（**28,203 星**）  
  可复用的 IaC 基础设施编排能力，适合平台化环境管理。
- [backstage/backstage](https://github.com/backstage/backstage)（**32,887 星**）  
  内部开发平台基座，适合搭建目录、模板和自助式工具入口。
- [hashicorp/terraform](https://github.com/hashicorp/terraform)（**48,023 星**）  
  行业主流 IaC 引擎，支持跨环境声明式交付。
- [hashicorp/nomad](https://github.com/hashicorp/nomad)（**16,327 星**）  
  工作负载编排引擎，适合服务、批处理与多租户运行时分层。
- [KusionStack/kusion](https://github.com/KusionStack/kusion)（**1,284 星**）  
  面向平台意图（intent）的交付编排框架，支持策略化治理。
- [cnoe-io/ai-platform-engineering](https://github.com/cnoe-io/ai-platform-engineering)（**328 星**）  
  AI 平台工程参考实现，聚焦工具链治理与工程治理闭环。

### AI Native 工具

- [openai/openai-agents-python](https://github.com/openai/openai-agents-python)（**20,239 星**）  
  轻量级多智能体编排框架，适合构建结构化 agent 工作流。
- [langchain-ai/langchain](https://github.com/langchain-ai/langchain)（**130,777 星**）  
  LLM 应用开发的基础框架，适合工具调用与链路编排。
- [langchain-ai/langgraph](https://github.com/langchain-ai/langgraph)（**27,272 星**）  
  状态图编排引擎，适合复杂长期任务与流程恢复场景。
- [microsoft/autogen](https://github.com/microsoft/autogen)（**56,090 星**）  
  支持 planning、工具调用与多智能体协作的编排框架。
- [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI)（**46,994 星**）  
  角色化智能体框架，适合分工明晰的复杂任务流水线。
- [run-llama/llama_index](https://github.com/run-llama/llama_index)（**47,914 星**）  
  检索增强和上下文工程的主流实现基础。
- [ComposioHQ/composio](https://github.com/ComposioHQ/composio)（**27,484 星**）  
  为智能体提供统一工具接入、权限与运行时调用控制。
- [BerriAI/litellm](https://github.com/BerriAI/litellm)（**40,088 星**）  
  多模型网关与成本治理层，适合统一 LLM 调用治理。
- [tensorzero/tensorzero](https://github.com/tensorzero/tensorzero)（**11,125 星**）  
  LLMOps 平台，覆盖路由、评估和迭代优化。
- [mlflow/mlflow](https://github.com/mlflow/mlflow)（**24,928 星**）  
  实验跟踪、模型管理与生产观测平台。
- [qdrant/qdrant](https://github.com/qdrant/qdrant)（**29,801 星**）  
  向量检索数据库，适合 RAG 与智能检索链路。
- [chroma-core/chroma](https://github.com/chroma-core/chroma)（**26,791 星**）  
  面向应用场景的轻量向量数据库，适合快速构建语义检索。
- [langfuse/langfuse](https://github.com/langfuse/langfuse)（**23,619 星**）  
  LLM trace、提示词和评测平台，支持质量、成本和异常监控。

## 贡献规范

- 文章以英文为主，中文条目只保留高质量且紧密相关内容。
- 工具条目需保留：GitHub 链接、星标数、可落地场景说明。
- 新增内容前先确认“平台工程 / AI Native”相关性，不要堆砌泛 AI 工具。
