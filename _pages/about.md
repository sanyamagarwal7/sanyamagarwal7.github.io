---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I'm a PhD student in Computer Science at Saarland University advised by Prof. Markus Bl\"aser. Previously I completed my M.Sc. in computer science at CMI, advised by Prof. Nitin Saxena. Long before that, I obtained a B.Tech. in Mechanical Engineering from IIT Delhi. My research interests lie in exploring the computational aspects in Algebra.

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


Acknowledgement
------
This website was forked from [Academic Pages](https://academicpages.github.io/)

