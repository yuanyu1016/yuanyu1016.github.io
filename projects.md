---
title: "项目"
permalink: /projects/
author_profile: false
---

<main class="taste-site">
  <section class="taste-hero">
    <div>
      <p class="taste-kicker">Selected systems</p>
      <h1>项目不是列表，<span class="taste-inline-image" style="background-image: url('https://picsum.photos/seed/system-board/640/360');"></span>是可复用的交付证据。</h1>
      <p>这里保留最能说明能力边界的四类项目：AI 教育工作流、健康对话 Agent、云图库后端系统和 SEEG 语音解码研究。简历页不再重复铺满同样的项目长文。</p>
      <div class="taste-actions">
        <a class="taste-button primary" href="/resume/v15/">视觉版简历</a>
        <a class="taste-button secondary" href="https://github.com/yuanyu1016" target="_blank" rel="noopener noreferrer">GitHub</a>
      </div>
    </div>
    <div class="taste-portrait" style="--taste-image: url('https://picsum.photos/seed/backend-console/1920/1080');" data-caption="Agent workflow · RAG · backend reliability"></div>
  </section>

  <section class="taste-section taste-pin">
    <div class="taste-pin-copy">
      <h2>从生成到系统。</h2>
      <p class="taste-reveal">
        <span>每个</span><span>项目</span><span>都</span><span>围绕</span><span>真实</span><span>约束：</span><span>数据源、</span><span>任务队列、</span><span>工具调用、</span><span>权限、</span><span>验证</span><span>与</span><span>持续迭代。</span>
      </p>
    </div>
    <div class="taste-stack">
      <article>
        <h3>智学星途教师端 AI Agent 与教学工作流平台</h3>
        <p><strong>2026.06 - 2026.08</strong> · 参与教师端 AI 教育产品研发，覆盖教案、课件、资料上传、可信源、事实核验和外部 Agent 工具开放。重点推进 MAIC PPT Agent 的需求解析、大纲确认、页面规划、图片生成、预览编辑、结构化输出、重试和 worker 调度。</p>
      </article>
      <article>
        <h3>基于大模型的智能健康对话 Agent 系统</h3>
        <p><strong>2025.04 - 2025.07</strong> · 基于 Spring AI 和 PGvector 构建 RAG 系统，接入联网搜索、网页抓取、文件、邮件、地图和图片搜索等工具调用，使用 ReAct 与 CoT 构建分层规划 Agent，有效应答率提高 37%。</p>
      </article>
      <article>
        <h3>云端存储智能协同图库管理平台</h3>
        <p><strong>2024.07 - 2024.11</strong> · 基于 Spring Boot、DDD、ShardingSphere、Elasticsearch、Redis、Caffeine、RabbitMQ、Redisson、WebSocket、Sa-Token 和 Disruptor，完成高并发图片资源管理和团队协同链路。</p>
      </article>
      <article>
        <h3>基于深度学习的脑电语音解码研究</h3>
        <p><strong>2023.07 - 2026.03</strong> · 设计 ConvED-SR 和 Scale-Recursive Reconstructor，面向 SEEG 语音解码解决稀疏数据、过拟合和频谱重建问题，MCD 降低 2.38 dB。</p>
      </article>
    </div>
  </section>

  <section class="taste-section">
    <div class="taste-bento">
      <a class="taste-card large image" href="https://github.com/yuanyu1016/ai-agent" target="_blank" rel="noopener noreferrer" style="--taste-image: url('https://picsum.photos/seed/health-agent/1920/1080');">
        <h2>Health Agent</h2>
        <p>Spring AI · PGvector · RAG · ReAct · Tool Calling · MCP · Docker · Serverless</p>
      </a>
      <a class="taste-card medium" href="https://github.com/yuanyu1016/picture-backend-ddd" target="_blank" rel="noopener noreferrer">
        <h3>Picture Backend</h3>
        <p>DDD、分库分表、多级缓存、异步任务和协同编辑。</p>
      </a>
      <a class="taste-card medium image" href="https://github.com/yuanyu1016/ConvED-SR" target="_blank" rel="noopener noreferrer" style="--taste-image: url('https://picsum.photos/seed/seeg-lab/1920/1080');">
        <h3>ConvED-SR</h3>
        <p>SEEG speech decoding research implementation.</p>
      </a>
      <div class="taste-card small">
        <h3>Agent Tooling</h3>
        <p>MCP · Skill · API Key · Token 审核 · 接入文档。</p>
      </div>
      <div class="taste-card small">
        <h3>Reliability</h3>
        <p>任务队列、重试、结构化输出、限流、权限和部署。</p>
      </div>
      <div class="taste-card small">
        <h3>Research</h3>
        <p>模型设计、实验验证、英文论文写作和结果复现。</p>
      </div>
    </div>
  </section>
</main>
