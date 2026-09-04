---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am an Assistant Professor in the School of Computing and Artificial Intelligence at Chungnam National University (CNU), Korea. I received my Ph.D. in Computer Science from KAIST under the supervision of Prof. Jae-Gil Lee and Prof. Kyu-Young Whang. Before joining CNU, I was a Postdoctoral Researcher in the Department of AI at Gwangju Institute of Science and Technology (GIST).

My research focuses on developing human-like reasoning capabilities in artificial intelligence, with an emphasis on abstraction, compositional generalization, and alignment. I use the Abstraction and Reasoning Corpus (ARC) as a testbed for studying general intelligence and investigate how AI systems can acquire structured and reusable reasoning capabilities through program synthesis, trajectory-based learning, reinforcement learning, and neuro-symbolic approaches. Ultimately, I aim to develop general and adaptive AI systems that can learn from limited experience and systematically generalize to diverse and unfamiliar problems.

My work has been published in major machine learning and AI venues, including KDD and ICLR, as well as journals such as ACM TIST, TMLR, and Machine Learning. I have served as an Area Chair for the KDD Datasets and Benchmarks Track and as a Program Committee member for major AI and machine learning conferences. I was selected as a Top 10% Outstanding Reviewer at KDD and received the NRF Postdoctoral Fellowship and the Excellence Postdoctoral Researcher Award at GIST.

Education
------
* 2009.02 - 2013.08   B.S. in School of Computing, KAIST
* 2013.09 - 2016.08   M.S. in School of Computing, KAIST
* 2017.03 - 2023.02   Ph.D. in School of Computing, KAIST


Selected Publications
------
  <ul>{% assign pubs = site.publications | where: "selected", true | sort: "selected_order" %}{% for post in pubs %}
    {% include archive-single-selected.html %}
  {% endfor %}</ul>

[See all publications →](/publications/)
