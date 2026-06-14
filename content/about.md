---
title: Showcase
description: 项目展示
layout: showcase
date: 2026-06-06T17:00:00+08:00
lastmod: 2026-06-06T17:00:00+08:00
---

<div class="showcase-item">
<div class="showcase-text">
<h2 class="showcase-title">Morning 3K Run</h2>
<p>Since joining the laboratory, running three kilometers in the morning has gradually become an important habit in my daily life. It is not only a way to strengthen my body, but also a form of preparation for academic research, helping me build the physical endurance, discipline, and focus needed for long-term exploration.</p>
<p>Morning running also reminds me of the spirit of scientific research. Progress is not achieved through a single moment of effort, but through persistence, adjustment, and accumulation day by day. Each run teaches me to keep a steady rhythm, overcome fatigue, and move forward with patience, which is similar to the process of facing challenges in research.</p>
<p>More importantly, running with my teammates has made this habit more meaningful. A person may run faster alone, but a team can run farther together. Through team running, I have learned the value of encouragement, cooperation, and shared persistence. These experiences have helped me develop a stronger body, a more resilient mindset, and a deeper understanding of teamwork, all of which support my growth as an engineering student and researcher.</p>
</div>
<div class="showcase-media">
<div class="showcase-slider">
<div class="showcase-track">
<img class="showcase-slide is-active no-lightbox lazyload" src="/showcase/morning-run-1.png" alt="Morning 3K Run photo 1" />
<img class="showcase-slide no-lightbox lazyload" src="/showcase/morning-run-2.png" alt="Morning 3K Run photo 2" />
<img class="showcase-slide no-lightbox lazyload" src="/showcase/morning-run-3.png" alt="Morning 3K Run photo 3" />
<img class="showcase-slide no-lightbox lazyload" src="/showcase/morning-run-4.png" alt="Morning 3K Run photo 4" />
</div>
<button type="button" class="showcase-arrow showcase-next" aria-label="Next slide">›</button>
<div class="showcase-dots" role="tablist">
<button type="button" class="showcase-dot is-active" data-index="0" aria-label="Slide 1"></button>
<button type="button" class="showcase-dot" data-index="1" aria-label="Slide 2"></button>
<button type="button" class="showcase-dot" data-index="2" aria-label="Slide 3"></button>
<button type="button" class="showcase-dot" data-index="3" aria-label="Slide 4"></button>
</div>
</div>
</div>
</div>

<style>
.showcase-page .article-inner,
.showcase-page .article-entry {
  padding: 0;
  margin: 0;
}
.showcase-item {
  display: flex;
  gap: 24px;
  align-items: stretch;
  flex-wrap: nowrap;
  margin: 0;
  font-family: "Times New Roman", "KaiTi", "楷体", "STKaiti", "AR PL UKai CN", serif;
  font-weight: 700;
}
.showcase-text {
  flex: 1 1 50%;
  min-width: 0;
  background: var(--color-wrap, #fff);
  border-radius: 10px;
  padding: 24px 28px;
  box-shadow: var(--shadow-card, 0 2px 12px rgba(0,0,0,0.06));
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
}
.showcase-title {
  margin: 0 0 12px;
  font-size: 1.65rem;
  font-weight: 700;
  border-bottom: 1px solid var(--red-4, #eee);
  padding-bottom: 10px;
}
.showcase-text p {
  text-align: justify;
  line-height: 1.65;
  margin: 0 0 12px;
  font-size: 0.92rem;
}
.showcase-text p:last-child { margin-bottom: 0; }
.showcase-media {
  flex: 1 1 50%;
  min-width: 0;
  display: flex;
  align-items: stretch;
}
.showcase-slider {
  position: relative;
  width: 100%;
  flex: 1;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: var(--shadow-card, 0 2px 12px rgba(0,0,0,0.06));
  background: #f5f5f5;
  min-height: 100%;
}
.showcase-track {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
}
.showcase-slide {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: center;
  opacity: 0;
  z-index: 0;
  transition: opacity 0.45s ease;
}
.showcase-slide.is-active { opacity: 1; z-index: 1; }
.showcase-arrow {
  position: absolute;
  top: 50%;
  right: 10px;
  transform: translateY(-50%);
  width: 34px;
  height: 34px;
  border: none;
  border-radius: 50%;
  background: rgba(255,255,255,0.88);
  color: #666;
  font-size: 1.4rem;
  line-height: 1;
  cursor: pointer;
  box-shadow: 0 2px 8px rgba(0,0,0,0.12);
  z-index: 2;
}
.showcase-arrow:hover { background: #fff; color: var(--red-1, #42a5f5); }
.showcase-dots {
  position: absolute;
  left: 50%;
  bottom: 12px;
  transform: translateX(-50%);
  display: flex;
  gap: 8px;
  align-items: center;
  z-index: 2;
}
.showcase-dot {
  width: 18px;
  height: 4px;
  padding: 0;
  border: none;
  border-radius: 2px;
  background: rgba(255,255,255,0.55);
  cursor: pointer;
}
.showcase-dot.is-active {
  width: 28px;
  background: rgba(255,255,255,0.95);
}
@media (max-width: 900px) {
  .showcase-item { flex-wrap: wrap; }
  .showcase-text, .showcase-media { flex: 1 1 100%; }
  .showcase-slider { min-height: 320px; }
}
</style>
