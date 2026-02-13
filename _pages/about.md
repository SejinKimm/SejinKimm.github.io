---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---


I am a Postdoctoral Researcher in the Department of AI Convergence at Gwangju Institute of Science and Technology (GIST), Korea. I received my Ph.D. in Computer Science from KAIST under the supervision of Prof. Jae-Gil Lee and Prof. Kyu-Young Whang. My doctoral research focused on spatio-temporal prediction and transfer learning, and my current work centers on advancing human-like reasoning and abstraction in artificial intelligence.

My research aims to develop abstraction and reasoning capabilities toward general and adaptive intelligence, with a particular focus on ARC-AGI, compositional generalization, program synthesis, and reinforcement learning with trajectory modeling. I have published in leading international conferences, including KDD and ICLR, as well as in Q1 SCI-E journals such as ACM Transactions on Intelligent Systems and Technology.

I currently serve as an Area Chair for KDD 2026 Datasets and Benchmarks Track and as a Program Committee member for AAAI. I was selected as a top 10% Outstanding Reviewer at KDD 2025, and received the NRF Postdoctoral Fellowship (2024–2026) and the Excellence Postdoctoral Researcher Award at GIST.

Education
------
* 2009.02 - 2013.08   B.S. in Computer Science, KAIST
* 2013.09 - 2016.08   M.S. in School of Computing, KAIST
* 2017.03 - 2023.02   Ph.D in School of Computing, KAIST


Selected Publications
------
  <ul>{% assign pubs = site.publications | reverse %}{% for post in pubs %}{% if post.selected %}
    {% include archive-single-selected.html %}
  {% endif %}{% endfor %}</ul>

[See all publications →](/publications/)
