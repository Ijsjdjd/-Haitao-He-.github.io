---
permalink: /
author_profile: true
stylesheets:
  - /assets/css/home.css
---

<div class="wow-page" id="about">
  <section class="wow-hero">
    <div class="wow-hero-copy">
      <div class="wow-eyebrow">RESEARCH PORTFOLIO · 2026</div>
      <h1>Building systems<br><span>that learn.</span></h1>
      <p class="wow-lead">I work on <strong>foundation-model training</strong>, agentic infrastructure and quantitative research — from scientific data to reliable evaluation.</p>
      <div class="wow-actions">
        <a class="wow-button wow-button--primary" href="#projects">Explore the work <span>↗</span></a>
        <a class="wow-button" href="mailto:18944499902@163.com">Get in touch <span>✉</span></a>
        <a class="wow-text-link" href="{{ site.baseurl }}/zh/">中文主页 →</a>
      </div>
    </div>
    <div class="wow-hero-orbit" aria-label="Foundation models, agents and quantitative research">
      <div class="wow-orbit wow-orbit--one"></div>
      <div class="wow-orbit wow-orbit--two"></div>
      <div class="wow-orbit wow-orbit--three"></div>
      <div class="wow-orbit-core">HH</div>
      <span class="wow-orbit-label wow-orbit-label--top">FOUNDATION<br>MODELS</span>
      <span class="wow-orbit-label wow-orbit-label--right">AGENTS</span>
      <span class="wow-orbit-label wow-orbit-label--left">QUANT</span>
    </div>
  </section>

  <section class="wow-metrics" aria-label="Selected metrics">
    <div><strong>1,714</strong><span>executable SQLite environments</span></div>
    <div><strong>10,660</strong><span>MCP tools built</span></div>
    <div><strong>14,770</strong><span>distillation SFT trajectories</span></div>
    <div><strong>0.15 → 0.25</strong><span>post-cost CSI 300 IR</span></div>
  </section>

  <section class="wow-section" id="experience">
    <div class="wow-section-heading">
      <div><span class="wow-kicker">01 · EXPERIENCE</span><h2>Research in<br>the loop.</h2></div>
      <p>IQuest Research · Ubiquant Investment<br>Research Intern · Beijing · May 2026 — Present</p>
    </div>
    <div class="wow-timeline">
      <article class="wow-timeline-item"><div class="wow-timeline-meta"><span>UBio-ARCK</span><span>General Trace · Agentic Eval</span></div><h3>Open-source agent evaluation</h3><p>Core contributor to an open-source omni-evaluation Agent benchmark; led the General Trace and built an automated Agentic Eval pipeline.</p></article>
      <article class="wow-timeline-item"><div class="wow-timeline-meta"><span>Mid-Training</span><span>Scientific research data</span></div><h3>From papers to annealing data</h3><p>Selected research questions, methods and solutions from papers, then used models to synthesize high-quality annealing data for mid-training.</p></article>
      <article class="wow-timeline-item"><div class="wow-timeline-meta"><span>Teacher-model SFT &amp; MOPD</span><span>Next-stage merge</span></div><h3>Training-ready teacher assets</h3><p>Built distillation SFT data covering Table Join/Reformat, Zebra Puzzle/Spatial Reasoning and mathematics to train multiple teacher models and provide inputs for subsequent MOPD merging.</p></article>
    </div>
  </section>

  <section class="wow-section" id="projects">
    <div class="wow-section-heading"><div><span class="wow-kicker">02 · SYSTEMS</span><h2>A pipeline,<br>not a slide.</h2></div><p>Mid-Training · Agentic Environment Scaling · Teacher SFT/MOPD · Benchmark Evaluation</p></div>
    <div class="wow-flow">
      <div><b>01</b><h3>Mid-Training</h3><p>Paper-grounded research questions, methods and solutions become high-quality annealing data.</p></div>
      <div><b>02</b><h3>Infra</h3><p>Self-evolving environments, tools and tasks form a reusable agent-training base.</p></div>
      <div><b>03</b><h3>Teacher SFT</h3><p>Distillation trajectories train and screen multiple teacher models.</p></div>
      <div><b>04</b><h3>Evaluation</h3><p>Private benchmark suites make model behavior measurable and comparable.</p></div>
    </div>
    <div class="wow-project-grid">
      <article class="wow-project-card"><span class="wow-card-tag">AGENT INFRASTRUCTURE</span><h3>Agentic Environment Scaling</h3><p>Agent World turns executable environments and MCP tools into a reusable substrate for data generation, SFT and future RL training.</p><ul><li><strong>1,714</strong> executable SQLite environments</li><li><strong>10,660</strong> MCP tools</li><li><strong>8,582</strong> multi-turn tasks with self-evolving expansion</li></ul><div class="wow-tags"><span>SQLite</span><span>MCP</span><span>Agent infra</span><span>Self-evolving</span></div></article>
      <article class="wow-project-card"><span class="wow-card-tag">TEACHER-MODEL PIPELINE</span><h3>Distillation SFT &amp; MOPD</h3><p>After mid-training, mathematical SFT data and task-specific trajectories train multiple teacher models and provide inputs for downstream MOPD merging.</p><ul><li><strong>4.55M</strong> mathematical SFT examples labelled and filtered</li><li><strong>14,770</strong> distillation SFT trajectories</li><li>Table Join/Reformat · Zebra Puzzle/Spatial Reasoning</li></ul><div class="wow-tags"><span>SFT</span><span>Distillation</span><span>Teacher models</span><span>MOPD</span></div></article>
    </div>
  </section>

  <section class="wow-section" id="publications">
    <div class="wow-section-heading"><div><span class="wow-kicker">03 · RESEARCH</span><h2>Evidence<br>over noise.</h2></div><p>Selected publications and current research directions.</p></div>
    <div class="wow-publications">
      <article><span>KDD 2026 · ACCEPTED</span><h3><i>NMRGym: A Comprehensive Benchmark for Nuclear Magnetic Resonance Based Molecular Structure Elucidation.</i></h3><p>Core contributor.</p></article>
      <article><span>ACM MM 2026 · ACCEPTED</span><h3><i>Knowing the Self, Understanding the World: A Dual-Cognition Benchmark for UAV Spatio-temporal Reasoning with MLLMs.</i></h3><p>Core contributor.</p></article>
      <article><span>NATURE MI · UNDER REVIEW</span><h3><i>Generative model for discovering microbiome-derived peptide ligands of G protein-coupled receptors.</i></h3><p>Core contributor.</p></article>
    </div>
  </section>

  <section class="wow-section" id="quant"><div class="wow-section-heading"><div><span class="wow-kicker">04 · QUANT</span><h2>Agents that<br>remember.</h2></div><p>Recursive Self-Improvement for financial-factor discovery.</p></div><article class="wow-quant-card"><div class="wow-quant-copy"><span class="wow-card-tag">AI QUANT FACTOR DISCOVERY · RSI</span><h3>Macro brain → Micro brain → Cross-brain memory</h3><p>The macro brain reads reports and retrieves evidence; specialist Agents generate hypotheses; the micro brain turns them into factor code, mutates and tests them, and checks their financial logic; a cross-agent brain summarizes each round and feeds the memory back into the next iteration.</p></div><div class="wow-quant-stats"><div><strong>2,500</strong><span>candidate factors</span></div><div><strong>2</strong><span>effective factors</span></div><div><strong>0.15 → 0.25</strong><span>post-cost IR</span></div></div></article></section>

  <section class="wow-section" id="contact"><div class="wow-contact"><div><span class="wow-kicker">05 · CONTACT</span><h2>Let’s build a<br>better loop.</h2><p>For research conversations, PhD opportunities or collaborations around model training, agents and quantitative research, feel free to reach out.</p></div><div class="wow-contact-links"><a href="mailto:18944499902@163.com"><small>Email</small><strong>18944499902@163.com</strong><b>↗</b></a><a href="tel:+8618944499902"><small>Phone</small><strong>+86 189 4449 9902</strong><b>↗</b></a><a href="{{ site.baseurl }}/files/English_CV.tex"><small>CV</small><strong>Download LaTeX CV</strong><b>↓</b></a></div></div></section>
</div>
