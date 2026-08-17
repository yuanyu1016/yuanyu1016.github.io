---
title: "项目"
permalink: /projects/
---

这里整理我做过或正在整理的项目。当前重点放在 AI Agent、RAG、后端系统、自动化工程与研究工程能力。

## AI Agent / Workflow Automation

### 基于大模型的智能健康对话 Agent 系统

2025.04 - 2025.07

基于 Spring AI 的自主规划智能体对话系统，集成 RAG 知识库、联网搜索和多种工具调用，为用户提供个性化饮食与健身计划。

- Problem：健康建议需要结合用户问题、知识库、实时信息和多步骤规划，单轮问答难以覆盖复杂场景
- Approach：基于 PGvector 构建 RAG 系统，通过查询重写和多维过滤优化检索；集成联网搜索、网页抓取、文件操作、邮件发送、地图和图片搜索等工具调用
- Agent：基于 ReAct 和 CoT 构建可自主规划、任务分解的分层 Agent 架构
- Engineering：使用 Dockerfile 容器化并部署于 Serverless 平台，实现按需扩缩容和高效运维
- Result：有效应答率提高 37%
- Stack：Spring AI, PGvector, RAG, Tool Calling, MCP, Docker, Serverless

## Backend / Intelligent Systems

### 云端存储智能协同图库管理平台

2024.07 - 2024.11

基于 Spring Boot 的云图库系统，结合 DDD、分库分表、多级缓存、异步任务与实时协同能力，实现图片资源的高并发存储、检索、编辑与团队空间管理。

- Data：基于 ShardingSphere 实现可扩展分库分表；使用 Elasticsearch 实现自动打标的多维全文检索
- Performance：构建 Redis + Caffeine 多级缓存，提升复杂条件与热门图片查询性能
- Async：基于 RabbitMQ 实现 AI 扩图、批量编辑等高负载任务的异步削峰与解耦
- Control：利用 Redisson 分布式限流控制 AI 接口调用频率和成本
- Collaboration：基于 WebSocket 与 Sa-Token RBAC 权限控制实现团队协同编辑空间，并引入 Disruptor 优化异步处理流水线
- Stack：Spring Boot, DDD, ShardingSphere, Elasticsearch, Redis, Caffeine, RabbitMQ, Redisson, WebSocket, Sa-Token

## Research / Signal Decoding

### 基于深度学习的脑电语音解码研究

2023.07 - 2026.03

围绕 SEEG 语音解码开展研究，解决数据稀缺、模型过拟合和重建语音模糊等问题。相关论文以第一作者身份被 IEEE Sensors Journal 接收。

- Model：设计 ConvED-SR 模型，从高维脑电信号中提取紧凑潜在特征，缓解稀疏数据下的过拟合
- Reconstruction：构建 Scale-Recursive Reconstructor，通过从粗到细的频谱融合方式提升语音重建清晰度，MCD 降低 2.38 dB
- Exploration：探索结合 Hifi-Codec 和 Transformer 的跨模态语义解码范式
- Paper：[Enhancing SEEG-Based Speech Decoding via Convolutional Encoder-Decoder and Scale-Recursive Reconstructor](/publications/)
- Keywords：SEEG, speech decoding, deep learning, Transformer, neural signal processing

## Personal Infrastructure

### Agent-Oriented Personal Website

把个人网站作为持续迭代的个人基础设施项目：用 GitHub Pages、Jekyll 和 Minimal Mistakes 维护内容结构，用 Git 管理更新和发布流程，并逐步把经历、论文、项目、简历和思考沉淀成可检索、可展示的公开系统。

- Problem：个人信息分散在 GitHub、Scholar、论文、简历和社交平台中，缺少统一入口
- Approach：用静态站点组织内容，用版本控制管理迭代，用清晰导航承载不同受众的访问路径
- Result：形成一个可持续维护的个人主页，支持求职、展示和长期记录
- Stack：GitHub Pages, Jekyll, Minimal Mistakes, Markdown, YAML, Git
- Link：[yuanyu1016.github.io](https://github.com/yuanyu1016/yuanyu1016.github.io)
