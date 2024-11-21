---
layout: default
title: Home
---

<div class="page-wrapper">
    <div class="hero">
        <h1 class="hero-title">Cheeseman Lab</h1>
    </div>
</div>

<style>
.page-wrapper {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
}

.hero {
    flex: 1;
    width: 100%;
    background-image: url('{{ site.baseurl }}assets/img/research/background.jpg');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    display: flex;
    align-items: center;
    justify-content: center;
}

.hero-title {
    color: white;
    font-size: 4rem;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
}
</style>