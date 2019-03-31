---
layout: archive
title: Publications
permalink: /publications/
author_profile: true
---

<b>[Traffic pattern modeling, trajectory classification and vehicle tracking within urban intersections](https://ieeexplore.ieee.org/abstract/document/8090791)</b><br>
<b>Cheng-En Wu</b>, Wen-Yen Yang, Hai-Che Ting, Jia-Shung Wang. <i>International Smart Cities Conference (ISC2), 2017</i> <br>
[[PDF]](https://CEWu.github.io/files/Vehicle_tracking_ICS2_2017.pdf)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
