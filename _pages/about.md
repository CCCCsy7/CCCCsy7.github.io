---
layout: home
permalink: /
title: "Shuying Cao's Homepage"
excerpt: "Shuying Cao is a Computer Science M.S. student at USC and Student Research Assistant at Stanford, working on LLM agents, evaluation, and trustworthy AI."
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<main class="academic-home">
  <section class="academic-hero" id="about">
    <div class="academic-hero__text">
      <p class="academic-eyebrow">Shuying Cao</p>
      <h1>
        From
        <span>General Capability</span>
        to
        <span>Situated Reliability</span>.
      </h1>
      <p class="academic-tagline">
        Benchmarks test what models can answer; my work studies how foundation models behave as agents in real
        environments: whether they can complete long-horizon tasks end to end, protect the private context they are
        given, and recursively improve themselves through structured memory of their own experience.
      </p>
      <div class="academic-actions">
        <a class="academic-cv" href="{{ '/files/Shuying_Cao_CV.pdf' | relative_url }}">Curriculum Vitae &rarr;</a>
        <div class="academic-socials">
          <a href="https://scholar.google.com/citations?user=36r5lAkAAAAJ&amp;hl=en" target="_blank" rel="noopener noreferrer">Google Scholar</a>
          <a href="https://github.com/CCCCsy7" target="_blank" rel="noopener noreferrer">GitHub</a>
          <a href="https://www.linkedin.com/in/shuying-cao-0ab112234" target="_blank" rel="noopener noreferrer">LinkedIn</a>
        </div>
      </div>
    </div>

    <div class="academic-hero__media">
      <div class="academic-portrait">
        <img src="{{ '/images/profile-preview.png' | relative_url }}" alt="Shuying Cao">
      </div>
      <p>
        <span>Student Research Assistant and Visiting Student</span>
        <span>Stanford University</span>
        <span><a href="mailto:shuyingc@stanford.edu">shuyingc@stanford.edu</a></span>
        <span><a href="mailto:shuyingcao7@gmail.com">shuyingcao7@gmail.com</a></span>
      </p>
    </div>
  </section>

  <section class="academic-section academic-about">
    <h2>About</h2>
    <div class="academic-prose">
      <p>
        I am an M.S. student in Computer Science at the University of Southern California, where I work with
        <a href="https://spkreddy.org/" target="_blank" rel="noopener noreferrer"><strong>Prof. Sai Praneeth Karimireddy</strong></a>
        on auditing privacy in LLM systems. I am also a Student Research Assistant and Visiting Student at Stanford
        University, advised by
        <a href="https://profiles.stanford.edu/michael-zeineh" target="_blank" rel="noopener noreferrer"><strong>Prof. Michael Zeineh</strong></a>
        and in collaboration with
        <a href="https://yejinc.github.io/" target="_blank" rel="noopener noreferrer"><strong>Prof. Yejin Choi</strong></a>,
        and a core contributor to Agents' Last Exam v2 at Berkeley AI Research.
      </p>
      <p>
        My research asks what it takes for foundation models to be reliable once they act as agents in real
        environments. I build agents that complete long-horizon tasks end to end, such as NeuroImAgent, which runs
        full neuroimaging pipelines on raw MRI and improves itself through a memory graph linking past protocols,
        decisions, tool calls, and outcomes. I build evaluations that measure whether agents actually succeed on such
        tasks, including an executable, auto-graded benchmark of real scientific work. And I audit whether models
        protect the private context they are given, as in ContextLeak, a black-box framework that turns auditor
        accuracy into an empirical lower bound on privacy leakage.
      </p>
      <p>
        Previously, I received my B.E. in Geodesy and Geomatics Engineering from Wuhan University, advised by
        <a href="https://zhenzhong-chen.github.io/" target="_blank" rel="noopener noreferrer"><strong>Prof. Zhenzhong Chen</strong></a>,
        and was a visiting student at UC Berkeley's SKY Lab, where I worked with
        <a href="https://people.eecs.berkeley.edu/~jegonzal/" target="_blank" rel="noopener noreferrer"><strong>Prof. Joseph E. Gonzalez</strong></a>
        and
        <a href="https://tianjunz.github.io/" target="_blank" rel="noopener noreferrer"><strong>Tianjun Zhang</strong></a>
        on vision-language assistants for reading figures in research papers.
      </p>
    </div>
    <div class="academic-interest-grid">
      <article>
        <h3>LLM Agents &amp; Long-Horizon Tasks</h3>
        <p>Agents that plan, call tools, and finish multi-step workflows end to end in executable environments.</p>
      </article>
      <article>
        <h3>Recursive Self-Improvement</h3>
        <p>Memory graphs and reusable skills that let an agent learn from its own past cases without losing reliability.</p>
      </article>
      <article>
        <h3>Trustworthy AI &amp; Privacy Auditing</h3>
        <p>Black-box auditing of what models leak from private context, and how empirical leakage compares to theoretical guarantees.</p>
      </article>
    </div>
  </section>

  <section class="academic-section" id="education">
    <h2>Education</h2>
    <div class="academic-timeline">
      <article>
        <div>
          <h3>Stanford University</h3>
          <p>Student Research Assistant &amp; Visiting Student</p>
        </div>
        <span>June 2026 - Present</span>
      </article>
      <article>
        <div>
          <h3>University of Southern California</h3>
          <p>M.S. in Computer Science</p>
        </div>
        <span>Sept 2024 - Dec 2026 (expected)</span>
      </article>
      <article>
        <div>
          <h3>UC Berkeley</h3>
          <p>Visiting Student, SKY Lab</p>
        </div>
        <span>Jan 2023 - July 2023</span>
      </article>
      <article>
        <div>
          <h3>Wuhan University</h3>
          <p>B.E. in Geodesy and Geomatics Engineering</p>
        </div>
        <span>Sept 2020 - June 2024</span>
      </article>
    </div>
  </section>

  <section class="academic-section" id="news">
    <h2>News</h2>
    <ul class="academic-news">
      <li><span>Oct 2026</span> Joined Agents' Last Exam v2 at Berkeley AI Research as a core contributor on the science track.</li>
      <li><span>July 2026</span> ContextLeak, our black-box privacy auditing framework for private in-context learning, was accepted to COLM 2026.</li>
      <li><span>June 2026</span> Started as a Student Research Assistant and Visiting Student at Stanford University.</li>
      <li><span>2025</span> Our work on auditing privacy-preserved in-context learning methods was accepted to the ACL 2025 L2M2 Workshop.</li>
    </ul>
  </section>

  <section class="academic-section" id="publications">
    <h2>Publications</h2>
    <p class="academic-note">* = equal contribution.</p>
    <article class="academic-pub-card">
      <div class="academic-pub-thumb">
        <img src="{{ '/images/contextleak-overview.png' | relative_url }}" alt="ContextLeak overview figure">
      </div>
      <div>
        <h3>ContextLeak: Auditing Leakage in Private In-Context Learning Methods</h3>
        <p class="academic-authors">Jacob Choi*, <strong>Shuying Cao*</strong>, Xingjian Dong*, Amin Banayeeanzade, Wang Bill Zhu, Robin Jia, and Sai Praneeth Karimireddy</p>
        <p class="academic-venue"><em>Conference on Language Modeling (COLM) 2026</em></p>
        <p>
          ContextLeak is an empirical auditing framework for measuring information leakage in private in-context learning methods using canary insertion and targeted adversarial queries.
        </p>
        <div class="academic-pub-links">
          <a href="https://arxiv.org/abs/2512.16059" target="_blank" rel="noopener noreferrer">arXiv</a>
          <a href="{{ '/publications/' | relative_url }}">details</a>
        </div>
      </div>
    </article>

    <h3 class="academic-subheading">In Preparation</h3>
    <ul class="academic-pub-list">
      <li>
        <strong>NeuroImAgent: An AI Agent for Translating Pathology to Neuroradiology</strong>
        <span class="academic-authors"><strong>Shuying Cao*</strong>, Yixin Wang*, et al., Yejin Choi, Michael Zeineh</span>
      </li>
      <li>
        <strong>Towards Intent-Aware Language Models</strong>
        <span class="academic-authors">Lihao Sun, Shan Gao, <strong>Shuying Cao</strong>, et al.</span>
      </li>
    </ul>
  </section>

  <section class="academic-section" id="projects">
    <h2>Projects</h2>
    <div class="academic-card-list">
      <article>
        <h3>ContextLeak</h3>
        <p>An auditing framework for empirically measuring information leakage in private in-context learning methods.</p>
        <a href="{{ '/portfolio/contextleak/' | relative_url }}">project page &rarr;</a>
      </article>
      <article>
        <h3>Diversity in Language Model Generation</h3>
        <p>Studying how large language models select from multiple valid outputs and why diversity collapses in generation.</p>
        <a href="{{ '/portfolio/llm-diversity/' | relative_url }}">project page &rarr;</a>
      </article>
      <article>
        <h3>SoulSoul: LLM Persona Platform</h3>
        <p>A platform for creating, editing, and sharing persistent AI personas with memory and interaction boundaries.</p>
        <a href="{{ '/portfolio/soulsoul/' | relative_url }}">project page &rarr;</a>
      </article>
    </div>
  </section>

  <section class="academic-section">
    <h2>Skills</h2>
    <div class="academic-skill-grid">
      <article>
        <h3>Research Areas</h3>
        <p>Trustworthy AI, privacy auditing, LLM behavior, human-centered AI, medical AI agents.</p>
      </article>
      <article>
        <h3>Methods</h3>
        <p>Empirical auditing, canary insertion, targeted adversarial queries, model behavior analysis.</p>
      </article>
      <article>
        <h3>Systems</h3>
        <p>Large language models, instruction-tuned systems, visual-capable chatbots, AI persona platforms.</p>
      </article>
    </div>
  </section>
</main>
