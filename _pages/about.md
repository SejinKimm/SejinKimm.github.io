---
permalink: /
title: "Sejin Kim"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---


I am a Postdoctoral Researcher at the Department of AI Convergence, Gwangju Institute of Science and Technology (GIST), Korea. I received my Ph.D. in Computer Science from KAIST, where I worked under the supervision of Prof. Jae-Gil Lee, focusing on spatio-temporal prediction and transfer learning for data-poor cities.

My current research focuses on human-like AI, artificial general intelligence, reinforcement learning, and program synthesis. I have published in leading venues, including NeurIPS, KDD, ICML, and IJCAI. I am the recipient of the NRF Postdoctoral Fellowship (2024–2026) for developing AI models with advanced abstraction and reasoning capabilities. I was recognized with the Excellence Postdoctoral Researcher Award at GIST in 2024 and selected as an Outstanding Reviewer at KDD 2025.

Education
------
* 2009.02 - 2013.08   B.S. in Computer Science, KAIST
* 2013.09 - 2016.08   M.S. in School of Computing, KAIST
* 2017.03 - 2023.02   Ph.D in School of Computing, KAIST


Selected Publications
------
  <ul>{% assign pubs = site.publications | reverse %}{% for post in pubs %}{% if post.selected %}
    {% include archive-single-cv.html %}
  {% endif %}{% endfor %}</ul>

[See all publications →](/publications/)
