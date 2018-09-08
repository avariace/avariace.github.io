---
permalink: /
title: "Qianqian's Homepage"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Qianqian Xie is a Ph.D candidate in School of Computer Science at Wuhan University, Wuhan, China. She received her bachelors degrees from Jiangxi Normal University. Her current research focus areas include natural language processing, machine learning and deep learning.

[Curriculum Vitae](https://xashely.github.io/files/cv.pdf)

Education
======
* Ph.D. in Computer Software and Theory, Wuhan University, 2014 - 2019 (expected)
* B.S. in Computer Science and Technology, Jiangxi Normal University, 2010 - 2014

Publications
======
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
