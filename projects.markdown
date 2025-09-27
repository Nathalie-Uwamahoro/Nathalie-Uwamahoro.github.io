---
layout: default
title: "Projects"
permalink: /projects/
---

<style>
  :root{
    --blue:#0b5fff;       /* primary */
    --blue-700:#0a4ed9;
    --orange:#ff7a18;     /* accent */
    --ink:#0f172a;        /* text */
    --muted:#475569;      /* secondary text */
    --bg:#ffffff;
    --card:#f8fafc;
    --ring: rgba(11,95,255,.25);
  }
  .projects-wrap{
    max-width: 1100px; margin: 24px auto; padding: 0 16px;
  }
  .page-title{
    font-size: 34px; line-height: 1.2; margin: 6px 0 18px; text-align: center;
    color: var(--blue);
  }
  .subtitle{
    text-align:center; color: var(--muted); margin-bottom: 24px;
  }
  .grid{
    display:grid; gap:16px;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  }
  details.project{
    background: var(--card);
    border: 1px solid #e2e8f0;
    border-radius: 14px;
    padding: 10px 12px;
    transition: box-shadow .2s ease, transform .05s ease;
  }
  details.project[open]{ box-shadow: 0 8px 24px rgba(2,6,23,.08); }
  details.project:focus-within{ outline: 2px solid var(--ring); }

  summary.project-title{
    display:flex; align-items:center; gap:10px; outline:none; border:none; cursor:pointer;
  }
  .badge{
    background: linear-gradient(135deg, var(--blue), var(--orange));
    color: white; font-size: 11px; padding: 3px 8px; border-radius: 999px;
  }
  .name{
    font-weight: 700; color: var(--ink);
    font-size: 18px; line-height:1.3;
  }
  .chev{
    margin-left:auto; transition: transform .2s ease; color: var(--blue-700);
  }
  details[open] .chev{ transform: rotate(90deg); }

  .meta{
    margin: 8px 0 0; color: var(--muted); font-size: 13px;
  }
  .content{
    margin-top: 10px; padding-top: 10px; border-top: 1px dashed #e2e8f0;
    color:#0f172a; font-size:15px; line-height:1.6;
  }
  .section-title{
    color: var(--blue-700); font-weight: 700; margin: 8px 0 6px; font-size: 15px;
  }
  .pill{
    display:inline-block; padding:2px 8px; border-radius:999px; font-size:12px;
    background: #fff; border:1px solid #e2e8f0; color: var(--muted); margin-right:6px;
  }
</style>

<div class="projects-wrap">
  <h1 class="page-title">Projects</h1>
  <p class="subtitle">Click a project name to read more</p>

  <div class="grid">

    <!-- Project 1 -->
    <details class="project" id="proj-cascade">
      <summary class="project-title">
        <span class="badge">Power Systems</span>
        <span class="name">Project 1: A Comparative Study of Data-Driven Power Grid Cascading Failure Prediction Methods</span>
        <span class="chev" aria-hidden="true">▸</span>
      </summary>
      <div class="meta">
        <span class="pill">Binary classification</span>
        <span class="pill">IEEE 30-bus</span>
        <span class="pill">Reliability</span>
      </div>
      <div class="content">
        <div class="section-title">Abstract</div>
        <p>
          Cascading failures in power grids, where failures propagate from one component to another, are a major cause of large-scale blackouts. With renewed interest in enhancing power grid resilience, predicting cascading failures has become crucial for implementing effective mitigation strategies.
        </p>
        <p>
          Existing cascading failure prediction methods often struggle with accuracy, computation time, and dataset imbalances. In this study, we conduct a comparative analysis of various data-driven methods for failure prediction that offer shorter computation times and improved predictive accuracy.
        </p>
        <p>
          The problem is formulated as a binary classification task, where input features (such as transmission line loading levels) are mapped to their failure status. To validate our approach, we apply the proposed methods to the IEEE 30-bus system, demonstrating their viability in power grid failure prediction.
        </p>
        <p>
          This study provides insights into developing fast and accurate data-driven cascading failure models, aiding future research on power system reliability and outage classification.
        </p>

        <div class="section-title">Publication</div>
        <p>
          Uwamahoro, Nathalie, and Sara Eftekharnejad.<br>
          “A Comparative Study of Data-Driven Power Grid Cascading Failure Prediction Methods.”<br>
          In 2023 North American Power Symposium (NAPS), IEEE, 2023.
        </p>
      </div>
    </details>

    <!-- Project 2 -->
    <details class="project" id="proj-community">
      <summary class="project-title">
        <span class="badge">Graph Analytics</span>
        <span class="name">Project 2: Community Detection in the Power System</span>
        <span class="chev" aria-hidden="true">▸</span>
      </summary>
      <div class="meta">
        <span class="pill">Cascading data</span>
        <span class="pill">IEEE 30-bus</span>
        <span class="pill">Illinois 200-bus</span>
      </div>
      <div class="content">
        <div class="section-title">Abstract</div>
        <p>
          Modern power grids are highly interconnected, making them vulnerable to cascading failures when a single component fails. Accurately modeling these failures is critical for grid reliability, but understanding complex dependencies among grid components remains a challenge.
        </p>
        <p>
          This study introduces a clustering-based community detection method that identifies vulnerable transmission lines using conditional failure probabilities. By classifying components into vulnerable and non-vulnerable categories, this approach enhances grid monitoring, reduces operational costs, and mitigates fault propagation.
        </p>
        <p>
          The proposed methodology is applied to the IEEE 30-bus and Illinois 200-bus systems using simulated cascading failure data. We utilize a graph-based community detection algorithm on an interaction matrix derived from historical or simulated failure data. In this model:
        </p>
        <ul>
          <li>Transmission lines are treated as graph vertices.</li>
          <li>Edge weights represent conditional failure probabilities.</li>
          <li>A threshold-based clustering strategy classifies lines into failure risk categories.</li>
        </ul>
        <p>
          A sensitivity analysis is conducted to evaluate the robustness of this method under different probability thresholds. Results indicate that historical cascade data effectively clusters transmission lines, pinpointing vulnerable areas. However, increasing the failure probability threshold reduces the number of identified vulnerable lines while increasing non-vulnerable classifications.
        </p>
        <p>
          Future work aims to integrate cluster status as a predictive variable in cascading failure models and develop real-time monitoring strategies for enhancing grid resilience.
        </p>

        <div class="section-title">Poster Presentation</div>
        <p>
          Uwamahoro Nathalie, Sara Eftekharnejad.<br>
          “Community Detection in Power Grids with Graph-based Methods Using Cascading Failure Data.”<br>
          Presented at: North American Power Symposium (NAPS), Asheville, NC, US. October 2023.
        </p>
      </div>
    </details>

    <!-- Project 3 -->
    <details class="project" id="proj-battery">
      <summary class="project-title">
        <span class="badge">Energy Storage</span>
        <span class="name">Project 3: A Feasibility Study of Li-Ion Battery Refurbishment</span>
        <span class="chev" aria-hidden="true">▸</span>
      </summary>
      <div class="meta">
        <span class="pill">EIS</span>
        <span class="pill">Internal impedance</span>
        <span class="pill">Second life</span>
      </div>
      <div class="content">
        <div class="section-title">Abstract</div>
        <p>
          The demand for Li-ion batteries is increasing due to the transition toward a low-carbon future across various sectors. Electric vehicles, including electric motorbikes in East Africa, heavily rely on Li-ion battery packs. Additionally, electronic devices worldwide contribute to a significant increase in Li-ion battery waste each year.
        </p>
        <p>
          Understanding the key parameters of battery packs is crucial for predicting performance degradation and ensuring safe and efficient second-life applications. This study investigates the internal resistance variations of battery cells, which impact battery pack longevity and safety. Over time, cell-to-cell voltage deviations become apparent, leading to reduced efficiency and safety concerns. Analyzing these deviations enables effective refurbishment strategies.
        </p>
        <p>
          Refurbishing Li-ion battery packs offers a sustainable solution to reducing battery waste. However, research into the characteristics of post-first-use Li-ion cells remains limited. This study identifies and analyzes the critical characteristics necessary for battery refurbishment, with a focus on:
        </p>
        <ul>
          <li>Conducting a literature review to assess the current state of Li-ion battery technologies.</li>
          <li>Identifying essential cell characteristics for effective refurbishment.</li>
          <li>Analyzing internal impedance using electrochemical impedance spectroscopy (EIS) to evaluate cell viability.</li>
        </ul>

        <div class="section-title">Project Report</div>
        <p>
          A Feasibility Study of Li-Ion Battery Refurbishment<br>
          18980-RW-M.S. GRADUATE PROJECT REPORT, Carnegie Mellon University - Africa Campus
        </p>
      </div>
    </details>

  </div>
</div>
