---
title: "项目"
permalink: /projects/
---

这里整理我做过或正在整理的项目。当前重点放在 AI Agent、RAG、后端系统、自动化工程与研究工程能力。

## AI Agent / 工作流自动化

### 智学星途教师端 AI Agent 与教学工作流平台

2026.06 - 2026.08

参与智学星途教师端 AI 教育产品研发，公司产品在 WAIC 2026 参展展示；项目面向教师备课、教案生成、课件生成、学情分析和外部 Agent 工具调用场景，建设可追踪、可验证、可复用的教学 Agent 工作流。

- 问题：教师端 AI 能力涉及教案、课件、资料、联网检索和教学数据，单次生成难以满足可追踪、可验证和持续编辑的产品需求
- 方法：围绕 AI 教案、新教材理解、目标驱动教案等场景，实现意图识别、任务路由、资料上传、过程状态展示与历史管理
- Agent：接入联网可信源、用户上传资料、平台资料、开放网页回退和事实核验策略，补充资料引用与证据链能力，提升输出可追溯性
- 工程化：优化 MAIC PPT 生成 Agent 链路，拆分需求解析、大纲确认、页面规划、图片生成、预览编辑等阶段，并完善 Prompt、结构化输出、重试机制、任务队列与 worker 调度
- 开放能力：参与教师 Agent MCP / Skill、API Key、Token 审核、附件工具和官网接入文档建设，将内部教学能力封装为可被外部 Agent 调用的 Tool / Skill
- 技术栈：Java、Spring Boot、Next.js、Agent Workflow、Tool Calling、MCP、Skill、Prompt Engineering、MySQL、Redis

### 基于大模型的智能健康对话 Agent 系统

2025.04 - 2025.07

基于 Spring AI 的自主规划智能体对话系统，集成 RAG 知识库、联网搜索和多种工具调用，为用户提供个性化饮食与健身计划。

- 问题：健康建议需要结合用户问题、知识库、实时信息和多步骤规划，单轮问答难以覆盖复杂场景
- 方法：基于 PGvector 构建 RAG 系统，通过查询重写和多维过滤优化检索；集成联网搜索、网页抓取、文件操作、邮件发送、地图和图片搜索等工具调用
- Agent：基于 ReAct 和 CoT 构建可自主规划、任务分解的分层 Agent 架构
- 工程化：使用 Dockerfile 容器化并部署于 Serverless 平台，实现按需扩缩容和高效运维
- 结果：有效应答率提高 37%
- 技术栈：Spring AI、PGvector、RAG、Tool Calling、MCP、Docker、Serverless

## 后端系统 / 智能系统

### 云端存储智能协同图库管理平台

2024.07 - 2024.11

基于 Spring Boot 的云图库系统，结合 DDD、分库分表、多级缓存、异步任务与实时协同能力，实现图片资源的高并发存储、检索、编辑与团队空间管理。

- 数据治理：基于 ShardingSphere 实现可扩展分库分表；使用 Elasticsearch 实现自动打标的多维全文检索
- 性能优化：构建 Redis + Caffeine 多级缓存，提升复杂条件与热门图片查询性能
- 异步处理：基于 RabbitMQ 实现 AI 扩图、批量编辑等高负载任务的异步削峰与解耦
- 资源管控：利用 Redisson 分布式限流控制 AI 接口调用频率和成本
- 实时协同：基于 WebSocket 与 Sa-Token RBAC 权限控制实现团队协同编辑空间，并引入 Disruptor 优化异步处理流水线
- 技术栈：Spring Boot、DDD、ShardingSphere、Elasticsearch、Redis、Caffeine、RabbitMQ、Redisson、WebSocket、Sa-Token

## 科研 / 信号解码

### 基于深度学习的脑电语音解码研究

2023.07 - 2026.03

围绕 SEEG 语音解码开展研究，解决数据稀缺、模型过拟合和重建语音模糊等问题。相关论文以第一作者身份被 IEEE Sensors Journal 接收。

- 模型设计：设计 ConvED-SR 模型，从高维脑电信号中提取紧凑潜在特征，缓解稀疏数据下的过拟合
- 重建方法：构建 Scale-Recursive Reconstructor，通过从粗到细的频谱融合方式提升语音重建清晰度，MCD 降低 2.38 dB
- 探索方向：探索结合 Hifi-Codec 和 Transformer 的跨模态语义解码范式
- 论文：[Enhancing SEEG-Based Speech Decoding via Convolutional Encoder-Decoder and Scale-Recursive Reconstructor](/publications/)
- 关键词：SEEG、语音解码、深度学习、Transformer、神经信号处理

## 个人基础设施

### 面向 Agent 时代的个人网站

把个人网站作为持续迭代的个人基础设施项目：用 GitHub Pages、Jekyll 和 Minimal Mistakes 维护内容结构，用 Git 管理更新和发布流程，并逐步把经历、论文、项目、简历和思考沉淀成可检索、可展示的公开系统。

- 问题：个人信息分散在 GitHub、Scholar、论文、简历和社交平台中，缺少统一入口
- 方法：用静态站点组织内容，用版本控制管理迭代，用清晰导航承载不同受众的访问路径
- 结果：形成一个可持续维护的个人主页，支持求职、展示和长期记录
- 技术栈：GitHub Pages、Jekyll、Minimal Mistakes、Markdown、YAML、Git
- 链接：[yuanyu1016.github.io](https://github.com/yuanyu1016/yuanyu1016.github.io)
