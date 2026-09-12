---
title: "简历"
permalink: /resume-entry/
author_profile: false
---

<style>
  .hyy-resume {
    width: var(--hyy-wide);
    margin-inline: auto;
  }

  .hyy-resume :is(h1, h2, h3, p, ul) {
    margin-top: 0;
  }

  .hyy-resume p,
  .hyy-resume li {
    line-height: 1.72;
    text-wrap: pretty;
  }

  .hyy-resume .hero {
    width: var(--hyy-prose);
    margin: 0 auto clamp(4rem, 8vw, 6rem);
    text-align: center;
  }

  .hyy-resume .eyebrow,
  .hyy-resume .meta,
  .hyy-resume .label {
    color: var(--hyy-muted);
    font-family: var(--hyy-ui);
    font-size: 0.82rem;
    font-weight: 500;
    line-height: 1.45;
    text-transform: uppercase;
  }

  .hyy-resume .hero h1 {
    margin: 1.1rem 0 1.2rem;
    color: var(--hyy-ink);
    font-family: var(--hyy-serif);
    font-size: clamp(2.2rem, 5vw, 4.8rem);
    font-style: italic;
    font-weight: 500;
    letter-spacing: 0;
    line-height: 1.1;
    text-wrap: balance;
  }

  .hyy-resume .positioning {
    max-width: 39rem;
    margin: 0 auto;
    color: var(--hyy-muted);
    font-size: clamp(1.05rem, 1rem + 0.35vw, 1.22rem);
    line-height: 1.85;
  }

  .hyy-resume .actions {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 0.8rem 1.1rem;
    margin-top: 2rem;
  }

  .hyy-resume a {
    color: inherit;
    text-decoration-line: underline;
    text-decoration-style: dotted;
    text-decoration-thickness: 0.06em;
    text-underline-offset: 0.16em;
    transition: color 180ms ease;
  }

  .hyy-resume a:hover {
    color: var(--hyy-accent);
    text-decoration-style: solid;
  }

  .hyy-resume .contact {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1px;
    margin: 0 auto clamp(4rem, 8vw, 6rem);
    border: 1px solid var(--hyy-line);
    background: var(--hyy-line);
    font-style: normal;
  }

  .hyy-resume .contact a,
  .hyy-resume .contact span {
    min-height: 6.5rem;
    padding: 1.15rem 1.25rem;
    background: rgba(250, 249, 245, 0.84);
    text-decoration: none;
  }

  .hyy-resume .contact strong {
    display: block;
    margin-bottom: 0.5rem;
    font-family: var(--hyy-ui);
    font-size: 0.78rem;
    text-transform: uppercase;
  }

  .hyy-resume .contact small {
    color: var(--hyy-muted);
    font-size: 1rem;
    line-height: 1.65;
  }

  .hyy-resume .section {
    display: grid;
    grid-template-columns: minmax(8.5rem, 13rem) minmax(0, 1fr);
    gap: clamp(1.25rem, 4vw, 3.2rem);
    padding: clamp(1.5rem, 3.4vw, 2.2rem) 0;
    border-top: 1px solid var(--hyy-line);
  }

  .hyy-resume .section:first-of-type {
    border-top-color: var(--hyy-line-strong);
  }

  .hyy-resume .section h2,
  .hyy-resume .entry h3,
  .hyy-resume .mini h3 {
    margin: 0 0 0.5rem;
    color: var(--hyy-ink);
    font-family: var(--hyy-serif);
    font-size: clamp(1.18rem, 1.55vw, 1.52rem);
    font-style: italic;
    font-weight: 500;
    line-height: 1.28;
    text-wrap: balance;
  }

  .hyy-resume .entry {
    padding-bottom: 1.75rem;
  }

  .hyy-resume .entry:last-child {
    padding-bottom: 0;
  }

  .hyy-resume .role,
  .hyy-resume .stack,
  .hyy-resume .publication-meta {
    color: var(--hyy-muted);
    font-size: 1rem;
  }

  .hyy-resume .entry ul,
  .hyy-resume .plain-list {
    margin: 0.7rem 0 0;
    padding-left: 1.15rem;
  }

  .hyy-resume .entry li,
  .hyy-resume .plain-list li {
    margin-bottom: 0.35rem;
  }

  .hyy-resume .two-column {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1.4rem 2.2rem;
  }

  .hyy-resume .mini {
    margin-bottom: 1.35rem;
  }

  .hyy-resume .mini:last-child {
    margin-bottom: 0;
  }

  .hyy-resume .footer-note {
    width: var(--hyy-prose);
    margin: clamp(3rem, 7vw, 5rem) auto 0;
    color: var(--hyy-muted);
    font-family: var(--hyy-ui);
    font-size: 0.82rem;
    line-height: 1.7;
    text-align: center;
  }

  @media (max-width: 900px) {
    .hyy-resume .hero {
      text-align: left;
    }

    .hyy-resume .positioning {
      margin-left: 0;
    }

    .hyy-resume .actions {
      justify-content: flex-start;
    }
  }

  @media (max-width: 760px) {
    .hyy-resume,
    .hyy-resume .hero,
    .hyy-resume .footer-note {
      width: 100%;
    }

    .hyy-resume .contact,
    .hyy-resume .section,
    .hyy-resume .two-column {
      grid-template-columns: 1fr;
    }
  }

  @media print {
    .masthead,
    .page__footer,
    .hyy-resume .actions {
      display: none;
    }

    .hyy-resume {
      width: auto;
      padding: 0;
    }

    .hyy-resume .hero,
    .hyy-resume .contact,
    .hyy-resume .section {
      break-inside: avoid;
    }
  }
</style>

<main class="hyy-site">
  <article id="resume-content" class="hyy-resume" aria-label="何元玉简历">

    <header class="hero">
      <p class="eyebrow">AI systems · Backend engineering</p>
      <h1>何元玉</h1>
      <p class="positioning">面向 AI Agent、工作流自动化与智能系统的工程实践者，具备 Spring AI / LangChain4j、RAG、后端工程与深度学习科研经验。</p>
      <div class="actions">
        <a href="mailto:heyuanyu@mail.ustc.edu.cn">联系候选人</a>
        <a href="/assets/resume/Yuanyu_He_Resume.pdf">下载 PDF</a>
      </div>
    </header>

    <address class="contact">
      <a href="tel:+8613083066971"><strong>Tel</strong><small>13083066971</small></a>
      <a href="mailto:heyuanyu@mail.ustc.edu.cn"><strong>Mail</strong><small>heyuanyu@mail.ustc.edu.cn</small></a>
      <span><strong>WeChat</strong><small>YUANYU_1016</small></span>
      <a href="https://yuanyu1016.github.io" target="_blank" rel="noopener noreferrer"><strong>Site</strong><small>yuanyu1016.github.io</small></a>
    </address>

    <section class="section" aria-labelledby="profile-title">
      <p class="label">Profile</p>
      <div>
        <h2 id="profile-title">个人简介</h2>
        <p>擅长把模型、工具、数据、状态和反馈机制组织为可追踪、可验证、可复用的产品链路。核心方向包括 Agent 工作流、RAG、工具调用、后端可靠性和研究工程。</p>
      </div>
    </section>

    <section class="section" aria-labelledby="experience-title">
      <p class="label">Experience</p>
      <div>
        <h2 id="experience-title">实习经历</h2>
        <article class="entry">
          <p class="meta">2026.06 - 2026.08</p>
          <h3>智学星途｜AI 教育 B/C 端产品研发</h3>
          <p class="role">Agent 开发实习生 · 教师 Agent / AI 教案 / AI 课件 / 工具开放能力</p>
          <ul>
            <li>负责 MAIC PPT Agent 模块，拆分需求解析、大纲确认、页面规划、图片生成、预览编辑、结构化输出、重试、任务队列与工作节点调度。</li>
            <li>参与普通教案、目标驱动教案、新教材理解等场景，串联意图识别、任务路由、资料上传、过程状态与历史管理。</li>
            <li>接入可信源、用户/平台资料、网页回退与事实核验；参与 MCP / Skill、API 密钥、Token 审核、附件工具及接入文档建设。</li>
          </ul>
          <p class="stack">Java · Spring Boot · Next.js · Agent 工作流 · Tool Calling · MCP · Skill · MySQL · Redis</p>
        </article>
      </div>
    </section>

    <section class="section" aria-labelledby="projects-title">
      <p class="label">Projects</p>
      <div>
        <h2 id="projects-title">代表项目</h2>
        <article class="entry">
          <p class="meta">2025.04 - 2025.07</p>
          <h3>基于大模型的智能健康对话 Agent 系统</h3>
          <p class="role">0→1 核心模块负责人 · RAG / Agent 规划 / 工具体系</p>
          <ul>
            <li>基于 PGvector 设计检索链路，以查询重写和多维过滤优化准确度与召回率，有效应答率提升 37%。</li>
            <li>基于 ReAct + CoT 构建分层规划架构，集成联网搜索、抓取、文件、邮件、地图及图片搜索等 Tool Calling / MCP 能力。</li>
            <li>使用 Dockerfile 容器化并部署至 Serverless 平台，支持按需扩缩容。</li>
          </ul>
          <p class="stack"><a href="https://github.com/yuanyu1016/ai-agent" target="_blank" rel="noopener noreferrer">github.com/yuanyu1016/ai-agent</a></p>
        </article>

        <article class="entry">
          <p class="meta">2024.07 - 2024.11</p>
          <h3>云端存储智能协同图库管理平台</h3>
          <p class="role">0→1 后端核心模块负责人 · 数据治理 / 异步任务 / 实时协同</p>
          <ul>
            <li>以 DDD 划分领域，组合 ShardingSphere 分库分表、Elasticsearch 检索及 Redis + Caffeine 多级缓存。</li>
            <li>RabbitMQ 削峰解耦 AI 扩图和批量编辑，Redisson 限流控成本；WebSocket + Sa-Token RBAC + Disruptor 支撑团队协同。</li>
          </ul>
          <p class="stack"><a href="https://github.com/yuanyu1016/picture-backend-ddd" target="_blank" rel="noopener noreferrer">github.com/yuanyu1016/picture-backend-ddd</a></p>
        </article>
      </div>
    </section>

    <section class="section" aria-labelledby="research-title">
      <p class="label">Research</p>
      <div>
        <h2 id="research-title">科研经历</h2>
        <article class="entry">
          <p class="meta">2023.07 - 2026.03</p>
          <h3>基于深度学习的脑电语音解码研究</h3>
          <p class="role">第一作者 · 研究与模型模块负责人 · SEEG 语音解码</p>
          <ul>
            <li>设计 ConvED-SR 卷积编码器-解码器，缓解稀疏数据条件下的过拟合。</li>
            <li>构建 Scale-Recursive Reconstructor，以多尺度频谱融合将 MCD 降低 2.38 dB。</li>
            <li>探索 Hifi-Codec + Transformer 脑电-语音特征对齐；第一作者论文被 IEEE Sensors Journal 接收。</li>
          </ul>
          <p class="stack"><a href="https://github.com/yuanyu1016/ConvED-SR" target="_blank" rel="noopener noreferrer">github.com/yuanyu1016/ConvED-SR</a></p>
        </article>
      </div>
    </section>

    <section class="section" aria-labelledby="education-title">
      <p class="label">Education</p>
      <div class="two-column">
        <article class="mini">
          <h3 id="education-title">中国科学技术大学</h3>
          <p class="meta">2022.09 - 2027.03</p>
          <p>信息与通信工程 · 硕士（推免）<br>类脑智能技术及应用国家工程实验室</p>
        </article>
        <article class="mini">
          <h3>中国科学技术大学</h3>
          <p class="meta">2018.09 - 2022.06</p>
          <p>自动化 · 学士 · 优秀毕业生</p>
        </article>
      </div>
    </section>

    <section class="section" aria-labelledby="skills-title">
      <p class="label">Skills</p>
      <div class="two-column">
        <article class="mini">
          <h3 id="skills-title">AI / Agent</h3>
          <p>Spring AI, LangChain4j, RAG, Agent 工作流, ReAct, Tool Calling, MCP, 提示词工程, PyTorch, Transformer</p>
        </article>
        <article class="mini">
          <h3>后端工程</h3>
          <p>Spring Boot, MyBatis, MySQL, Redis, RabbitMQ, Elasticsearch, Nginx, Spring Cloud, WebSocket</p>
        </article>
        <article class="mini">
          <h3>编程语言</h3>
          <p>Java, Python；掌握 C/C++</p>
        </article>
        <article class="mini">
          <h3>工程能力</h3>
          <p>Linux, Docker, Git, Serverless, 任务拆解, 状态管理, 执行反馈, 循环验证</p>
        </article>
      </div>
    </section>

    <section class="section" aria-labelledby="honors-title">
      <p class="label">Honors</p>
      <div>
        <h2 id="honors-title">荣誉与实践</h2>
        <ul class="plain-list">
          <li><strong>教育部港澳台学生奖学金</strong> · 2 次</li>
          <li><strong>研究生学业奖学金</strong> · 3 次</li>
          <li><strong>优秀学生奖学金</strong> · 2 次</li>
          <li><strong>第十九届 RoboGame 机器人大赛</strong> · 亚军</li>
          <li><strong>学生工作：</strong>本科连续四年担任班委</li>
          <li><strong>教学：</strong>《微机原理和嵌入式系统》课程助教</li>
        </ul>
      </div>
    </section>

    <p class="footer-note">需要一个能把 AI 应用落到工程系统的人，欢迎联系我讨论 AI Agent、RAG、工作流编排、后端工程和科研工程相关机会。</p>
  </article>
</main>
