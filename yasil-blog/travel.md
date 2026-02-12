---
layout: page
title: 行旅杂记
description: 记录旅行中的点点滴滴
permalink: /travel/
---

<div class="travel-grid">
    <div class="travel-card">
        <div class="travel-placeholder">🏖️</div>
        <h3>待添加旅行记录</h3>
        <p>即将分享旅途中的美好瞬间...</p>
    </div>

    <div class="travel-card">
        <div class="travel-placeholder">🗺️</div>
        <h3>探索世界</h3>
        <p>每一次旅行都是一次成长...</p>
    </div>
</div>

<style>
.travel-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
}

.travel-card {
    background: white;
    padding: 2rem;
    border-radius: 15px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    text-align: center;
    transition: all 0.3s ease;
}

.travel-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 10px 25px rgba(0, 0, 0, 0.15);
}

.travel-placeholder {
    font-size: 4rem;
    margin-bottom: 1rem;
}

.travel-card h3 {
    color: #6366f1;
    margin-bottom: 0.5rem;
}
</style>
