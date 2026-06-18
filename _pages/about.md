---
layout: home
permalink: /
title: "Shuying Cao"
excerpt: "Academic homepage"
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
        At the intersection of
        <span>Trustworthy AI</span>,
        <span>Privacy Auditing</span>,
        <span>LLM Behavior</span>, and
        <span>Human-Centered AI</span>.
      </h1>
      <p class="academic-tagline">
        M.S. student in <strong>Computer Science</strong> at the
        <strong>University of Southern California</strong> and Visiting Student Researcher at
        <strong>Stanford University</strong>.
      </p>
      <div class="academic-schools" aria-label="Education">
        <div class="academic-school">
          <span class="academic-school__mark">USC</span>
          <span>M.S. Computer Science, University of Southern California</span>
        </div>
        <div class="academic-school">
          <span class="academic-school__mark">WHU</span>
          <span>B.Eng. Geodesy and Geomatics Engineering, Wuhan University</span>
        </div>
      </div>
      <div class="academic-actions">
        <a class="academic-cv" href="{{ '/files/Shuying_Cao_CV.pdf' | relative_url }}">Curriculum Vitae &rarr;</a>
        <div class="academic-socials">
          <a href="mailto:shuyingc@stanford.edu" aria-label="Email">Email</a>
          <a href="https://github.com/CCCCsy7" target="_blank" rel="noopener noreferrer">GitHub</a>
          <a href="https://www.linkedin.com/in/shuying-cao-0ab112234" target="_blank" rel="noopener noreferrer">LinkedIn</a>
        </div>
      </div>
    </div>

    <div class="academic-hero__media">
      <div class="academic-portrait">
        <img src="{{ '/images/profile-preview.png' | relative_url }}" alt="Shuying Cao">
      </div>
      <p>Stanford, CA | shuyingc@stanford.edu</p>
    </div>
  </section>

  <section class="academic-section academic-about">
    <h2>About</h2>
    <div class="academic-prose">
      <p>
        I am a M.S. student in Computer Science at the
        <a href="https://www.usc.edu/">University of Southern California</a>, advised by
        <strong>Prof. Sai Praneeth Karimireddy</strong>, and a Visiting Student Researcher at
        <a href="https://www.stanford.edu/">Stanford University</a>, advised by
        <strong>Prof. Michael Zeineh</strong>.
      </p>
      <p>
        My research focuses on trustworthy and human-centered AI, with interests in privacy auditing for large language models,
        diversity in language model generation, LLM persona, and medical AI agents. I am broadly interested in understanding
        how AI systems behave in real-world settings and building methods to make them more reliable, private, and aligned
        with human needs.
      </p>
      <p>
        Previously, I received my B.Eng. in Geodesy and Geomatics Engineering from
        <a href="https://www.whu.edu.cn/">Wuhan University</a>, advised by
        <strong>Prof. Zhenzhong Chen</strong>. I was also a visiting student at
        <a href="https://www.berkeley.edu/">UC Berkeley</a>, where I worked with
        <strong>Prof. Joseph E. Gonzalez</strong> and his former Ph.D. student
        <strong>Tianjun Zhang</strong> on visual-capable chatbot systems based on instruction-tuned language models.
      </p>
    </div>
    <div class="academic-interest-grid">
      <article>
        <h3>Trustworthy LLMs</h3>
        <p>Privacy auditing, leakage evaluation, and reliability under real deployment conditions.</p>
      </article>
      <article>
        <h3>LLM Diversity</h3>
        <p>Understanding why generation collapses and how models choose among multiple valid outputs.</p>
      </article>
      <article>
        <h3>Human-Centered AI</h3>
        <p>Persona systems, medical AI agents, and AI behavior aligned with human needs.</p>
      </article>
    </div>
  </section>

  <section class="academic-section" id="news">
    <h2>News</h2>
    <ul class="academic-news">
      <li><span>Jun 2026</span> Started as a Visiting Student Researcher at Stanford University.</li>
      <li><span>2025</span> Our work on auditing privacy-preserved in-context learning methods was accepted to ACL 2025 L2M2 Workshop.</li>
    </ul>
  </section>

  <section class="academic-section" id="publications">
    <h2>Publications</h2>
    <p class="academic-note">* = equal contribution.</p>
    <article class="academic-pub-card">
      <div class="academic-pub-thumb">
        <span>ContextLeak</span>
      </div>
      <div>
        <h3>ContextLeak: Auditing Leakage in Private In-Context Learning Methods</h3>
        <p class="academic-authors">Jacob Choi*, <strong>Shuying Cao*</strong>, Xingjian Dong*, Amin Banayeeanzade, Wang Bill Zhu, Robin Jia, and Sai Praneeth Karimireddy</p>
        <p class="academic-venue"><em>arXiv preprint arXiv:2512.16059; ACL 2025 L2M2 Workshop</em></p>
        <p>
          ContextLeak is an empirical auditing framework for measuring information leakage in private in-context learning methods using canary insertion and targeted adversarial queries.
        </p>
        <div class="academic-pub-links">
          <a href="https://arxiv.org/abs/2512.16059" target="_blank" rel="noopener noreferrer">arXiv</a>
          <a href="{{ '/publications/' | relative_url }}">details</a>
        </div>
      </div>
    </article>
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

  <section class="academic-section" id="experience">
    <h2>Experience</h2>
    <div class="academic-timeline">
      <article>
        <div>
          <h3>Stanford University</h3>
          <p>Visiting Student Researcher</p>
        </div>
        <span>Jun 2026 - Present</span>
      </article>
      <article>
        <div>
          <h3>University of Southern California</h3>
          <p>M.S. Computer Science</p>
        </div>
        <span>2024 - Present</span>
      </article>
      <article>
        <div>
          <h3>UC Berkeley</h3>
          <p>Visiting student; visual-capable chatbot systems based on instruction-tuned language models.</p>
        </div>
        <span>Previous</span>
      </article>
    </div>
  </section>

  <section class="academic-section">
    <h2>Education</h2>
    <div class="academic-timeline">
      <article>
        <div>
          <h3>University of Southern California</h3>
          <p>M.S. in Computer Science</p>
        </div>
        <span>Present</span>
      </article>
      <article>
        <div>
          <h3>Wuhan University</h3>
          <p>B.Eng. in Geodesy and Geomatics Engineering</p>
        </div>
        <span>Previous</span>
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
