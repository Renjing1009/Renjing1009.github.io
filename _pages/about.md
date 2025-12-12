---
layout: single
permalink: /
title: "About me"
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<style>
/* ===== Layout ===== */
.about-wrap {
  max-width: 1100px;
  margin: 32px auto;
  display: flex;
  gap: 36px;
  align-items: flex-start;
  padding: 0 16px;
  box-sizing: border-box;
}

/* ===== Sidebar ===== */
.about-sidebar {
  width: 260px;
  flex: 0 0 260px;
  padding: 18px;
  border: 1px solid #ececec;
  border-radius: 6px;
  background: #fff;
  box-shadow: 0 1px 0 rgba(0,0,0,0.03);
  box-sizing: border-box;
}

.about-sidebar .avatar {
  width: 110px;
  height: 110px;
  border-radius: 50%;
  display: block;
  margin: 0 auto 12px auto;
  object-fit: cover;
  border: 4px solid #fff;
  box-shadow: 0 0 0 4px rgba(0,0,0,0.03);
}

.about-sidebar h2 {
  text-align: center;
  margin: 6px 0 8px;
  font-size: 18px;
}

.about-sidebar p {
  font-size: 13px;
  line-height: 1.45;
  color: #333;
}

.about-sidebar ul {
  list-style: none;
  padding: 0;
  margin-top: 12px;
  font-size: 14px;
}

.about-sidebar li {
  margin: 8px 0;
  display: flex;
  gap: 8px;
  align-items: center;
}

.about-sidebar a {
  color: #0b6dbf;
  text-decoration: none;
}

/* ===== Main content ===== */
.about-main {
  flex: 1 1 0;
  min-width: 0;
}

.about-main .content {
  max-width: 760px;
  margin: 0 auto;
}

.about-main h1 {
  font-size: 28px;
  margin-bottom: 12px;
}

.about-main h2 {
  margin-top: 28px;
  margin-bottom: 12px;
  font-size: 20px;
}

.about-main p {
  line-height: 1.6;
  color: #222;
}

.pub-year {
  margin-top: 24px;
  color: #2a6fb0;
  font-weight: 600;
}

.pub-item {
  margin: 14px 0 18px;
  line-height: 1.45;
}

.pub-item .meta {
  color: #666;
  font-size: 13px;
  margin-top: 6px;
}

/* ===== Responsive ===== */
@media (max-width: 880px) {
  .about-wrap {
    flex-direction: column;
    gap: 20px;
  }

  .about-sidebar {
    width: 100%;
    display: flex;
    gap: 14px;
    align-items: center;
  }

  .about-sidebar .avatar {
    width: 72px;
    height: 72px;
    margin: 0;
  }

  .about-main .content {
    max-width: 100%;
  }
}
</style>

<div class="about-wrap">

<!-- ===== Sidebar ===== -->
<aside class="about-sidebar">
  <img class="avatar" src="{{ '/images/IMG_20191228_170234.jpg' | relative_url }}" alt="Ren Jing photo">

  <h2>Ren Jing</h2>

  <p>
    Postdoctoral Fellow<br>
    Institute of Applied Ecology, CAS<br>
    CSC Scholar at IRD, France
  </p>

  <ul>
    <li>📍 China / France</li>
    <li>🏫 Institute of Applied Ecology, CAS</li>
    <li>✉️ <a href="mailto:your.email@institute.edu">your.email@institute.edu</a></li>
    <li>🔎 <a href="https://scholar.google.com/citations?user=YOURID" target="_blank">Google Scholar</a></li>
    <li>🆔 <a href="https://orcid.org/YOUR-ORCID" target="_blank">ORCID</a></li>
    <li>📄 <a href="{{ '/files/CV.pdf' | relative_url }}" target="_blank">CV (PDF)</a></li>
    <li>🐙 <a href="https://github.com/Renjing1009" target="_blank">GitHub</a></li>
    <li>🔗 <a href="https://www.researchgate.net/profile/YOURNAME" target="_blank">ResearchGate</a></li>
  </ul>
</aside>

<!-- ===== Main ===== -->
<main class="about-main">
  <div class="content">

    <h1>About me</h1>

    <p>
      I am currently a postdoctoral fellow at the Institute of Applied Ecology, Chinese Academy of Sciences, 
      and a recipient of the China Scholarship Council (CSC) scholarship to conduct research at IRD in France. 
      My research focuses on tree growth, functional traits, and forest ecology.
    </p>

    <h2>Research interests</h2>
    <ul>
      <li>Tree growth and forest dynamics</li>
      <li>Functional traits and plant strategies</li>
      <li>Neighborhood competition and environmental stress</li>
      <li>Temperate forest ecology</li>
    </ul>

    <h2>Selected publications</h2>

    <p>Jump to year:
      <a href="#y2025">2025</a>,
      <a href="#y2024">2024</a>,
      <a href="#y2023">2023</a>
    </p>

    <div id="y2026" class="pub-year">2025</div>
    <div class="pub-item">
      <strong>Functional traits shape tree growth response to winter freeze–thaw cycle and neighborhood crowding in humid temperate forests</strong>
      <div class="meta">
        J. Ren, S. Fang, G. Hao, F. Lin, J. Ye, Z. Hao, X. Wang & C. Fortunel.
        <em>Agricultural and Forest Meteorology</em>, 377: 110954.
        <a href="/publication/ren-2025-freeze-thaw-traits">details</a>
      </div>
    </div>

    <div id="y2024" class="pub-year">2024</div>
    <div class="pub-item">
      <strong>Disturbance history, neighborhood crowding and soil conditions jointly shape tree growth in temperate forests</strong>
      <div class="meta">
        S. Fang, J. Ren, M. W. Cadotte, et al.
        <em>Oecologia</em>, 205: 295–306.
        <a href="/publication/ren-2024-disturbance-history">details</a>
      </div>
    </div>

    <div id="y2023" class="pub-year">2023</div>
    <div class="pub-item">
      <strong>Ontogeny influences tree growth response to soil fertility and neighborhood crowding in an old-growth temperate forest</strong>
      <div class="meta">
        J. Ren et al.
        <em>Annals of Botany</em>, 131: 1061–1072.
      </div>
    </div>

    <p>
      A complete list of publications is available on the
      <a href="/publications/">Publications</a> page.
    </p>

  </div>
</main>

</div>

---

Copyright © 2021–2025 Jing Ren
