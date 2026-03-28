---
layout: default
title: "CV"
permalink: /cv/
---

<style>
  :root{
    --orange-bg: #fff7ed;
    --orange-light: #ffedd5;
    --orange-border: #fdba74;
    --orange-strong: #ea580c;
    --orange-soft: #fffaf5;
    --ink: #0f172a;
    --muted: #475569;
    --card: #ffffff;
  }

  body{
    background: linear-gradient(180deg, var(--orange-bg) 0%, #ffffff 42%);
  }

  .page,
  .page__inner-wrap,
  .page__content{
    margin-top: 0 !important;
    padding-top: 0 !important;
  }

  .page__title,
  h1.page__title{
    font-size: 1.65rem !important;
    line-height: 1.08;
    margin: 0 0 0.6rem !important;
    color: var(--ink);
  }

  .cv-wrap{
    max-width: 1080px;
    margin: 0 auto;
    padding: 0 10px 18px;
  }

  .cv-top,
  .cv-card{
    background: rgba(255,255,255,0.97);
    border: 1px solid var(--orange-border);
    border-radius: 16px;
    box-shadow: 0 4px 14px rgba(234, 88, 12, 0.08);
  }

  .cv-top{
    padding: 16px 18px;
    margin-bottom: 14px;
  }

  .cv-top p{
    margin: 0 0 10px;
    font-size: 15px;
    line-height: 1.5;
    color: var(--ink);
  }

  .cv-actions{
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    align-items: center;
  }

  .cv-btn{
    display: inline-block;
    padding: 10px 16px;
    border-radius: 10px;
    background: var(--orange-strong);
    color: #ffffff !important;
    text-decoration: none !important;
    font-weight: 700;
    font-size: 14px;
    border: 1px solid var(--orange-strong);
    transition: 0.2s ease;
  }

  .cv-btn:hover{
    background: #c2410c;
    border-color: #c2410c;
  }

  .cv-card{
    padding: 18px 20px;
  }

  .cv-header{
    border-bottom: 2px solid var(--orange-light);
    padding-bottom: 12px;
    margin-bottom: 16px;
  }

  .cv-name{
    font-size: 1.7rem;
    font-weight: 800;
    color: var(--ink);
    line-height: 1.1;
    margin: 0 0 6px;
  }

  .cv-contact{
    font-size: 14px;
    color: var(--muted);
    line-height: 1.5;
  }

  .cv-contact a{
    color: var(--orange-strong);
    text-decoration: none;
  }

  .cv-contact a:hover{
    text-decoration: underline;
  }

  .cv-section{
    margin-bottom: 18px;
  }

  .cv-section-title{
    font-size: 13px;
    font-weight: 800;
    text-transform: uppercase;
    letter-spacing: 0.4px;
    color: var(--orange-strong);
    margin: 0 0 10px;
  }

  .cv-entry{
    margin-bottom: 14px;
  }

  .cv-entry:last-child{
    margin-bottom: 0;
  }

  .cv-entry-head{
    display: flex;
    justify-content: space-between;
    gap: 12px;
    align-items: baseline;
    flex-wrap: wrap;
    margin-bottom: 2px;
  }

  .cv-role,
  .cv-degree{
    font-weight: 700;
    color: var(--ink);
    font-size: 15px;
  }

  .cv-org{
    color: var(--muted);
    font-style: italic;
    font-size: 14px;
    margin-bottom: 4px;
  }

  .cv-date{
    color: var(--muted);
    font-size: 13px;
    white-space: nowrap;
  }

  .cv-list{
    margin: 6px 0 0;
    padding-left: 18px;
  }

  .cv-list li{
    margin: 4px 0;
    color: var(--ink);
    font-size: 14px;
    line-height: 1.45;
  }

  .skills-grid{
    display: grid;
    gap: 8px;
  }

  .skill-line{
    font-size: 14px;
    line-height: 1.5;
    color: var(--ink);
  }

  .skill-line strong{
    color: var(--ink);
  }

  .two-col{
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 16px;
  }

  @media (max-width: 900px){
    .two-col{
      grid-template-columns: 1fr;
    }
  }

  @media (max-width: 768px){
    .page__title,
    h1.page__title{
      font-size: 1.45rem !important;
    }

    .cv-wrap{
      padding: 0 8px 14px;
    }

    .cv-top,
    .cv-card{
      padding: 14px;
    }

    .cv-name{
      font-size: 1.45rem;
    }
  }
</style>

<div class="cv-wrap">

  <section class="cv-top">
    <p>You can download my Resume using the button below</p>
    <div class="cv-actions">
      <a class="cv-btn" href="{{ '/assets/cv.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer">
        Download CV (PDF)
      </a>
    </div>
  </section>

  <section class="cv-card">
    <div class="cv-header">
      <div class="cv-name">Nathalie Uwamahoro</div>
      <div class="cv-contact">
        Syracuse, NY 13210, USA<br>
        Email: <a href="mailto:nuwamaho@syr.edu">nuwamaho@syr.edu</a><br>
        Website:
        <a href="https://nathalie-uwamahoro.github.io/" target="_blank" rel="noopener noreferrer">
          nathalie-uwamahoro.github.io
        </a>
      </div>
    </div>

    <section class="cv-section">
      <h2 class="cv-section-title">Education</h2>

      <div class="cv-entry">
        <div class="cv-entry-head">
          <div class="cv-degree">Ph.D., Electrical and Computer Engineering (Power Systems)</div>
          <div class="cv-date">Aug 2022 – Aug 2026 (Expected)</div>
        </div>
        <div class="cv-org">Syracuse University, Syracuse, NY, USA</div>
        <div class="skill-line">Advisor: Dr. Sara Eftekharnejad</div>
      </div>

      <div class="cv-entry">
        <div class="cv-entry-head">
          <div class="cv-degree">M.S., Electrical and Computer Engineering (Energy Systems) &amp; Applied Machine Learning</div>
          <div class="cv-date">Jul 2018 – Dec 2019</div>
        </div>
        <div class="cv-org">Carnegie Mellon University, Pittsburgh, PA, USA</div>
      </div>

      <div class="cv-entry">
        <div class="cv-entry-head">
          <div class="cv-degree">B.S., Electrical Engineering, Second Class Honors Upper Division</div>
          <div class="cv-date">Jul 2013 – May 2017</div>
        </div>
        <div class="cv-org">University of Rwanda, Kigali, Rwanda</div>
      </div>
    </section>

    <section class="cv-section">
      <h2 class="cv-section-title">Skills</h2>
      <div class="skills-grid">
        <div class="skill-line"><strong>Tools:</strong> PSSE, DigSilent PowerFactory, TSAT, VSAT, PSAT, PowerWorld Simulator, PSIM, PandaPower, ANDES, HOMER, MATPOWER, MATLAB, Python, Java</div>
        <div class="skill-line"><strong>Toolkit:</strong> Git, MySQL, NetworkX, PyTorch, NumPy, SciPy, scikit-learn, OpenCV, Giotto-TDA, Linux</div>
        <div class="skill-line"><strong>Languages:</strong> English (Fluent), French (Intermediate)</div>
      </div>
    </section>

    <section class="cv-section">
      <h2 class="cv-section-title">Work Experience</h2>

      <div class="cv-entry">
        <div class="cv-entry-head">
          <div class="cv-role">Electric Transmission &amp; Distribution Engineering Ph.D. Intern</div>
          <div class="cv-date">May 2025 – Aug 2025</div>
        </div>
        <div class="cv-org">Pacific Gas and Electric Company (PG&amp;E), San Francisco, CA, USA</div>
        <ul class="cv-list">
          <li>Shadowed the Vice President of Electric Transmission &amp; Distribution, gaining executive-level exposure to grid modernization strategy, system resilience planning, and T&amp;D operational priorities.</li>
          <li>Conducted AC power-flow and load-growth studies to assess feeder hosting capacity, identify thermal overloads and voltage violations, and recommend reinforcement measures to improve grid reliability.</li>
          <li>Automated root-cause analysis of underground cable failures by applying causal inference techniques to historical fault and asset condition data, reducing reporting cycle time by 40%.</li>
          <li>Authored an executive technical report on grid resilience, large-load interconnection impacts, and Advanced Distribution Management System (ADMS) architectures.</li>
          <li>Contributed to daily, weekly, and monthly reliability review meetings.</li>
          <li>Represented PG&amp;E Transmission &amp; Distribution at the IEEE PES General Meeting 2025 and synthesized technical findings for the T&amp;D team.</li>
        </ul>
      </div>

      <div class="cv-entry">
        <div class="cv-entry-head">
          <div class="cv-role">Data Scientist Team Leader</div>
          <div class="cv-date">Jul 2021 – Jul 2022</div>
        </div>
        <div class="cv-org">National Institute of Statistics of Rwanda, Kigali, Rwanda</div>
        <ul class="cv-list">
          <li>Engineered and deployed Python-based ETL pipelines to ingest and analyze web-scraped economic data, reducing processing time by 20%.</li>
          <li>Developed scalable workflows to disseminate socio-economic indicators, reducing nationwide reporting time by 15%.</li>
          <li>Led a cross-functional team of 5+ data scientists using Agile methodology to deliver large-scale national data initiatives.</li>
        </ul>
      </div>

      <div class="cv-entry">
        <div class="cv-entry-head">
          <div class="cv-role">Research Assistant</div>
          <div class="cv-date">Jun 2021 – Aug 2022</div>
        </div>
        <div class="cv-org">Carnegie Mellon University, Kigali, Rwanda</div>
        <ul class="cv-list">
          <li>Developed a data-driven analysis framework in Python using Chi-Square tests, Extra Trees Classifier, and regression models to assess the socio-economic impact of COVID-19 policies across Africa.</li>
          <li>Improved causality analysis accuracy and reduced processing time by 30% through feature selection.</li>
        </ul>
      </div>

      <div class="cv-entry">
        <div class="cv-entry-head">
          <div class="cv-role">Industrial Researcher Intern</div>
          <div class="cv-date">Jun 2019 – Aug 2019</div>
        </div>
        <div class="cv-org">Hitachi Research &amp; Development, Tokyo, Japan</div>
        <ul class="cv-list">
          <li>Re-engineered a Maximum Power Point Tracking (MPPT) algorithm in C for photovoltaic microgrid applications, improving energy harvest efficiency and inverter performance under varying irradiance conditions.</li>
          <li>Conducted distribution system reliability studies, including circuit performance evaluation and N-1 contingency analysis.</li>
          <li>Participated in technical strategy meetings with industrial partners to align R&amp;D outcomes with commercialization objectives.</li>
        </ul>
      </div>

      <div class="cv-entry">
        <div class="cv-entry-head">
          <div class="cv-role">Project Engineer Intern</div>
          <div class="cv-date">Aug 2020 – Oct 2020</div>
        </div>
        <div class="cv-org">Energy Development Corporation Limited, Kirehe, Rwanda</div>
        <ul class="cv-list">
          <li>Supervised quality control for medium- and low-voltage distribution line construction, ensuring compliance with utility standards.</li>
          <li>Performed distribution planning and reliability studies, including thermal loading, N-1 contingency analysis, large-load interconnection review, and DER integration evaluation.</li>
          <li>Developed scoping documents for distribution system improvement projects, including substation upgrades, transformer replacements, and distribution automation improvements.</li>
          <li>Digitized more than 1,000 customer records to improve operational accessibility.</li>
        </ul>
      </div>

      <div class="cv-entry">
        <div class="cv-entry-head">
          <div class="cv-role">Electrical Engineer Intern</div>
          <div class="cv-date">May 2017 – Sep 2017</div>
        </div>
        <div class="cv-org">Pfunda Tea Factory, Rubavu, Rwanda</div>
        <ul class="cv-list">
          <li>Monitored and optimized plant electrical system performance through real-time load analysis.</li>
          <li>Installed and configured three-phase induction motors with star-delta starters, reducing inrush current and improving operational reliability.</li>
          <li>Redesigned factory lighting systems with energy-efficient fixtures to improve workplace safety and energy utilization.</li>
        </ul>
      </div>
    </section>

    <div class="two-col">
      <section class="cv-section">
        <h2 class="cv-section-title">Publications and Posters</h2>
        <ul class="cv-list">
          <li>N. Uwamahoro and S. Eftekharnejad, “Dynamic Community Detection from Temporal Sequences of Cascading Failures in Power Grids,” 2025 57th North American Power Symposium (NAPS), IEEE Xplore, 2025.</li>
          <li>N. Uwamahoro and S. Eftekharnejad, “A Comparative Study of Data-Driven Power Grid Cascading Failure Prediction Methods,” 2023 North American Power Symposium (NAPS), IEEE Xplore, 2023. <strong>(First Place Graduate Paper Award)</strong></li>
          <li>N. Uwamahoro and S. Eftekharnejad, “The Impact of Large Data Center Load Uncertainties on Power Grid Reliability,” IEEE PES General Meeting, 2026. <strong>(Accepted)</strong></li>
          <li>N. Uwamahoro, P. Karia, S. Araballi, B. Yang, and N. Gautam, “Adaptive Hybrid Ensemble Learning Method for Robust Net Load Forecasting in Power Grid,” submitted to IEEE PES General Meeting, 2026.</li>
          <li>O. Ajayi, N. Uwamahoro, and B. Rawn, “A Cost-Effective Open-Source Synchrophasor for Power Grid Monitoring: A Case Study for Rwanda,” submitted to IEEE PES General Meeting, 2026.</li>
          <li>Poster and presentation record includes NY-BEST 2025, NAPS 2023, Syracuse University ECE Research Day 2023, and the First Rwanda Science, Technology and Innovation Conference 2022.</li>
        </ul>
      </section>

      <section class="cv-section">
        <h2 class="cv-section-title">Achievements and Recognitions</h2>
        <ul class="cv-list">
          <li>Women in Science and Engineering (WiSE) Future Professionals Program Recipient, Syracuse University (2025)</li>
          <li>Selected by PG&amp;E to attend the IEEE PES General Meeting 2025, fully sponsored</li>
          <li>38th Outstanding Teaching Award, Syracuse University (2025)</li>
          <li>First Place Graduate Research Paper Award, 55th North American Power Symposium (2023)</li>
          <li>Teaching Mentor for new Teaching Assistants, Syracuse University (2024–2025)</li>
          <li>Represented the Syracuse University ECE Department at the Tapia Conference (2024)</li>
          <li>Selected by CMU-Africa to complete the final semester at Carnegie Mellon University Pittsburgh (2019)</li>
          <li>Nominated by the University of Rwanda for a Master’s scholarship in Aerospace Engineering at Cranfield University (2017)</li>
        </ul>
      </section>
    </div>

    <section class="cv-section">
      <h2 class="cv-section-title">Professional Service</h2>
      <ul class="cv-list">
        <li>Secretary of Energy and Embedded Systems, Carnegie Mellon University Africa (2019)</li>
        <li>External Reviewer, IEEE PES General Meeting 2026</li>
        <li>External Reviewer, North American Power Symposium (NAPS) 2023</li>
      </ul>
    </section>
  </section>
</div>