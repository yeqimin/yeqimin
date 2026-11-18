# 构建可靠、可演进的系统

我关注 Java 后端、分布式系统和云原生平台。平时做一致性、幂等和故障恢复方面的工程实践，也研究如何把 RAG、MCP 和多智能体工作流接入企业应用。

## 代表项目

### [ComputeHub · 算力调度平台](https://github.com/yeqimin/compute-hub-demo)

可独立运行的全栈项目，涵盖租户权限、资源与实例管理、预付费钱包、异步任务及集群监控。

- **可靠投递** · 使用 MySQL Outbox 和 gRPC 模拟引擎串联实例操作与回调。
- **资金与状态一致性** · 演示余额冻结、成功结算、失败解冻、重复回调防重和超时对账。
- **租户边界与验证** · 通过 JWT、角色权限和租户过滤控制访问，提供 Docker Compose 启动与核心流程验证。

`Java 21` · `Spring Boot` · `MySQL` · `Redis` · `gRPC` · `Vue 3`

[运行说明](https://github.com/yeqimin/compute-hub-demo#快速启动) · [架构与接口](https://github.com/yeqimin/compute-hub-demo/blob/main/docs/architecture.md)

## 源码研究

这些仓库均为上游项目的 Fork，用于源码阅读与技术选型。

**Java 与 AI Agent**

- [Spring AI Alibaba](https://github.com/yeqimin/spring-ai-alibaba) · Graph 工作流、多智能体编排与 MCP 集成
- [LangChain4j](https://github.com/yeqimin/langchain4j) · JVM 上的模型接入、RAG 与工具调用

**云原生与平台工程**

- [Nacos](https://github.com/yeqimin/nacos) · 服务发现、动态配置与微服务治理
- [CloudExplorer](https://github.com/yeqimin/CloudExplorer) · 多云资源管理、模块边界与平台扩展

**AI 应用**

- [Horizon](https://github.com/yeqimin/Horizon) · AI 新闻采集、筛选与双语简报

## 工程关注点

- **Java 后端** · Spring Boot、Spring Security、MyBatis 与 REST API
- **分布式可靠性** · 最终一致性、状态机、幂等控制、重试与对账
- **可观测性** · 关键状态、调用链、异常定位与自动化验证
