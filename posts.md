---
title: "文章"
permalink: /posts/
layout: single
author_profile: false
---

<main class="hyy-site">
  <article class="hyy-doc hyy-posts">
    <header class="hyy-doc-header hyy-posts-header">
      <p class="hyy-kicker">Posts</p>
      <h1>文章是慢一点的通信。</h1>
      <p class="hyy-lede">这里放不适合塞进简历的想法：关于 AI Agent、工程系统、研究、写作，以及人与人之间如何保持清晰连接。</p>
    </header>

    <ul class="hyy-posts-list" aria-label="文章列表">
      {% for post in site.posts %}
        <li>
          <a href="{{ post.url | relative_url }}">
            <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%a, %d %b %Y" }}</time>
            <span>{{ post.title }}</span>
          </a>
        </li>
      {% endfor %}
    </ul>

    <p class="hyy-posts-action">
      <a href="mailto:heyuanyu@mail.ustc.edu.cn?subject=从文章页开始的一封信">Write to me</a>
    </p>
  </article>
</main>
