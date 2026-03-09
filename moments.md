---
layout: page
title: 岁岁年年
description: 时光流转，岁月留痕
permalink: /moments/
---

<div class="timeline">
    <div class="timeline-item">
        <div class="timeline-date">2023</div>
        <div class="timeline-content">
            <h3>🎊 新的开始</h3>
            <p>创建了这个博客，记录生活的点滴...</p>
        </div>
    </div>

    <div class="timeline-item">
        <div class="timeline-date">2025.2.9</div>
        <div class="timeline-content">
            <a href="{{ '/moments/yuyi/' | relative_url }}" class="moment-link">
                <h3>雨衣</h3>
                <p> </p>
                <span class="read-more">阅读全文 →</span>
            </a>
        </div>
    </div>

    <div class="timeline-item">
        <div class="timeline-date">Coming</div>
        <div class="timeline-content">
            <h3>✨ 更多记忆</h3>
            <p>即将添加更多珍贵的回忆...</p>
        </div>
    </div>
</div>

<style>
.timeline {
    position: relative;
    max-width: 800px;
    margin: 0 auto;
}

.timeline::before {
    content: '';
    position: absolute;
    left: 50%;
    transform: translateX(-50%);
    width: 2px;
    height: 100%;
    background: linear-gradient(180deg, #6366f1, #8b5cf6);
}

.timeline-item {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 3rem;
    position: relative;
}

.timeline-item:nth-child(odd) {
    flex-direction: row-reverse;
}

.timeline-date {
    flex: 1;
    text-align: center;
    font-size: 1.5rem;
    font-weight: 700;
    color: #6366f1;
}

.timeline-content {
    flex: 1;
    background: white;
    padding: 1.5rem;
    border-radius: 15px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: all 0.3s ease;
}

.timeline-content:hover {
    transform: scale(1.05);
    box-shadow: 0 10px 25px rgba(0, 0, 0, 0.15);
}

.moment-link {
    text-decoration: none;
    color: inherit;
    display: block;
}

.timeline-content h3 {
    color: #1f2937;
    margin-bottom: 0.5rem;
    transition: color 0.3s ease;
    font-size: 1.3rem;
}

.moment-link:hover h3 {
    color: #6366f1;
}

.timeline-content p {
    color: #6b7280;
    margin-bottom: 0.5rem;
    font-size: 0.95rem;
    min-height: 1.2em;
}

.read-more {
    color: #6366f1;
    font-size: 0.9rem;
    font-weight: 600;
    display: inline-block;
    transition: all 0.3s ease;
}

.moment-link:hover .read-more {
    transform: translateX(5px);
    color: #8b5cf6;
}

@media (max-width: 768px) {
    .timeline::before {
        left: 20px;
    }

    .timeline-item {
        flex-direction: column !important;
        align-items: flex-start;
        padding-left: 50px;
    }

    .timeline-date {
        text-align: left;
        margin-bottom: 1rem;
    }
}
</style>