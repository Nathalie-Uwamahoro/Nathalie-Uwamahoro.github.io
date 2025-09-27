---
layout: default
title: "News"
permalink: /news/
---

<style>
  :root{
    --blue:#0b5fff;
    --blue-700:#0a4ed9;
    --orange:#ff7a18;
    --ink:#0f172a;
    --muted:#475569;
    --card:#f8fafc;
    --ring: rgba(11,95,255,.25);
  }
  .news-wrap{max-width:1100px;margin:24px auto;padding:0 16px;}
  .page-title{font-size:34px;line-height:1.2;margin:6px 0 18px;text-align:center;color:var(--blue);}

  /* HERO uses your two images as BACKGROUNDS only */
  .hero{
    display:grid; gap:10px; grid-template-columns: 2fr 1fr;
    margin-bottom:18px;
  }
  .hero-tile{
    position:relative; height:220px; border-radius:16px; overflow:hidden;
    box-shadow:0 8px 24px rgba(2,6,23,.08); background-size:cover; background-position:center;
  }
  .hero-overlay{
    position:absolute; inset:0;
    background:linear-gradient(180deg, rgba(0,0,0,0) 0%, rgba(0,0,0,.55) 100%);
  }
  .hero-caption{
    position:absolute; left:12px; right:12px; bottom:10px;
    color:#fff; font-size:13px;
    text-shadow:0 1px 2px rgba(0,0,0,.4);
  }
  @media (max-width:720px){
    .hero{grid-template-columns:1fr;}
    .hero-tile{height:180px;}
  }

  /* Cards */
  .grid{display:grid;gap:16px;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));}
  .card{
    display:flex; flex-direction:column; background:var(--card);
    border:1px solid #e2e8f0; border-radius:14px; overflow:hidden;
    transition: transform .05s ease, box-shadow .2s ease, border-color .2s ease;
  }
  .card:hover{transform: translateY(-2px); box-shadow:0 10px 28px rgba(2,6,23,.10); border-color:#dbe3f0;}

  /* Gradient thumbs (no images) */
  .thumb{
    height:150px; overflow:hidden;
    background: radial-gradient(120% 120% at 10% 0%, #eaf1ff 0%, #dbeafe 35%, #c7d2fe 55%, #b7c3ff 70%, #ffa76a 100%),
                linear-gradient(135deg, var(--blue), var(--orange));
  }

  .body{padding:12px 14px;}
  .title{
    font-weight:800; font-size:16px; line-height:1.35; margin:0 0 6px;
    color:var(--ink); text-decoration:none;
    background: linear-gradient(90deg,var(--blue),var(--orange));
    -webkit-background-clip:text; background-clip:text; color:transparent;
  }
  .desc{color:var(--muted); font-size:14px; margin:0;}
  .meta{display:flex; gap:8px; margin-top:10px; flex-wrap:wrap;}
  .pill{font-size:11px; padding:3px 8px; border-radius:999px; border:1px solid #e2e8f0; background:#fff; color:var(--muted);}
  .ext{margin-top:auto; padding:10px 14px; border-top:1px solid #eef2f7; display:flex; align-items:center; gap:8px;}
  .ext a{color:var(--orange); font-weight:700; text-decoration:none;}
  .ext a:hover{text-decoration:underline;}
  .dot{width:8px; height:8px; background:var(--blue-700); border-radius:50%;}
</style>

<div class="news-wrap">
  <h1 class="page-title">News</h1>

  <!-- HERO (backgrounds only) -->
  <div class="hero" aria-label="Featured photos">
    <div class="hero-tile" style="background-image:url('/assets/main_IEE_img.jpg');">
      <span class="hero-overlay" aria-hidden="true"></span>
      <div class="hero-caption">Highlights from recent IEEE activities</div>
    </div>
    <div class="hero-tile" style="background-image:url('/assets/me_IEEE.jpg');">
      <span class="hero-overlay" aria-hidden="true"></span>
      <div class="hero-caption">On site at an IEEE conference</div>
    </div>
  </div>

  <!-- News Cards (no photos inside cards) -->
  <div class="grid">

    <article class="card">
      <div class="thumb" aria-hidden="true"></div>
      <div class="body">
        <a class="title" href="https://ecs.syracuse.edu/about/news/electrical-engineering-and-computer-science-graduate-students-faculty-and-staff-celebrate-diversity-in-computing-and-technology-at-the-tapia-conference" target="_blank" rel="noopener noreferrer">
          Electrical Engineering and Computer Science Graduate Students, Faculty, and Staff Celebrate Diversity at Tapia
        </a>
        <p class="desc">Community, representation, and cutting-edge research at the Tapia Conference.</p>
        <div class="meta">
          <span class="pill">Diversity</span><span class="pill">Conference</span>
        </div>
      </div>
      <div class="ext">
        <span class="dot" aria-hidden="true"></span>
        <a href="https://ecs.syracuse.edu/about/news/electrical-engineering-and-computer-science-graduate-students-faculty-and-staff-celebrate-diversity-in-computing-and-technology-at-the-tapia-conference" target="_blank" rel="noopener noreferrer">Read article</a>
      </div>
    </article>

    <article class="card">
      <div class="thumb" aria-hidden="true"></div>
      <div class="body">
        <a class="title" href="https://ecs.syracuse.edu/about/news/power-up-electrical-engineering-and-computer-science-graduate-student-nathalie-uwamahoro" target="_blank" rel="noopener noreferrer">
          Power Up: Graduate Student Nathalie Uwamahoro
        </a>
        <p class="desc">A feature on research, resilience, and a vision for a flexible, reliable grid.</p>
        <div class="meta">
          <span class="pill">Feature</span><span class="pill">Power Systems</span>
        </div>
      </div>
      <div class="ext">
        <span class="dot" aria-hidden="true"></span>
        <a href="https://ecs.syracuse.edu/about/news/power-up-electrical-engineering-and-computer-science-graduate-student-nathalie-uwamahoro" target="_blank" rel="noopener noreferrer">Read article</a>
      </div>
    </article>

    <article class="card">
      <div class="thumb" aria-hidden="true"></div>
      <div class="body">
        <a class="title" href="https://www.linkedin.com/posts/syracuse-university-college-of-engineering-and-computer-science_congratulations-to-electrical-engineering-activity-7127374479462129664-f_dK" target="_blank" rel="noopener noreferrer">
          North American Power Symposium (NAPS) Award — 2023
        </a>
        <p class="desc">Celebrating recognition at NAPS for contributions to power engineering.</p>
        <div class="meta">
          <span class="pill">Award</span><span class="pill">NAPS</span>
        </div>
      </div>
      <div class="ext">
        <span class="dot" aria-hidden="true"></span>
        <a href="https://www.linkedin.com/posts/syracuse-university-college-of-engineering-and-computer-science_congratulations-to-electrical-engineering-activity-7127374479462129664-f_dK" target="_blank" rel="noopener noreferrer">View post</a>
      </div>
    </article>

  </div>
</div>
