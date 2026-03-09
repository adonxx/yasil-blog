---
layout: page
title: 雨衣
permalink: /moments/yuyi/
---

<div class="moment-detail">
    <div class="moment-header">
        <span class="moment-date">2025年2月</span>
        <h1>**雨衣**</h1>
    </div>

    <div class="moment-content poem-content">
        <p>晚饭后</p>
        <p>看到小孩坐在妈妈的电瓶车上</p>
        <p>想起小时候</p>
        <p>坐在同样的后座</p>
        <p>罩在雨衣里</p>
        <p>透过雨衣的下摆观察着路面</p>
        <p>炊烟的味道、转弯的味道</p>
        <p>默念时时间、转弯的声音</p>
        <p>都是我用来揣测现在正赶到某街某巷的线索</p>
        <p>水滴顺着雨衣裙摆轻轻啊长裙</p>
        <p>我迟不及待想验证已己的正确与否</p>
        <p>掀开雨衣</p>
        <p>已是二十年后</p>
        <p class="bgm-note">BGM：时间煮雨 - 陈思宇</p>
    </div>

    <div class="moment-footer">
        <a href="{{ '/moments/' | relative_url }}" class="back-btn">← 返回</a>
    </div>
</div>

<style>
.moment-detail {
    max-width: 800px;
    margin: 0 auto;
}

.moment-header {
    text-align: center;
    margin-bottom: 3rem;
}

.moment-date {
    display: inline-block;
    color: #8b5cf6;
    font-size: 0.9rem;
    font-weight: 600;
    background: rgba(139, 92, 246, 0.1);
    padding: 0.5rem 1rem;
    border-radius: 20px;
    margin-bottom: 1rem;
}

.moment-header h1 {
    font-size: 2.5rem;
    color: #1f2937;
    margin-top: 1rem;
}

.moment-content {
    line-height: 2;
    padding: 2rem;
    background: rgba(255, 255, 255, 0.95);
    border-radius: 15px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

/* 诗歌内容右对齐 */
.poem-content p {
    text-align: right;
    margin-bottom: 1.2rem;
    color: #374151;
    font-size: 1.1rem;
    font-family: "KaiTi", "楷体", serif;
    letter-spacing: 1px;
}

/* BGM提示特殊样式 */
.poem-content .bgm-note {
    font-size: 0.9rem;
    color: #8b5cf6;
    font-style: italic;
    margin-top: 2rem;
    padding-top: 1rem;
    border-top: 1px solid #e5e7eb;
}

.moment-footer {
    margin-top: 3rem;
    padding-top: 2rem;
    border-top: 2px solid #e5e7eb;
    text-align: center;
}

.back-btn {
    display: inline-block;
    padding: 0.75rem 2rem;
    background: linear-gradient(135deg, #6366f1, #8b5cf6);
    color: white;
    text-decoration: none;
    border-radius: 25px;
    transition: all 0.3s ease;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.back-btn:hover {
    transform: translateY(-2px);
    box-shadow: 0 10px 25px rgba(0, 0, 0, 0.15);
}

/* 淡入动画 */
@keyframes fadeIn {
    from {
        opacity: 0;
        transform: translateY(20px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

.poem-content p {
    animation: fadeIn 0.8s ease;
    animation-fill-mode: both;
}

.poem-content p:nth-child(1) { animation-delay: 0.1s; }
.poem-content p:nth-child(2) { animation-delay: 0.2s; }
.poem-content p:nth-child(3) { animation-delay: 0.3s; }
.poem-content p:nth-child(4) { animation-delay: 0.4s; }
.poem-content p:nth-child(5) { animation-delay: 0.5s; }
.poem-content p:nth-child(6) { animation-delay: 0.6s; }
.poem-content p:nth-child(7) { animation-delay: 0.7s; }
.poem-content p:nth-child(8) { animation-delay: 0.8s; }
.poem-content p:nth-child(9) { animation-delay: 0.9s; }
.poem-content p:nth-child(10) { animation-delay: 1.0s; }
.poem-content p:nth-child(11) { animation-delay: 1.1s; }
.poem-content p:nth-child(12) { animation-delay: 1.2s; }
.poem-content p:nth-child(13) { animation-delay: 1.3s; }
.poem-content p:nth-child(14) { animation-delay: 1.4s; }
</style>