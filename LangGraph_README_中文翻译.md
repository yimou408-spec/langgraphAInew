<div align="center">
  <a href="https://www.langchain.com/langgraph">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset=".github/images/logo-dark.svg">
      <source media="(prefers-color-scheme: light)" srcset=".github/images/logo-light.svg">
      <img alt="LangGraph Logo" src=".github/images/logo-dark.svg" width="50%">
    </picture>
  </a>
</div>

<div align="center">
  <h3>用于构建有状态智能体的底层编排框架。</h3>
</div>

<div align="center">
  <a href="https://opensource.org/licenses/MIT" target="_blank"><img src="https://img.shields.io/pypi/l/langgraph" alt="PyPI - License"></a>
  <a href="https://pypistats.org/packages/langgraph" target="_blank"><img src="https://img.shields.io/pepy/dt/langgraph" alt="PyPI - Downloads"></a>
  <a href="https://pypi.org/project/langgraph/" target="_blank"><img src="https://img.shields.io/pypi/v/langgraph.svg?label=%20" alt="Version"></a>
  <a href="https://x.com/langchain_oss" target="_blank"><img src="https://img.shields.io/twitter/url/https/twitter.com/langchain_oss.svg?style=social&label=Follow%20%40LangChain" alt="Twitter / X"></a>
</div>

<br>

受到 Klarna、Replit、Elastic 等塑造智能体未来的公司以及更多企业的信赖，LangGraph 是一个用于构建、管理和部署长时间运行、有状态智能体的底层编排框架。

```bash
pip install -U langgraph
```

> [!TIP]
> 如果你希望快速构建智能体，可以查看 **[Deep Agents](https://docs.langchain.com/oss/python/deepagents/overview)** ——这是一个构建在 LangGraph 之上的更高层级软件包，适用于能够进行规划、使用子智能体，并借助文件系统完成复杂任务的智能体。

如需功能等价的 JS/TS 库，请查看 [LangGraph.js](https://github.com/langchain-ai/langgraphjs) 以及 [JS 文档](https://docs.langchain.com/oss/javascript/langgraph/overview)。

## 为什么使用 LangGraph？

LangGraph 为任何长时间运行的有状态工作流或智能体提供底层支撑基础设施：

- **[持久化执行](https://docs.langchain.com/oss/python/langgraph/durable-execution)** ——构建能够从故障中恢复、长时间运行的智能体，并自动从中断位置准确继续执行。
- **[人在回路（Human-in-the-loop）](https://docs.langchain.com/oss/python/langgraph/interrupts)** ——在执行过程中的任意时点检查并修改智能体状态，顺畅地加入人工监督。
- **[全面的记忆能力](https://docs.langchain.com/oss/python/langgraph/memory)** ——构建真正具备状态的智能体，同时支持用于持续推理的短期工作记忆，以及跨会话的长期持久化记忆。
- **[使用 LangSmith 调试](https://www.langchain.com/langsmith)** ——借助可视化工具深入了解复杂智能体的行为：追踪执行路径、捕获状态转换，并提供详细的运行时指标。
- **[面向生产环境的部署](https://docs.langchain.com/langsmith/deployments)** ——借助专为有状态、长时间运行工作流的独特挑战而设计的可扩展基础设施，放心部署复杂的智能体系统。

> [!TIP]
> 如需开发、调试和部署 AI 智能体及 LLM 应用，请查看 [LangSmith](https://docs.langchain.com/langsmith/home)。

## LangGraph 生态

LangGraph 可以独立使用，也能与 LangChain 的任何产品无缝集成，为开发者提供一整套智能体构建工具。

为了提升 LLM 应用的开发体验，可以将 LangGraph 与以下产品搭配使用：

- [Deep Agents](https://docs.langchain.com/oss/python/deepagents/overview) ——构建能够进行规划、使用子智能体并借助文件系统完成复杂任务的智能体。
- [LangChain](https://docs.langchain.com/oss/python/langchain/overview) ——提供集成能力和可组合组件，以简化 LLM 应用的开发。
- [LangSmith](https://www.langchain.com/langsmith) ——适用于智能体评测和可观测性。你可以调试表现不佳的 LLM 应用运行过程，评估智能体轨迹，了解生产环境中的运行情况，并持续提升性能。
- [LangSmith Deployment](https://docs.langchain.com/langsmith/deployments) ——借助专为长时间运行、有状态工作流打造的部署平台，轻松部署和扩展智能体。你可以在团队之间发现、复用、配置和共享智能体，并通过 [LangSmith Studio](https://docs.langchain.com/langsmith/studio) 的可视化原型设计快速迭代。

---

## 文档

- [docs.langchain.com](https://docs.langchain.com/oss/python/langgraph/overview) ——包含概念总览和操作指南的完整文档。
- [reference.langchain.com/python/langgraph](https://reference.langchain.com/python/langgraph) ——LangGraph 软件包的 API 参考文档。
- [LangGraph 快速入门](https://docs.langchain.com/oss/python/langgraph/quickstart) ——开始使用 LangGraph 构建应用。
- [Chat LangChain](https://chat.langchain.com/) ——与 LangChain 文档对话并获得问题解答。

**讨论区**：访问 [LangChain Forum](https://forum.langchain.com)，与社区交流，提出技术问题。

## 其他资源

- **[指南](https://docs.langchain.com/oss/python/learn)** ——提供快速、可直接使用的代码片段，涵盖流式处理、添加记忆与持久化，以及分支、子图等设计模式。
- **[LangChain Academy](https://academy.langchain.com/courses/intro-to-langgraph)** ——参加免费的结构化课程，学习 LangGraph 基础。
- **[案例研究](https://www.langchain.com/built-with-langgraph)** ——了解行业领先企业如何使用 LangGraph 大规模交付 AI 应用。
- [贡献指南](https://docs.langchain.com/oss/python/contributing/overview) ——了解如何为 LangChain 项目贡献代码，并查找适合初次参与者的问题。
- [行为准则](https://github.com/langchain-ai/langchain/?tab=coc-ov-file) ——了解社区行为规范。

---

## 致谢

LangGraph 的设计受到 [Pregel](https://research.google/pubs/pub37252/) 和 [Apache Beam](https://beam.apache.org/) 的启发。其公开接口的设计参考了 [NetworkX](https://networkx.org/documentation/latest/)。LangGraph 由 LangChain Inc. 构建，该公司也是 LangChain 的创始团队；但 LangGraph 可以脱离 LangChain 独立使用。
