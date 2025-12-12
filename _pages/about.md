---
layout: home
permalink: /
title: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
/* 两栏容器：在大屏显示左右两栏；小屏自动堆叠 */
.about-wrap {
  max-width: 1100px;
  margin: 30px auto;
  display: flex;
  gap: 36px;
  align-items: flex-start;
  padding: 0 16px;
  box-sizing: border-box;
}

/* 左侧侧边栏（窄） */
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

/* 侧栏头像 */
.about-sidebar .avatar {
  width: 110px;
  height: 110px;
  border-radius: 50%;
  display:block;
  margin: 0 auto 12px auto;
  object-fit: cover;
  border: 4px solid #fff;
  box-shadow: 0 0 0 4px rgba(0,0,0,0.03);
}

/* 侧栏名字与简介 */
.about-sidebar h2 { text-align:center; margin: 6px 0 8px; font-size:18px; }
.about-sidebar p { font-size: 13px; line-height:1.45; color:#333; text-align:left; }

/* 侧栏小链接列表 */
.about-sidebar .links { margin-top:12px; list-style:none; padding:0; font-size:14px; }
.about-sidebar .links li { margin:8px 0; display:flex; gap:8px; align-items:center; }
.about-sidebar .links li a { color:#0b6dbf; text-decoration:none; font-size:14px; }

/* 右侧主体（可伸缩） */
.about-main { flex: 1 1 0; min-width: 0; }

/* 主体宽窄控制（让内容看起来不占满整个屏幕）*/
.about-main .content {
  max-width: 720px;
  margin: 0 auto;
  padding-bottom: 40px;
}

/* 标题样式 */
.about-main h1 { font-size: 28px; margin-bottom: 10px; }
.about-main h2 { margin-top: 26px; margin-bottom: 12px; font-size: 20px; }

/* Publications list */
.pub-year { margin-top: 22px; color:#2a6fb0; font-weight:600; }
.pub-item { margin: 14px 0 18px; line-height:1.4; }
.pub-item .meta { color:#666; font-size:13px; margin-top:6px; }

/* 右侧小缩略图（浮动到右） */
.pub-thumb { float:right; width:180px; margin-left:18px; object-fit:cover; }

/* 响应式：小屏时堆叠，侧栏变为顶部小卡片 */
@media (max-width: 880px) {
  .about-wrap { flex-direction: column; padding: 8px; gap: 20px; }
  .about-sidebar { width:100%; flex: none; order: 0; display:flex; gap:12px; align-items:center; }
  .about-sidebar .avatar { width:72px; height:72px; margin:0; }
  .about-sidebar h2 { text-align:left; font-size:16px; }
  .about-main .content { max-width:100%; padding: 0 6px; }
  .pub-thumb { float:none; width:100%; margin: 12px 0; display:block; }
}

/* 更好的可读行距和链接颜色 */
.about-main p { line-height:1.6; color:#222; }
.about-main a { color:#0b6dbf; text-decoration:none; }
.about-main a:hover { text-decoration:underline; }
</style>

<div class="about-wrap">

  <!-- 左侧侧边栏 -->
  <aside class="about-sidebar" aria-label="Sidebar">
    <!-- 把 src 改成你仓库 images 里的头像文件 -->
    <img class="avatar" src="images/bio-photo.jpg" alt="Ren Jing photo">
    <h2>Ren Jing</h2>
    <p>Postdoctoral fellow at Institute of Applied Ecology, Chinese Academy of Sciences.<br>CSC scholar at IRD, France.</p>

    <ul class="links">
      <li>📍 <span>China / France</span></li>
      <li>🏫 <span>Institute of Applied Ecology, CAS</span></li>
      <li>✉️ <a href="mailto:your.email@institute.edu">your.email@institute.edu</a></li>
      <li>🔎 <a href="https://scholar.google.com/citations?user=YOURID" target="_blank">Google Scholar</a></li>
      <li>🆔 <a href="https://orcid.org/YOUR-ORCID" target="_blank">ORCID</a></li>
      <li>📄 <a href="/files/Your_CV.pdf" target="_blank">CV (PDF)</a></li>
      <li>🐙 <a href="https://github.com/Renjing1009" target="_blank">GitHub</a></li>
      <li>🔗 <a href="https://www.researchgate.net/profile/YOURNAME" target="_blank">ResearchGate</a></li>
    </ul>
  </aside>

  <!-- 右侧主要内容 -->
  <main class="about-main">
    <div class="content">
      <h1>About me</h1>

      <p>I am currently a postdoctoral fellow at the Institute of Applied Ecology, Chinese Academy of Sciences, and a recipient of the China Scholarship Council (CSC) scholarship to conduct research at IRD in France. My research focuses on tree growth, functional traits and forest ecology.</p>

      <h2>Publications</h2>

      <p>Jump to year: <a href="#2026">2026</a>, <a href="#2024">2024</a>, <a href="#2023">2023</a>.</p>

      <div id="2026" class="pub-year">2026</div>
      <div class="pub-item">
        <strong>Functional traits shape tree growth response to winter freeze-thaw cycle and neighborhood crowding in humid temperate forests</strong><br>
        <span class="meta">J. Ren, S. Fang, G. Hao, F. Lin, J. Ye, Z. Hao, X. Wang & C. Fortunel. <em>Agricultural and Forest Meteorology</em>, 377: 110954. <a href="/publication/ren-2026-freeze-thaw-traits">details</a></span>
      </div>

      <div id="2024" class="pub-year">2024</div>
      <div class="pub-item">
        <strong>Disturbance history, neighborhood crowding and soil conditions jointly shape tree growth in temperate forests</strong><br>
        <span class="meta">S. Fang, J. Ren, M. W. Cadotte, et al. <em>Oecologia</em>, 205: 295–306. <a href="/publication/ren-2024-disturbance-history">details</a></span>
      </div>

      <div id="2023" class="pub-year">2023</div>
      <div class="pub-item">
        <strong>Ontogeny influences tree growth response to soil fertility and neighborhood crowding in an old-growth temperate forest</strong><br>
        <span class="meta">Ren, J., et al. <em>Annals of Botany</em>, 131: 1061–1072. <a href="/publication/2023-ontogeny-tree-growth-soil-crowding">details</a></span>
      </div>

      <p>If you would like a full list of publications, please visit <a href="/publications/">Publications</a>.</p>

    </div>
  </main>

</div>






Copyright © 2021 – 2025 by Jing Ren | GitHub
