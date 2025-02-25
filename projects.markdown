---
layout: default
title: "Projects"
permalink: /projects/
---

# <span style="color:green;">Projects</span>

## <span style="color:green;">Project 1: A Comparative Study of Data-Driven Power Grid Cascading Failure Prediction Methods</span>

### <span style="color:green;">Abstract</span>  
Cascading failures in power grids, where failures propagate from one component to another, are a major cause of large-scale blackouts. With renewed interest in enhancing power grid resilience, predicting cascading failures has become crucial for implementing effective mitigation strategies.  

Existing cascading failure prediction methods often struggle with **accuracy, computation time, and dataset imbalances**. In this study, we conduct a **comparative analysis of various data-driven methods** for failure prediction that offer **shorter computation times** and improved predictive accuracy.  

The problem is formulated as a **binary classification task**, where input features (such as transmission line loading levels) are mapped to their **failure status**. To validate our approach, we apply the proposed methods to the **IEEE 30-bus system**, demonstrating their viability in power grid failure prediction.  

This study provides insights into developing fast and accurate data-driven cascading failure models, aiding future research on **power system reliability and outage classification**.  

### <span style="color:green;">Publication</span>  
**Uwamahoro, Nathalie**, and **Sara Eftekharnejad**.  
*"A Comparative Study of Data-Driven Power Grid Cascading Failure Prediction Methods."*  
In **2023 North American Power Symposium (NAPS),** IEEE, 2023.

---

## <span style="color:green;">Project 2: Community Detection in the Power System</span>

### <span style="color:green;">Abstract</span>  
Modern power grids are **highly interconnected**, making them vulnerable to cascading failures when a **single component fails**. Accurately modeling these failures is **critical for grid reliability**, but understanding **complex dependencies** among grid components remains a challenge.  

This study introduces a **clustering-based community detection method** that identifies **vulnerable transmission lines** using **conditional failure probabilities**. By classifying components into **vulnerable** and **non-vulnerable** categories, this approach enhances grid monitoring, reduces operational costs, and mitigates fault propagation.  

Our methodology is applied to the **IEEE 30-bus and Illinois 200-bus systems** using **simulated cascading failure data**. We utilize a **graph-based community detection algorithm** on an **interaction matrix** derived from historical or simulated failure data. In this model:
- Transmission lines are treated as **graph vertices**.
- Edge weights represent **conditional failure probabilities**.
- A **threshold-based clustering strategy** classifies lines into failure risk categories.

A **sensitivity analysis** is conducted to evaluate the robustness of this method under different probability thresholds. Results indicate that **historical cascade data effectively clusters transmission lines**, pinpointing vulnerable areas. However, increasing the failure probability threshold reduces the number of identified vulnerable lines while increasing **non-vulnerable classifications**.

Future work aims to integrate **cluster status as a predictive variable** in cascading failure models and develop **real-time monitoring strategies** for enhancing grid resilience.

### <span style="color:green;">Poster Presentation</span>  
**Uwamahoro Nathalie**, **Sara Eftekharnejad**.  
*"Community Detection in Power Grids with Graph-based Methods Using Cascading Failure Data."*  
**Presented at:** *North American Power Symposium (NAPS), Asheville, NC, US. October 2023.*

---

## <span style="color:green;">Project 3: A Feasibility Study of Li-Ion Battery Refurbishment</span>

### <span style="color:green;">Abstract</span>  
The demand for Li-ion batteries is increasing due to the transition toward a low-carbon future across various sectors. Electric vehicles, including electric motorbikes in East Africa, heavily rely on Li-ion battery packs. Additionally, electronic devices worldwide contribute to a significant increase in Li-ion battery waste each year.

Understanding the key parameters of battery packs is crucial for predicting performance degradation and ensuring safe and efficient second-life applications. This study investigates the internal resistance variations of battery cells, which impact battery pack longevity and safety. Over time, cell-to-cell voltage deviations become apparent, leading to reduced efficiency and safety concerns. Analyzing these deviations enables effective refurbishment strategies.

Refurbishing Li-ion battery packs offers a sustainable solution to reducing battery waste. However, research into the characteristics of post-first-use Li-ion cells remains limited. This study identifies and analyzes the critical characteristics necessary for battery refurbishment, with a focus on:
- Conducting a literature review to assess the current state of Li-ion battery technologies.
- Identifying essential cell characteristics for effective refurbishment.
- Analyzing internal impedance using electrochemical impedance spectroscopy (EIS) to evaluate cell viability.

### <span style="color:green;">Project Report</span>  
*A Feasibility Study of Li-Ion Battery Refurbishment*  
[18980-RW-M.S. GRADUATE PROJECT REPORT, Carnegie Mellon University - Africa Campus](https://drive.google.com/file/d/1_j6ojmbcMDNtEyEQB6tt81iLtUlXqVxu/view?usp=sharing)
