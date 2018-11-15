---
permalink: /
title: "Yanzhao's Homepage"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am Yanzhao Lai, a PhD Candidate in Economics at The George Washington University.

I am on the job market and will be available for interviews at the 2019 ASSA Annual Meeting in Atlanta.

My current research interests include industrial organization, economics of technological change, innovation and entrepreneurship. My primary research focus is on university technology transfer, academic entrepreneurship, entrepreneurial and innovation ecosystem, with secondary interests in innovations in the financial sector (Fintech).

[Curriculum Vitae](https://laiyz.github.io/files/cv.pdf)

Education
======
* Ph.D., Economics, The George Washington University, Washington, DC, 2019 (expected)
  Dissertation: Essays on Innovation and Entrepreneurship
  
  Committee: Professor Nicholas Vonortas (Chair), Professor Anupama Phene, Professor Roberto Samaniego
* M.A., Economics, Boston University, Boston, MA, 2011
* M.S., Mathematics, University of North Carolina, Wilmington, NC, 2009
* B.A., Information and Computing Science, Huazhong University of Science and Technology, Wuhan, China, 2007

Publications
======
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## Working Papers
{% for post in site.publications reversed %}
  {% if post.publications %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Working in Progress
{% for post in site.publications reversed %}
  {% if post.posts %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
