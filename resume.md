---
title: "简历"
permalink: /resume/
---

## Profile

Yuanyu He is an AI-native builder focused on AI Agents, workflow automation, backend systems, and intelligent products. He has experience in Spring AI / LangChain4j-based Agent applications, RAG systems, backend engineering, and deep-learning research.

## 技术技能

- 编程语言：Java、Python；掌握 C/C++
- AI 开发：Spring AI、LangChain4j、RAG、Agent、Tool Calling、PyTorch、Transformer
- Agent 与自动化工程：Agentic Workflow、任务拆解、工具调用、上下文/状态管理、执行反馈、循环验证、多 Agent 协作编排
- 后端开发：Spring Boot、Spring IoC/AOP、MyBatis、MySQL、Redis、RabbitMQ、Elasticsearch、Nginx、Spring Cloud
- 工程基础：Linux、Docker、Git、计算机网络、数据结构与算法
- 写作与研究：英文技术文献阅读、英文论文写作

## 项目与科研经历

### 基于大模型的智能健康对话 Agent 系统

2025.04 - 2025.07

一个基于 Spring AI 的自主规划智能体对话系统，集成 RAG 知识库、联网搜索和多种工具调用，为用户提供个性化饮食与健身计划。

- RAG 查询增强：基于 PGvector 设计并实现检索增强生成系统，通过查询重写和多维过滤优化用户提问，提升检索准确度与信息召回率，将有效应答率提高 37%
- AI 工具调用：开发并集成联网搜索、网页抓取、文件操作、邮件发送等 Tool Calling 工具，并接入地图和图片搜索等 MCP 服务，扩展 Agent 能力边界
- 自主规划智能体：基于 ReAct 和 CoT 模式构建可自主规划、任务分解的分层 Agent 架构；通过 Dockerfile 容器化并部署于 Serverless 平台，实现按需扩缩容和高效运维

### 云端存储智能协同图库管理平台

2024.07 - 2024.11

基于 Spring Boot 的云图库系统，通过 DDD 领域驱动设计，结合分库分表、多级缓存与异步任务优化，实现图片资源的高并发存储与检索，并支持多端实时协同编辑及多用户团队空间管理。

- 分布式数据治理：基于 ShardingSphere 实现可扩展的分库分表多用户空间素材管理；利用 Elasticsearch 实现自动打标的多维全文检索，并构建 Redis + Caffeine 多级缓存提升复杂条件与热门图片查询性能
- 高并发性能优化与资源管控：基于 RabbitMQ 构建任务处理流水线，实现 AI 扩图、批量编辑等高负载任务的异步削峰与解耦；利用 Redisson 分布式限流控制 AI 接口调用频率和成本
- 实时协同引擎：基于 WebSocket 与 Sa-Token 精细化 RBAC 权限控制，支持多端状态同步的团队协同编辑空间；引入 Disruptor 无锁队列优化异步处理流水线

### 基于深度学习的脑电语音解码研究

2023.07 - 2026.03

研究立体脑电 SEEG 语音解码中数据稀缺、模型过拟合和重建语音模糊等问题。相关论文以第一作者身份被 IEEE Sensors Journal 接收。

- ConvED-SR 模型：设计并实现基于卷积编码器-解码器的深度学习模型，从高维脑电信号中提取紧凑潜在特征，缓解稀疏数据下的过拟合问题
- 多尺度递归重建：构建 Scale-Recursive Reconstructor，通过从粗到细的方式渐进融合频谱信息，将重建语音的梅尔倒谱失真度 MCD 降低 2.38 dB
- 跨模态语义解码：探索结合 Hifi-Codec 和 Transformer 的脑电-语音特征对齐网络，提升低级特征解码中的语义表达能力

## 实习经历

### 智学星途

2026.06 - 2026.08

- 在上海参与实习工作，积累工程实践与系统构建经验

## 学生工作与教学

- 本科连续四年担任班委，具备组织协调和沟通能力
- 担任《微机原理和嵌入式系统》课程助教

## 教育背景

### 中国科学技术大学

2022.09 - 2027.03

- 信息与通信工程，硕士，推免

### 中国科学技术大学

2018.09 - 2022.07

- 自动化，学士，优秀毕业生

### 中央大学附属中坜高级中学

2015.09 - 2018.06

## 论文

- Enhancing SEEG-Based Speech Decoding via Convolutional Encoder-Decoder and Scale-Recursive Reconstructor. IEEE Sensors Journal.

## 荣誉与实践

- 教育部港澳台学生奖学金 2 次
- 研究生学业奖学金 3 次
- 优秀学生奖学金 2 次
- 第十九届 RoboGame 机器人大赛亚军
- 本科毕业优秀毕业生

## 联系方式

- Email：heyuanyu@mail.ustc.edu.cn
- GitHub：[yuanyu1016](https://github.com/yuanyu1016)
- Contact page：[/contact/](/contact/)
