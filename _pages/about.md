---
layout: about
title: about
permalink: /
description: Shuying Cao is a Computer Science M.S. student at USC and Student Research Assistant at Stanford, working on LLM agents, evaluation, and trustworthy AI.
subtitle: From General Capability to Situated Reliability.
redirect_from:
  - /about/
  - /about.html

profile:
  align: right
  image: profile-preview.png
  image_circular: false
  more_info: >
    <p>Student Research Assistant and Visiting Student</p>
    <p>Stanford University</p>
    <p><a href="mailto:shuyingc@stanford.edu">shuyingc@stanford.edu</a></p>
    <p><a href="mailto:shuyingcao7@gmail.com">shuyingcao7@gmail.com</a></p>

selected_papers: true
social: true

announcements:
  enabled: true
  scrollable: false
  limit: 5

latest_posts:
  enabled: false
---

Benchmarks test what models can answer; my work studies how foundation models behave as agents in real environments: whether they can complete long-horizon tasks end to end, protect the private context they are given, and recursively improve themselves through structured memory of their own experience.

I am an M.S. student in Computer Science at the University of Southern California, where I work with [**Prof. Sai Praneeth Karimireddy**](https://spkreddy.org/) on auditing privacy in LLM systems. I am also a Student Research Assistant and Visiting Student at Stanford University, advised by [**Prof. Michael Zeineh**](https://profiles.stanford.edu/michael-zeineh), and a core contributor to Agents' Last Exam v2 at Berkeley AI Research.

My research asks what it takes for foundation models to be reliable once they act as agents in real environments. I build agents that complete long-horizon tasks end to end, such as NeuroImAgent, which runs full neuroimaging pipelines on raw MRI and improves itself through a memory graph linking past protocols, decisions, tool calls, and outcomes. I build evaluations that measure whether agents actually succeed on such tasks, including an executable, auto-graded benchmark of real scientific work. And I audit whether models protect the private context they are given, as in ContextLeak, a black-box framework that turns auditor accuracy into an empirical lower bound on privacy leakage.

Previously, I received my B.E. in Geodesy and Geomatics Engineering from Wuhan University, advised by [**Prof. Zhenzhong Chen**](https://zhenzhong-chen.github.io/), and was a visiting student at UC Berkeley's SKY Lab, where I worked with [**Prof. Joseph E. Gonzalez**](https://people.eecs.berkeley.edu/~jegonzal/) and [**Tianjun Zhang**](https://tianjunz.github.io/) on vision-language assistants for reading figures in research papers.

[Curriculum Vitae]({{ '/files/Shuying_Cao_CV.pdf' | relative_url }}) · [Google Scholar](https://scholar.google.com/citations?user=36r5lAkAAAAJ&hl=en) · [GitHub](https://github.com/CCCCsy7) · [LinkedIn](https://www.linkedin.com/in/shuying-cao-0ab112234)

{% include home_sections.liquid %}
