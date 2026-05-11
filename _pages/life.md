---
title: "Life"
permalink: /life/
author_profile: false
---

<style>
.life-page {
  font-size: 1.08rem;
  line-height: 1.7;
}

.life-intro {
  margin-bottom: 1.6rem;
  color: #555555;
}

.life-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 2rem;
  margin-top: 1.8rem;
}

.life-card {
  border-bottom: 1px solid #e5e5e5;
  padding-bottom: 1.2rem;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.life-card:hover {
  transform: translateY(-2px);
}

.life-card img {
  width: 100%;
  height: 260px;
  display: block;
  object-fit: cover;
  border-radius: 6px;
}

.life-caption {
  margin-top: 0.75rem;
  font-size: 1.02rem;
  color: #333333;
}

.life-year {
  font-weight: 700;
  color: #005a3c;
  margin-right: 0.5rem;
}

.life-text {
  color: #444444;
}

@media (max-width: 768px) {
  .life-grid {
    grid-template-columns: 1fr;
    gap: 1.5rem;
  }

  .life-card img {
    height: auto;
  }
}
</style>

<div class="life-page">

<h1>Life</h1>

<p class="life-intro">
Selected moments from my academic life and personal experiences.
</p>

<div class="life-grid">

  <div class="life-card">
    <img src="/images/2026.jpg" alt="Reunion with old friends, 2026">
    <div class="life-caption">
      <span class="life-year">2026</span>
      <span class="life-text">Reunion with old friends</span>
    </div>
  </div>

  <div class="life-card">
    <img src="/images/2025.jpg" alt="Chengdu World Games, 2025">
    <div class="life-caption">
      <span class="life-year">2025</span>
      <span class="life-text">Chengdu World Games</span>
    </div>
  </div>

  <div class="life-card">
    <img src="/images/2024.jpg" alt="With my roommates, 2024">
    <div class="life-caption">
      <span class="life-year">2024</span>
      <span class="life-text">With my roommates</span>
    </div>
  </div>

  <div class="life-card">
    <img src="/images/2023.jpg" alt="Qingdao, 2023">
    <div class="life-caption">
      <span class="life-year">2023</span>
      <span class="life-text">Qingdao</span>
    </div>
  </div>

  <div class="life-card">
    <img src="/images/2022.jpg" alt="Orientation training for freshmen, 2022">
    <div class="life-caption">
      <span class="life-year">2022</span>
      <span class="life-text">Orientation training for freshmen</span>
    </div>
  </div>

  <div class="life-card">
    <img src="/images/2021.jpg" alt="Football League, 2021">
    <div class="life-caption">
      <span class="life-year">2021</span>
      <span class="life-text">Football League</span>
    </div>
  </div>

</div>

</div>
