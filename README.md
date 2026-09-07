<div align="center">

# 构建可靠、可演进的系统

### Java 架构 · 分布式系统 · 云原生 · AI Agent 工程化

[![Java](https://img.shields.io/badge/Java-21-0B5CAD?style=flat-square&logo=openjdk&logoColor=white)](https://openjdk.org/)
[![Spring Boot](https://img.shields.io/badge/Spring_Boot-工程实践-2F855A?style=flat-square&logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)
[![Distributed Systems](https://img.shields.io/badge/分布式系统-架构设计-334155?style=flat-square)](https://github.com/yeqimin/compute-hub-demo)
[![AI Agent](https://img.shields.io/badge/AI_Agent-工程化-0F766E?style=flat-square)](https://github.com/yeqimin/spring-ai-alibaba)

</div>

## 关于我

关注 Java 后端、分布式系统和云原生平台的工程设计，重视一致性、幂等性、可观测性与可演进性。目前也在研究如何把 LLM、RAG、MCP 和多智能体工作流可靠地接入企业级 Java 应用。

## 核心能力

| 方向 | 工程关注点 |
|---|---|
| **Java 与 Spring 生态** | Java 21、Spring Boot、Spring Security、MyBatis、REST API |
| **分布式系统** | 最终一致性、Outbox、幂等控制、状态机、异步任务、故障恢复 |
| **平台与基础设施** | Docker、MySQL、Redis、gRPC、监控与自动化验证 |
| **AI Agent 工程化** | Agent 工作流、工具调用、RAG、MCP、多智能体协作 |

## 代表项目

### [ComputeHub 算力调度平台](https://github.com/yeqimin/compute-hub-demo)

一个可独立运行的全栈算力调度平台，覆盖租户与权限、产品与资源、实例全生命周期、预付费钱包、异步任务和集群监控。

- 通过 **MySQL Outbox + gRPC Mock Engine** 展示可靠异步投递与最终一致性。
- 使用 **Redis 与数据库唯一约束** 实现请求、命令、回调和账务多层幂等。
- 对超时任务提供重试、状态查询和人工对账路径，处理分布式系统中的不确定结果。
- 采用 **JWT、BCrypt、HMAC-SHA256 与租户边界过滤** 保护访问和数据边界。
- 提供后端、前端、容器构建以及核心业务流程的自动化验证。

`Java 21` · `Spring Boot` · `MySQL 8` · `Redis 7` · `gRPC` · `Vue 3` · `Docker Compose`

## 源码研究方向

以下仓库用于跟踪 Java 架构与 Agent 工程化的核心实现。它们均为上游项目的 Fork，重点是源码阅读、技术选型和后续实践。

| 项目 | 研究主题 |
|---|---|
| [Spring AI Alibaba](https://github.com/yeqimin/spring-ai-alibaba) | Java Agent、Graph 工作流、多智能体编排与 MCP 集成 |
| [LangChain4j](https://github.com/yeqimin/langchain4j) | JVM 上的 LLM、RAG、工具调用和 Agent 抽象 |
| [CloudExplorer](https://github.com/yeqimin/CloudExplorer) | Spring Boot、多云管理、模块化平台与企业级扩展 |
| [Nacos](https://github.com/yeqimin/nacos) | 服务发现、动态配置和云原生微服务治理 |
| [Horizon](https://github.com/yeqimin/Horizon) | AI 驱动的信息采集、筛选与简报生成 |

## 我的工程原则

- **可观测**：关键状态、调用链和异常行为应当可以被定位。
- **可扩展**：模块边界清晰，核心流程通过稳定接口协作。
- **可演进**：架构服务于当前问题，也为容量、团队和业务变化保留空间。

## 技术语言

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=yeqimin&layout=compact&hide_border=true&bg_color=00000000&title_color=0B5CAD&text_color=475569&locale=cn" alt="yeqimin 的 GitHub 常用语言统计" />
</div>
