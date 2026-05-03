---
layout: default
---

## Welcome!

---

<p class="section-title">About Me</p>

I'm a Ph.D. candidate in Computer Science at the University of Texas at Dallas. My research broadly falls into **Neuro-Symbolic Reasoning**, **Explainable decision-making**, and **Code Generation under Low-Resource Settings**. The goal of my research is to help LLMs perform better in reasoning tasks, especially in high-stakes domains such as healthcare and tax compliance where **reliability** and **explainability** are crucial. By allowing LLMs leverage logic programs to encode reasoning, we can reduce hallucination and produce human-readable justifications at the same time.

---

<p class="section-title">Skills</p>

<ul class="skills-list">
  <li class="skill-tag">LLM Agents</li>
  <li class="skill-tag">LLM Fine-Tuning</li>
  <li class="skill-tag">Reinforcement Learning</li>
  <li class="skill-tag">World Modeling</li>
  <li class="skill-tag">Logic Programming</li>
</ul>

---

<p class="section-title">Work Experience</p>

<ul class="experience-list">
  <li class="experience-item">
    <div class="experience-row">
      <div class="experience-header">
        <span class="experience-role">Research Intern</span><span class="experience-org">, Skyfall AI &mdash; New York City, NY (Remote)</span>
      </div>
      <span class="experience-dates">May 2025 &ndash; Aug 2025</span>
    </div>
    <p class="experience-desc">Long-horizon planning for agents in stochastic business simulations via an LLM framework that learns dual code + probabilistic graphical world models; achieved 50-day bankruptcy-free survival in the Mini Amusement Parks benchmark.</p>
  </li>
  <li class="experience-item">
    <div class="experience-row">
      <div class="experience-header">
        <span class="experience-role">Data Science Intern</span><span class="experience-org">, AT&amp;T &mdash; Plano, TX (Remote)</span>
      </div>
      <span class="experience-dates">June 2022 &ndash; Aug 2022</span>
    </div>
    <p class="experience-desc">Name-spinnig fraud detection via a novel character-embedding partial-name matching model (PyTorch); improved detection precision by 26%.</p>
  </li>
  <li class="experience-item">
    <div class="experience-row">
      <div class="experience-header">
        <span class="experience-role">Research Intern</span><span class="experience-org">, Accenture Labs &mdash; Bangalore, India</span>
      </div>
      <span class="experience-dates">July 2019 &ndash; Dec 2019</span>
    </div>
    <p class="experience-desc">Stock movement classification via an LSTM + R-GCN model learned from company knowledge graphs and financial news; achieved a 65% relative improvement over baseline.</p>
  </li>
  <li class="experience-item">
    <div class="experience-row">
      <div class="experience-header">
        <span class="experience-role">Summer Analyst</span><span class="experience-org">, Goldman Sachs &mdash; Bangalore, India</span>
      </div>
      <span class="experience-dates">May 2019 &ndash; Jun 2019</span>
    </div>
    <p class="experience-desc">Complex data retrieval automation via Spring Boot and Elasticsearch; system deployed to production.</p>
  </li>
</ul>

---

<p class="section-title">Selected Publications</p>

<div class="paper-card">
  <p class="paper-title"><a href="https://arxiv.org/abs/2601.18620">CASSANDRA: Programmatic and Probabilistic Learning and Inference for Stochastic World Modeling</a></p>
  <div class="paper-meta">
    <span class="venue-badge">Workshop on World Models (WMW), 2026</span>
  </div>
  <p class="paper-abstract">
    Introduces <strong>CASSANDRA</strong>, a dual-stream framework that integrates code and probabilistic graphical models for stochastic world modeling. The system learns <strong>lightweight, executable world models</strong> that support long-horizon planning in complex environments. Empirically, it helps a planning agent achieve <strong>50-day bankruptcy-free survival</strong> in the Mini Amusement Parks benchmark, significantly outperforming comparable LLM-based world models.
  </p>
  <img class="paper-img" src="images/cassandra.jpg?raw=true" alt="CASSANDRA figure"/>
</div>
<div class="paper-card">
  <p class="paper-title"><a href="https://link.springer.com/chapter/10.1007/978-3-032-15981-6_10">REGAL: Reconstructing Implicit Logic Rules</a></p>
  <div class="paper-meta">
    <span class="venue-badge">Practical Aspects of Declarative Languages (PADL), 2026</span>
  </div>
  <p class="paper-abstract">
    Presents a novel framework for <strong>implicit rule reconstruction</strong>, addressing a key limitation of text-to-logic systems: their inability to recover implicit commonsense rules. REGAL introduces an iterative reasoning pipeline that reconstructs missing logical assumptions, enabling <strong>more complete and faithful logical representations</strong> of natural language reasoning problems.
  </p>
  <img class="paper-img" src="images/regal.png?raw=true" alt="REGAL figure"/>
</div>

<div class="paper-card">
  <p class="paper-title"><a href="https://link.springer.com/chapter/10.1007/978-3-031-52038-9_13">Automated Interactive Domain-Specific Conversational Agents that Understand Human Dialogs</a></p>
  <div class="paper-meta">
    <span class="venue-badge">Practical Aspects of Declarative Languages (PADL), 2024</span>
  </div>
  <p class="paper-abstract">
    Develops a framework for <strong>goal-directed conversational agents</strong> using Answer Set Programming (ASP). Unlike purely neural approaches, the system ensures conversations remain <strong>logically consistent, controllable, and aligned with task objectives</strong>.
  </p>
</div>

<div class="paper-card">
  <p class="paper-title"><a href="https://www.semanticscholar.org/paper/Reliable-Natural-Language-Understanding-with-Large-Rajasekharan-Zeng/b549716038bb167fcc65e3f9f725013d8b2ea649">Reliable Natural Language Reasoning using ASP and LLMs</a></p>
  <div class="paper-meta">
    <span class="venue-badge">International Conference on Logic Programming (ICLP), 2023</span>
  </div>
  <p class="paper-abstract">
    Introduces the <strong>STAR framework</strong>, a neuro-symbolic system combining LLM-based predicate extraction with Answer Set Programming for reliable reasoning. The approach achieves <strong>significant improvements on a qualitative reasoning benchmark (QuaRel)</strong>, especially for smaller LLMs. 
  </p>
  <img class="paper-img" src="images/STAR.png?raw=true" alt="STAR figure"/>
</div>

<div class="paper-card">
  <p class="paper-title"><a href="https://link.springer.com/chapter/10.1007/978-3-031-35254-6_4">Prolog: past, present, and future</a></p>
  <div class="paper-meta">
    <span class="venue-badge">Book Chapter (Pages 48-61 in Prolog: The Next 50 Years), 2023</span>
  </div>
  <p class="paper-abstract">
    Provides a forward-looking perspective on logic programming, highlighting how <strong>goal-directed predicate Answer Set Programming</strong> extends Prolog to support modern AI applications, including <strong>commonsense reasoning and complex decision-making systems</strong>.
  </p>
  <img class="paper-img" src="images/prolog_book.jpg?raw=true" alt="Prolog figure"/>
</div>