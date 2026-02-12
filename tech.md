---
layout: page
title: 技术怪谈
description: 技术探索与奇思妙想
permalink: /tech/
---

<div class="tech-posts">
    <article class="tech-post">
        <div class="post-icon">💻</div>
        <h3>欢迎来到技术专区</h3>
        <p class="post-meta">2025-02-12</p>
        <p>这里将分享各种技术文章、编程心得和项目经验...</p>
        <a href="#" class="read-more">阅读更多 →</a>
    </article>

    <article class="tech-post">
        <div class="post-icon">🚀</div>
        <h3>即将发布</h3>
        <p class="post-meta">Coming Soon</p>
        <p>更多精彩内容正在路上...</p>
    </article>
</div>

<style>
.tech-posts {
    display: grid;
    gap: 2rem;
}

.tech-post {
    background: white;
    padding: 2rem;
    border-radius: 15px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: all 0.3s ease;
    position: relative;
    overflow: hidden;
}

.tech-post::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 4px;
    background: linear-gradient(90deg, #6366f1, #8b5cf6);
    transform: scaleX(0);
    transition: transform 0.3s ease;
}

.tech-post:hover::before {
    transform: scaleX(1);
}

.tech-post:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 25px rgba(0, 0, 0, 0.15);
}

.post-icon {
    font-size: 3rem;
    margin-bottom: 1rem;
}

.tech-post h3 {
    color: #1f2937;
    margin-bottom: 0.5rem;
}

.post-meta {
    color: #6b7280;
    font-size: 0.9rem;
    margin-bottom: 1rem;
}

.read-more {
    color: #6366f1;
    text-decoration: none;
    font-weight: 600;
    transition: all 0.3s ease;
    display: inline-block;
    margin-top: 1rem;
}

.read-more:hover {
    transform: translateX(5px);
    color: #8b5cf6;
}
</style>
