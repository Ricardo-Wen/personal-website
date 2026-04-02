---
layout: page
title: Research
permalink: /research/
nav: true
nav_order: 4
---

<style>
  .research-card {
    margin-bottom: 2.5rem;
    padding: 2rem;
    border-left: 3px solid var(--global-theme-color);
    background: var(--global-bg-color);
    border-radius: 4px;
    box-shadow: 0 1px 3px rgba(0,0,0,0.06);
  }
  .research-card h3 {
    font-size: 1.15rem;
    margin-bottom: 0.5rem;
    color: var(--global-text-color);
  }
  .research-card .meta {
    font-size: 0.85rem;
    color: var(--global-text-color-light);
    margin-bottom: 0.8rem;
  }
  .research-card .meta .badge {
    font-size: 0.7rem;
    vertical-align: middle;
    margin-left: 0.5rem;
  }
  .research-card .finding {
    font-size: 0.92rem;
    line-height: 1.65;
    color: var(--global-text-color);
    margin-bottom: 0.6rem;
  }
  .research-card .finding::before {
    content: "▸ ";
    color: var(--global-theme-color);
    font-weight: bold;
  }
  .research-card .authors {
    font-size: 0.82rem;
    color: var(--global-text-color-light);
    margin-top: 0.5rem;
  }
  .section-label {
    font-size: 1.4rem;
    font-weight: 500;
    margin-bottom: 1.5rem;
    margin-top: 2.5rem;
    color: var(--global-text-color);
    border-bottom: 1px solid var(--global-divider-color);
    padding-bottom: 0.5rem;
  }
  .section-label:first-of-type {
    margin-top: 0;
  }
</style>

My research examines how digital platforms and urban systems interact, spanning **sharing economy spillover effects**, **revenue management**, **livestream commerce**, **AI-driven retail**, and **urban safety**. The following projects reflect my research agenda.

---

<div class="section-label">Sharing Economy & Urban Spillovers</div>

<div class="research-card">
  <h3>Boosting and Burdening: Dual Spillover Effects of Bike-Sharing Networks on Home-Sharing Performance</h3>
  <div class="meta">
    <em>Under Review at Production and Operations Management</em>
    <span class="badge rounded-pill" style="background-color: #C0392B; color: white;">ICIS 2023 Best Student Paper Nomination</span>
  </div>
  <p class="finding">Airbnb properties in newly served bike areas experience a <strong>13.5% monthly revenue increase</strong>; properties in existing service areas connected to new stations experience a <strong>16.9% revenue decline</strong> — revealing a dual spillover driven by location advantage gains versus intensified spatial competition.</p>
  <p class="finding">Mechanism decomposition: destination flexibility, time efficiency, and cost efficiency drive positive spillovers; intensified spatial competition drives negative spillovers. High-end properties benefit more and are more insulated from negative effects.</p>
  <p class="finding">Unlike ride-sharing (location-agnostic), bike-sharing's fixed-station network creates winners and losers through spatially anchored competitive dynamics — a novel <strong>network-driven redistribution</strong> mechanism.</p>
  <div class="authors"><strong>Authors:</strong> <em>Muchen Wen</em>, Junming Liu, Juhee Kwon*, Kyung Sung Jung, Young Kwark</div>
</div>

<div class="research-card">
  <h3>Protecting You, Threatening Your Property: Impacts of Bike-Sharing on Urban Crime</h3>
  <div class="meta"><em>Under Review at Decision Sciences</em></div>
  <p class="finding">Documents a <strong>paradoxical dual effect</strong>: personal (violent) crimes decline by <strong>5.3%</strong> after bike-sharing entry, while nighttime property crimes increase by <strong>3.6%</strong> — the same infrastructure simultaneously enhances both offender and victim mobility.</p>
  <p class="finding">Community heterogeneity: personal crime reduction is stronger in <strong>low-income communities</strong>; property crime increase concentrates in <strong>high-income communities</strong>.</p>
  <p class="finding">Intensive police deployment <strong>amplifies both effects</strong>, revealing that traditional policing cannot detect stealthy, dispersed bike-enabled property crimes. Advances Routine Activity Theory.</p>
  <div class="authors"><strong>Authors:</strong> Baozhen Zhan, Yulan (Amanda) Wang, Gengzhong Feng, <em>Muchen Wen*</em>, Jun Lin</div>
</div>

<div class="research-card">
  <h3>Rethinking Conventional Wisdom: The Net Spillover Effect of Bike Sharing Entry on Restaurant Patronage</h3>
  <div class="meta"><em>Target: Journal of Marketing Research</em></div>
  <p class="finding">Challenges the assumption that bike-sharing universally benefits local businesses. Using <strong>3+ billion location pings from 1.27M residents</strong> across 20,000+ restaurants, reveals a <strong>"siphon phenomenon"</strong>: in disadvantaged neighborhoods, outward substitution dominates, causing a net decline in patronage.</p>
  <p class="finding">First study to directly observe and disentangle <strong>outward vs. inward substitution</strong> using population-scale mobility data. The net effect emerges from offsetting consumer-level forces, exacerbating regional inequality.</p>
  <p class="finding">Socioeconomic disadvantage amplifies outward substitution; restaurant agglomeration weakens it; poor subway connectivity amplifies inward substitution.</p>
  <div class="authors"><strong>Authors:</strong> <em>Muchen Wen</em>, Junming Liu, Natasha Zhang Foutze, Baohong Sun</div>
</div>

<div class="research-card">
  <h3>Share the Sharing: Spillover Effects of Bike-Sharing on Local Taxi Markets and Driver Welfare</h3>
  <div class="meta">
    <em>Target: Manufacturing & Service Operations Management</em>
    <span class="badge rounded-pill" style="background-color: #D35400; color: white;">IJOPM Workshop 2026 Best Paper Award</span>
  </div>
  <p class="finding">Proposes a novel <strong>Taxi Accessibility Index (TAI)</strong> that predicts where bike-sharing substitutes vs. complements taxis based on road network and traffic flow characteristics.</p>
  <p class="finding">Bike-sharing <strong>increases demand in high-TAI areas</strong> (low matching friction) but <strong>reduces demand in low-TAI areas</strong> (substitution). Demand concentration near bike stations compresses earnings inequality — <strong>low-skill drivers gain, high-skill drivers lose</strong>.</p>
  <p class="finding">Identifies a <strong>demand-side channel</strong> for platform externalities on worker welfare, distinct from labor supply-side channels studied in prior literature.</p>
  <div class="authors"><strong>Authors:</strong> <em>Muchen Wen</em>, Baozhen Zhan, Yulan (Amanda) Wang</div>
</div>

<div class="research-card">
  <h3>The Safety Cost of Micro Mobility: Impact of Bike-Sharing on Traffic Accidents</h3>
  <div class="meta"><em>Target: Manufacturing & Service Operations Management</em></div>
  <p class="finding">Identifies <strong>speed variance</strong> as a previously unrecognized negative externality: introducing cyclists (10-15 km/h) into motor-vehicle traffic (30-50 km/h) increases speed dispersion, raising accident risk through cognitive burden and spatial conflict.</p>
  <p class="finding">Effects concentrate among <strong>trucks and taxis</strong> (frequent bike interactions), at <strong>intersections</strong> (modal mixing peaks), and on <strong>medium-width roads</strong> (constrained passing).</p>
  <p class="finding">Only <strong>protected bike lanes</strong> mitigate the effect; conventional painted lanes and shared lane markings provide no significant safety benefit. Back-of-the-envelope estimate: <strong>$10.6–12.4M</strong> annual accident cost in NYC attributable to bike-sharing.</p>
  <div class="authors"><strong>Authors:</strong> <em>Muchen Wen</em>, Baozhen Zhan, Yulan (Amanda) Wang</div>
</div>

---

<div class="section-label">Revenue Management & Operations</div>

<div class="research-card">
  <h3>Model-Free Online Learning for Revenue Management under Censored Demand</h3>
  <div class="meta"><em>In Progress</em></div>
  <p class="finding">Develops a <strong>model-free online optimization framework (MFO)</strong> based on entropy-regularized policy search, bypassing the parametric demand assumptions required by the traditional "estimate-then-optimize" paradigm in revenue management.</p>
  <p class="finding">Instead of estimating demand distributions from censored data, the algorithm learns optimal seat protection policy directly from observable revenue feedback, achieving a cumulative regret bound of <strong>O(√T)</strong>.</p>
  <p class="finding">The policy trajectory generated by the algorithm enables consistent recovery of underlying demand parameters via maximum likelihood estimation, providing actionable insights for long-term capacity planning.</p>
</div>

---

<div class="section-label">Digital Retail & Consumer Behavior</div>

<div class="research-card">
  <h3>Optimal Product Sequencing in Livestream Commerce: A Structural Model of Cognitive Resource Dynamics</h3>
  <div class="meta"><em>In Progress</em></div>
  <p class="finding">Develops a structural model in which consumers enter a livestream with <strong>finite cognitive resources</strong> that evolve through three mechanisms: passive depletion, rhythmic recovery, and active withdrawal based on cumulative experience.</p>
  <p class="finding">The model estimates how cognitive state interacts with <strong>product characteristics</strong> (functional vs. hedonic) to drive conversion, enabling derivation of optimal product sequences via counterfactual experiments.</p>
  <p class="finding">Quantifies potential revenue gains from <strong>cognitively informed sequencing strategies</strong> relative to current practitioner heuristics.</p>
</div>

<div class="research-card">
  <h3>Reshaping Urban Consumption Geography: A Deep Structural Choice Model of Bike-Sharing Infrastructure and Spatial Consideration Sets</h3>
  <div class="meta"><em>In Progress</em></div>
  <p class="finding">Develops a <strong>Deep Spatial Choice Model (DSCM)</strong> integrating deep learning within a structural discrete choice framework to model how consumers select spatial destinations under evolving accessibility conditions.</p>
  <p class="finding">Leverages population-scale GPS mobility data to show how bike-sharing stations <strong>expand or contract consumers' spatial consideration sets</strong>, thereby redistributing commercial foot traffic across urban space.</p>
  <p class="finding">Conducts counterfactual analyses to quantify commercial spatial externalities, evaluate <strong>equity-aware optimal placement strategies</strong>, and examine complementarities between bike-sharing and public transit.</p>
</div>

<div class="research-card">
  <h3>From Products to Solutions: Designing a Multi-Agent LLM System for Intent-Driven Grocery Recommendation</h3>
  <div class="meta"><em>In Progress</em></div>
  <p class="finding">Studies how LLMs can be orchestrated through a <strong>multi-agent architecture</strong> to transform a shopper's high-level intent into a complete, contextually appropriate shopping solution — a coherent bundle of products.</p>
  <p class="finding">The system decomposes the task across specialized agents responsible for intent parsing, recipe/occasion planning, product matching, and supply-side optimization (inventory, margin-aware substitution).</p>
  <p class="finding">Adopting design science methodology with both offline benchmarks and a <strong>field experiment</strong> with a partnering grocery retailer, establishing "solution-level recommendation" as a new design paradigm.</p>
</div>

---

<div class="section-label">Urban Safety & Human Mobility</div>

<div class="research-card">
  <h3>From Fear to Footprints: Tracing the Behavioral Impact of Urban Violence with GPS Trajectory Data</h3>
  <div class="meta"><em>In Progress</em></div>
  <p class="finding">Leverages <strong>large-scale GPS trajectory data</strong> combined with geo-coded violent crime records to examine how exposure to urban violence reshapes residents' daily behavioral patterns across four dimensions: mobility, spatial choices, temporal choices, and activity composition.</p>
  <p class="finding">Uses a <strong>difference-in-differences design with event study specifications</strong> to trace how behavioral responses unfold over time and vary across individual characteristics and neighborhood contexts.</p>
  <p class="finding">By directly observing complete daily movement patterns at the individual level, <strong>bridges the gap</strong> between survey-based psychological research and aggregate economic studies, revealing behavioral mechanisms through which urban violence propagates broader social costs.</p>
</div>
