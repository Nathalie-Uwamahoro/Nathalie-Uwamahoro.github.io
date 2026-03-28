---
layout: page
title: "Home"
permalink: /home/
---

<style>
  :root{
    --blue:#0b5fff;
    --green:#137a2a;
    --orange:#ffedd5;
    --orange-border:#fdba74;
    --orange-strong:#f97316;
    --ink:#0f172a;
    --muted:#475569;
    --border:#dbe3ee;
    --card:#ffffff;
  }

  body{
    background: linear-gradient(180deg, #fff7ed 0%, #ffffff 42%);
  }

  .page,
  .page__inner-wrap,
  .page__content{
    margin-top: 0 !important;
    padding-top: 0 !important;
  }

  .home-wrap{
    max-width: 1220px;
    margin: 0 auto;
    padding: 0 10px 10px;
  }

  .page__title,
  h1.page__title{
    font-size: 1.7rem !important;
    line-height: 1.05;
    margin: 0 0 0.5rem !important;
    padding: 0 !important;
    color: var(--ink);
  }

  .home-wrap p,
  .home-wrap li{
    font-size: 14px;
    line-height: 1.45;
    color: var(--ink);
  }

  .home-wrap p{
    margin: 0 0 8px;
  }

  .home-wrap a{
    color: var(--blue);
    text-decoration: none;
  }

  .home-wrap a:hover{
    text-decoration: underline;
  }

  .grid{
    display: grid;
    gap: 12px;
  }

  .top-grid{
    grid-template-columns: 270px 1fr;
    align-items: stretch;
  }

  .bottom-grid{
    grid-template-columns: 1.55fr 1fr;
    align-items: stretch;
  }

  @media (max-width: 980px){
    .top-grid,
    .bottom-grid{
      grid-template-columns: 1fr;
    }
  }

  .card,
  .profile{
    background: rgba(255,255,255,0.96);
    border: 1px solid var(--orange-border);
    border-radius: 16px;
    box-shadow: 0 4px 14px rgba(249,115,22,0.08);
  }

  .card{
    padding: 12px 14px;
  }

  .profile{
    padding: 12px;
    text-align: center;
    display: flex;
    flex-direction: column;
    justify-content: center;
    background: linear-gradient(180deg, #fffaf5 0%, #ffffff 100%);
  }

  .avatar-wrap{
    width: 160px;
    height: 160px;
    margin: 0 auto 10px;
    border-radius: 50%;
    overflow: hidden;
    border: 2px solid #fed7aa;
    background: #fff;
  }

  .avatar{
    width: 100%;
    height: 100%;
    display: block;
    object-fit: cover;
    object-position: center top;
    transform: translateZ(0);
    backface-visibility: hidden;
  }

  .name{
    font-size: 1.22rem;
    font-weight: 800;
    color: var(--ink);
    line-height: 1.15;
    margin: 2px 0 4px;
  }

  .meta{
    color: var(--muted);
    font-size: 13px;
    line-height: 1.3;
    margin: 0;
  }

  .icons{
    display: flex;
    justify-content: center;
    gap: 8px;
    margin-top: 10px;
    flex-wrap: wrap;
  }

  .icon{
    display: inline-flex;
    align-items: center;
    justify-content: center;
    width: 32px;
    height: 32px;
    border-radius: 9px;
    border: 1px solid #fdba74;
    color: var(--orange-strong);
    background: #fff;
    text-decoration: none;
  }

  .icon:hover{
    background: #fff7ed;
    border-color: #fb923c;
  }

  .icon svg{
    width: 16px;
    height: 16px;
  }

  .sect-title{
    font-size: 13px;
    font-weight: 800;
    color: var(--orange-strong);
    margin: 0 0 8px;
    line-height: 1.2;
    letter-spacing: 0.2px;
    text-transform: uppercase;
  }

  .bio-text{
    text-align: left;
  }

  .bio-highlights,
  .compact-list{
    margin: 6px 0 0;
    padding-left: 18px;
  }

  .bio-highlights li,
  .compact-list li{
    margin: 4px 0;
  }

  .tight-list li{
    margin: 3px 0;
  }

  .job-note{
    margin-top: 8px;
    font-weight: 700;
    color: #9a3412;
  }

  .edu-degree{
    font-weight: 700;
  }

  @media (max-width: 640px){
    .home-wrap{
      padding: 0 8px 8px;
    }

    .page__title,
    h1.page__title{
      font-size: 1.5rem !important;
      margin-bottom: 0.4rem !important;
    }

    .avatar-wrap{
      width: 145px;
      height: 145px;
    }

    .card,
    .profile{
      border-radius: 14px;
    }
  }
</style>

<div class="home-wrap">

  <!-- Top row -->
  <div class="grid top-grid">

    <aside class="profile">
      <div class="avatar-wrap">
        <img
          class="avatar"
          src="{{ '/assets/profile.jpg' | relative_url }}"
          alt="Nathalie Uwamahoro"
          loading="eager"
          decoding="async"
        >
      </div>

      <div class="name">Nathalie Uwamahoro</div>
      <p class="meta">Ph.D. Candidate</p>
      <p class="meta">Electrical &amp; Computer Engineering</p>
      <p class="meta">Syracuse University</p>

      <div class="icons" aria-label="Profile links">
        <a class="icon" href="mailto:nuwamaho@syr.edu" aria-label="Email">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor">
            <path d="M4 6h16v12H4z"/>
            <path d="m22 6-10 7L2 6" stroke-width="1.5"/>
          </svg>
        </a>

        <a class="icon" href="https://github.com/Nathalie-Uwamahoro" target="_blank" rel="noopener noreferrer" aria-label="GitHub">
          <svg viewBox="0 0 16 16" fill="currentColor">
            <path d="M8 0a8 8 0 0 0-2.53 15.6c.4.07.55-.17.55-.39v-1.35c-2.24.49-2.71-1.08-2.71-1.08-.36-.91-.88-1.15-.88-1.15-.72-.49.05-.48.05-.48.8.06 1.22.83 1.22.83.71 1.21 1.86.86 2.31.66.07-.52.28-.86.5-1.06-1.79-.2-3.68-.9-3.68-3.98 0-.88.31-1.6.83-2.17-.08-.2-.36-1.02.08-2.13 0 0 .67-.21 2.2.83a7.6 7.6 0 0 1 4 0c1.53-1.04 2.2-.83 2.2-.83.44 1.11.16 1.93.08 2.13.52.57.83 1.29.83 2.17 0 3.09-1.89 3.78-3.69 3.98.29.25.54.74.54 1.49v2.21c0 .22.15.47.55.39A8 8 0 0 0 8 0z"/>
          </svg>
        </a>

        <a class="icon" href="https://www.linkedin.com/in/nathalie-uwamahoro" target="_blank" rel="noopener noreferrer" aria-label="LinkedIn">
          <svg viewBox="0 0 24 24" fill="currentColor">
            <path d="M4.98 3.5a2.5 2.5 0 1 1 0 5.001 2.5 2.5 0 0 1 0-5zM3 9h4v12H3zM14.5 9A4.5 4.5 0 0 1 19 13.5V21h-4v-6a2 2 0 1 0-4 0v6H7V9h4v1.7A4.9 4.9 0 0 1 14.5 9z"/>
          </svg>
        </a>

        <a class="icon" href="{{ '/assets/cv.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="CV">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor">
            <path d="M6 2h7l5 5v15H6z" stroke-width="1.5"/>
            <path d="M13 2v6h6" stroke-width="1.5"/>
          </svg>
        </a>
      </div>
    </aside>

    <section class="card">
      <h2 class="sect-title">Biography</h2>

   <div class="bio-text">
  <p>
    I am a final-year Ph.D. candidate in <strong>Electrical &amp; Computer Engineering</strong> at <strong>Syracuse University</strong>, advised by
    <a href="https://ecs.syracuse.edu/faculty-staff/sara-eftekharnejad" target="_blank" rel="noopener noreferrer"><strong>Dr. Sara Eftekharnejad</strong></a>
    in the
    <a href="https://seftekha.expressions.syr.edu/" target="_blank" rel="noopener noreferrer"><strong>Smart Grid Research Lab</strong></a>.
  </p>

  <p>
    My research focuses on developing robust methods to assess and improve the <strong>reliability</strong> and <strong>resilience</strong> of modern <strong>power systems</strong> under both <strong>normal</strong> and <strong>contingency operating conditions</strong>. In particular, my work addresses:
  </p>

  <ul class="bio-highlights tight-list">
    <li><strong>Dynamic assessment</strong> of power grid failures and <strong>cascading outage behavior</strong></li>
    <li><strong>Modeling failure interdependencies</strong> among grid components and <strong>cyber-physical interactions</strong> in modern power systems</li>
    <li><strong>Analysis of generation and load uncertainty</strong> in grid operation and planning</li>
  </ul>

  <p>
    I have developed experience in <strong>electric transmission and distribution systems</strong>, <strong>NERC reliability standards</strong>, <strong>DC microgrid modeling</strong>, and <strong>data-driven analysis</strong> through work at <strong>Pacific Gas and Electric Company (PG&amp;E)</strong>, <strong>Hitachi R&amp;D</strong>, and the <strong>National Institute of Statistics of Rwanda</strong>.
  </p>

  <p class="job-note">
    <strong>Actively seeking full-time opportunities in power systems engineering, grid modeling, and machine learning.</strong>
  </p>
</div>
    </section>

  </div>

  <!-- Bottom row -->
  <div class="grid bottom-grid" style="margin-top:12px;">

    <section class="card">
      <h2 class="sect-title">Selected Awards &amp; Achievements</h2>
      <ul class="compact-list tight-list">
        <li>Represented PG&amp;E Transmission &amp; Distribution at the IEEE PES General Meeting 2025, Austin, TX.</li>
        <li> 38th Outstanding Teaching Award, recognized for excellence in teaching and student mentorship, ECE Department, Syracuse University (2025)</li>
        <li>Women in Science and Engineering Future Professional Program, Syracuse University, 2025.</li>
        <li><strong>First Place, Best Graduate Paper</strong>, North American Power Symposium (NAPS), 2023.</li>
        <li>Teaching Mentor for new Teaching Assistants, Syracuse University, 2024–2025.</li>
        <li>Professional internship, Hitachi R&amp;D, Tokyo, Japan, 2019.</li>
        <li>Selected by CMU-Africa to complete the final semester at CMU Pittsburgh, 2019.</li>
      </ul>
    </section>

    <section class="card">
      <h2 class="sect-title">Education</h2>
      <ul class="compact-list tight-list">
        <li><span class="edu-degree">Ph.D., Electrical &amp; Computer Engineering</span><br>Syracuse University, Aug, 2026 (Expected)</li>
        <li><span class="edu-degree">M.Sc., Electrical &amp; Computer Engineering</span><br>Carnegie Mellon University, 2019</li>
        <li><span class="edu-degree">B.Sc., Electrical Engineering</span><br>University of Rwanda, 2017</li>
      </ul>
    </section>

  </div>
</div>