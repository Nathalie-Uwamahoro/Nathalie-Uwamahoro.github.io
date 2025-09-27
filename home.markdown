---
layout: page
title: "Home"
permalink: /home/
---

<style>
  :root{
    --blue:#0b5fff; --orange:#ff7a18; --ink:#0f172a; --muted:#475569;
    --border:#e2e8f0; --card:#ffffff;
  }
  .home-wrap{max-width:1100px;margin:0 auto;padding:8px 12px;}

  /* Compact typography */
  .home-wrap p{margin:0 0 6px; line-height:1.45; font-size:15px;}
  .home-wrap ul{margin:6px 0 0; padding-left:18px; font-size:15px;}
  .home-wrap li{margin:4px 0;}
  .sect-title{font-size:18px; font-weight:800; color:#137a2a; text-align:center; margin:0 0 8px;}

  /* Grid */
  .row{display:grid; gap:10px;}
  .row.top{grid-template-columns: 300px 1fr; align-items:start;}
  .row.bottom{grid-template-columns: 1fr 1fr;}
  @media (max-width: 900px){
    .row.top, .row.bottom{grid-template-columns:1fr;}
  }

  /* Profile */
  .profile{
    background:var(--card); border:1px solid var(--border); border-radius:14px;
    padding:12px; text-align:center;
  }
  .avatar{width:120px;height:120px;border-radius:50%;object-fit:cover;display:block;margin:0 auto 8px;}
  .name{font-size:20px;font-weight:800;color:var(--ink);margin:2px 0;}
  .meta{color:var(--muted); font-size:13px; margin:0;}
  .icons{display:flex;justify-content:center;gap:8px;margin-top:8px;}
  .icon{display:inline-flex;align-items:center;justify-content:center;
        width:30px;height:30px;border-radius:8px;border:1px solid var(--border);
        color:#0a4ed9;text-decoration:none;}
  .icon svg{width:16px;height:16px;}

  /* Cards */
  .card{
    background:#fff;border:1px solid var(--border);border-radius:14px;
    padding:10px 12px;
  }

  /* Biography single-column paragraph */
  .bio-text{
    text-align:justify;
    hyphens:auto;
  }
</style>

<div class="home-wrap">

  <!-- ROW 1: Profile + Biography -->
  <div class="row top">

    <!-- Profile -->
    <aside class="profile">
      <img class="avatar" src="/assets/profile.jpg" alt="Nathalie Uwamahoro">
      <div class="name">Nathalie Uwamahoro</div>
      <p class="meta">PhD Candidate</p>
      <p class="meta">Syracuse University</p>
      <div class="icons" aria-label="Profile links">
        <a class="icon" href="mailto:nuwamaho@syr.edu" aria-label="Email">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor"><path d="M4 6h16v12H4z"/><path d="m22 6-10 7L2 6" stroke-width="1.5"/></svg>
        </a>
        <a class="icon" href="https://github.com/Nathalie-Uwamahoro" target="_blank" rel="noopener noreferrer" aria-label="GitHub">
          <svg viewBox="0 0 16 16" fill="currentColor"><path d="M8 0a8 8 0 0 0-2.53 15.6c.4.07.55-.17.55-.39v-1.35c-2.24.49-2.71-1.08-2.71-1.08-.36-.91-.88-1.15-.88-1.15-.72-.49.05-.48.05-.48.8.06 1.22.83 1.22.83.71 1.21 1.86.86 2.31.66.07-.52.28-.86.5-1.06-1.79-.2-3.68-.9-3.68-3.98 0-.88.31-1.6.83-2.17-.08-.2-.36-1.02.08-2.13 0 0 .67-.21 2.2.83a7.6 7.6 0 0 1 4 0c1.53-1.04 2.2-.83 2.2-.83.44 1.11.16 1.93.08 2.13.52.57.83 1.29.83 2.17 0 3.09-1.89 3.78-3.69 3.98.29.25.54.74.54 1.49v2.21c0 .22.15.47.55.39A8 8 0 0 0 8 0z"/></svg>
        </a>
        <a class="icon" href="https://www.linkedin.com/in/nathalie-uwamahoro" target="_blank" rel="noopener noreferrer" aria-label="LinkedIn">
          <svg viewBox="0 0 24 24" fill="currentColor"><path d="M4.98 3.5a2.5 2.5 0 1 1 0 5.001 2.5 2.5 0 0 1 0-5zM3 9h4v12H3zM14.5 9A4.5 4.5 0 0 1 19 13.5V21h-4v-6a2 2 0 1 0-4 0v6H7V9h4v1.7A4.9 4.9 0 0 1 14.5 9z"/></svg>
        </a>
        <a class="icon" href="/assets/cv.pdf" target="_blank" rel="noopener noreferrer" aria-label="CV">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor"><path d="M6 2h7l5 5v15H6z" stroke-width="1.5"/><path d="M13 2v6h6" stroke-width="1.5"/></svg>
        </a>
      </div>
    </aside>

    <!-- Biography (single-column paragraph, no em dash) -->
    <section class="card">
      <h2 class="sect-title">Biography</h2>
      <p class="bio-text">
        I am a 4th-year Ph.D. candidate in Electrical &amp; Computer Engineering at Syracuse University,
        advised by <a href="https://ecs.syracuse.edu/faculty-staff/sara-eftekharnejad" target="_blank" rel="noopener noreferrer">Dr. Sara Eftekharnejad</a> in the
        <a href="https://seftekha.expressions.syr.edu/" target="_blank" rel="noopener noreferrer">Smart Grid Research Lab</a>.
        In Summer 2025, I interned with PG&amp;E Electric Transmission &amp; Distribution, reporting to
        <a href="https://www.linkedin.com/in/shbahramirad" target="_blank" rel="noopener noreferrer">Dr. Shay Bahramirad</a>.
        I supported grid strategy and resilience planning, performed load-flow studies for distribution expansion, and
        built a Python cloud workflow for causal inference on underground-cable outage data, reducing report cycle time by 40%
        and producing ranked CapEx priorities for cable replacement. My research focuses on modernizing the power grid, improving
        flexibility, reliability, and resilience under uncertainties such as data-center growth and variable renewables.
        <strong>I’m seeking a Summer 2026 Ph.D.-level internship in Energy Systems, Data Science, or Machine Learning, and I welcome research collaborations.</strong>
      </p>
    </section>
  </div>

  <!-- ROW 2: Awards + (Interests & Education) side-by-side -->
  <div class="row bottom" style="margin-top:10px;">

    <!-- Awards -->
    <section class="card">
      <h2 class="sect-title">Selected Awards &amp; Achievements</h2>
      <ul>
      <li>Represented PG&amp;E Transmission &amp; Distribution at the IEEE PES General Meeting 2025, Austin, TX (fully sponsored).</li>
       <li>Women in Science and Engineering — Future Professional Program (WiSE-FPP) 2025, Syracuse University.</li>
        <li><strong>First Place, Best Graduate Paper</strong> — North American Power Symposium (NAPS) 2023.
          <br><em>“A Comparative Study of Data-Driven Power Grid Cascading Failure Prediction Methods…”</em>
        </li>
        <li>Teaching Mentor for new Teaching Assistants, Syracuse University (2024–2025).</li>
        <li>Professional internship, Hitachi R&amp;D, Tokyo, Japan (2019).</li>
        <li>Selected by CMU-Africa to complete final semester at CMU Pittsburgh, USA (2019).</li>
      </ul>
    </section>

    <!-- Interests + Education -->
    <section class="card">
      <div style="display:grid;grid-template-columns:1fr 1fr;gap:12px;">
        <div>
          <h2 class="sect-title">Interests</h2>
          <ul>
            <li>Power system flexibility &amp; resilience</li>
            <li>Renewable energy &amp; uncertainty modeling</li>
            <li>Smart cities &amp; resource allocation optimization</li>
            <li>Machine learning &amp; topological data analysis</li>
          </ul>
        </div>
        <div>
          <h2 class="sect-title">Education</h2>
          <ul>
            <li><strong>Ph.D., Electrical &amp; Computer Engineering</strong>, Syracuse University (Present)</li>
            <li><strong>M.Sc., Electrical &amp; Computer Engineering</strong>, Carnegie Mellon University (2019)</li>
            <li><strong>B.Sc., Electrical Engineering</strong>, University of Rwanda (2017)</li>
          </ul>
        </div>
      </div>
    </section>

  </div>
</div>
