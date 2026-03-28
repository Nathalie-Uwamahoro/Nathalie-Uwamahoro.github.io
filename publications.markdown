---
layout: default
title: "Publications"
permalink: /publications/
---

<style>
  :root{
    --orange-bg:#fff7ed;
    --orange-light:#ffedd5;
    --orange-border:#fdba74;
    --orange-strong:#ea580c;
    --orange-deep:#c2410c;
    --ink:#0f172a;
    --muted:#475569;
    --card:#ffffff;
  }

  body{
    background: linear-gradient(180deg, var(--orange-bg) 0%, #ffffff 45%);
  }

  .page,
  .page__inner-wrap,
  .page__content{
    margin-top: 0 !important;
    padding-top: 0 !important;
  }

  .page__title,
  h1.page__title{
    font-size: 1.7rem !important;
    line-height: 1.08;
    margin: 0 0 0.7rem !important;
    color: var(--ink);
  }

  .pub-wrap{
    max-width: 980px;
    margin: 0 auto;
    padding: 0 10px 18px;
  }

  .pub-card{
    background: rgba(255,255,255,0.97);
    border: 1px solid var(--orange-border);
    border-radius: 16px;
    box-shadow: 0 4px 14px rgba(234,88,12,0.08);
    padding: 18px 20px;
    margin-bottom: 14px;
  }

  .section-title{
    font-size: 1.05rem;
    font-weight: 800;
    color: var(--orange-strong);
    margin: 0 0 12px;
  }

  .pub-list{
    list-style: none;
    padding: 0;
    margin: 0;
  }

  .pub-item{
    padding: 0 0 14px;
    margin: 0 0 14px;
    border-bottom: 1px solid var(--orange-light);
  }

  .pub-item:last-child{
    border-bottom: none;
    margin-bottom: 0;
    padding-bottom: 0;
  }

  .pub-citation{
    font-size: 15px;
    line-height: 1.6;
    color: var(--ink);
    margin: 0 0 10px;
  }

  .pub-citation strong{
    color: var(--ink);
  }

  .pub-actions{
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
  }

  .pub-btn,
  .pub-badge{
    display: inline-block;
    padding: 8px 12px;
    border-radius: 10px;
    font-size: 13px;
    font-weight: 700;
    text-decoration: none !important;
  }

  .pub-btn{
    background: var(--orange-strong);
    color: #fff !important;
    border: 1px solid var(--orange-strong);
  }

  .pub-btn:hover{
    background: var(--orange-deep);
    border-color: var(--orange-deep);
  }

  .pub-badge{
    background: #fff7ed;
    color: var(--orange-deep);
    border: 1px solid var(--orange-border);
  }

  .note{
    color: var(--muted);
    font-size: 14px;
    line-height: 1.5;
    margin: 0;
  }

  @media (max-width: 768px){
    .page__title,
    h1.page__title{
      font-size: 1.5rem !important;
    }

    .pub-wrap{
      padding: 0 8px 14px;
    }

    .pub-card{
      padding: 14px;
    }
  }
</style>

<div class="pub-wrap">

  <section class="pub-card">
    <p class="note">
      This page lists selected publications and posters. Download links are included where available.
    </p>
  </section>

  <section class="pub-card">
    <h2 class="section-title">Published Papers</h2>

    <ul class="pub-list">
      <li class="pub-item">
        <p class="pub-citation">
          <strong>N. Uwamahoro</strong> and S. Eftekharnejad,
          “A Comparative Study of Data-Driven Power Grid Cascading Failure Prediction Methods,”
          <em>2023 North American Power Symposium (NAPS)</em>, pp. 1–6, IEEE, 2023.
        </p>
        <div class="pub-actions">
          <a class="pub-btn" href="https://ieeexplore-ieee-org.libezproxy2.syr.edu/document/10318537" target="_blank" rel="noopener noreferrer">
            View / Download Publication
          </a>
        </div>
      </li>

      <li class="pub-item">
        <p class="pub-citation">
          <strong>N. Uwamahoro</strong> and S. Eftekharnejad,
          “Dynamic Community Detection from Temporal Sequences of Cascading Failures in Power Grids,”
          <em>2025 57th North American Power Symposium (NAPS)</em>, Storrs, CT, USA, pp. 1–6, IEEE Xplore, 2025.
        </p>
        <div class="pub-actions">
          <a class="pub-btn" href="https://ieeexplore-ieee-org.libezproxy2.syr.edu/document/11272425" target="_blank" rel="noopener noreferrer">
            View / Download Publication
          </a>
        </div>
      </li>

      <li class="pub-item">
        <p class="pub-citation">
          <strong>N. Uwamahoro</strong> and S. Eftekharnejad,
          “The Impact of Large Data Center Load Uncertainties on Power Grid Reliability,”
          <em>IEEE PES General Meeting (GM)</em>, 2026.
          <strong>(Accepted)</strong>
        </p>
        <div class="pub-actions">
          <span class="pub-badge">Accepted Paper</span>
        </div>
      </li>
    </ul>
  </section>

  <section class="pub-card">
    <h2 class="section-title">Posters and Presentations</h2>

    <ul class="pub-list">
      <li class="pub-item">
        <p class="pub-citation">
          <strong>N. Uwamahoro</strong> and S. Eftekharnejad,
          <em>Community Detection in Power Grids with Graph-Based Methods with Cascading Failure Data</em> (Poster),
          North American Power Symposium, Asheville, NC, USA, October 2023.
        </p>
      </li>

      <li class="pub-item">
        <p class="pub-citation">
          <strong>N. Uwamahoro</strong> and S. Eftekharnejad,
          <em>Predicting Power Grid Cascading Failures with Data-Driven Methods</em> (Poster),
          Syracuse University Electrical and Computer Science Research Day, Syracuse, NY, USA, March 2023.
        </p>
      </li>

      <li class="pub-item">
        <p class="pub-citation">
          <strong>N. Uwamahoro</strong>, H. T. Gebrekidan, and S. Eftekharnejad,
          <em>A Novel Metric for Power Grid Flexibility Considering Uncertainty from Renewable Energy Sources</em> (Poster),
          Syracuse University Electrical and Computer Science Research Day, Syracuse, NY, USA, March 2023.
        </p>
      </li>

      <li class="pub-item">
        <p class="pub-citation">
          <strong>N. Uwamahoro</strong>, P. McSharry, Y. Mburu, M. Busogi, I. Coffie, E. Kuffuor, L. Kabarere, and H. Tembine,
          <em>A Relationship Between Stringency Index and COVID-19 Confirmed Cases in East Africa</em> (Poster),
          First Rwanda Science, Technology and Innovation (STI) Conference, Kigali, Rwanda, March 2022.
        </p>
      </li>
    </ul>
  </section>

</div>