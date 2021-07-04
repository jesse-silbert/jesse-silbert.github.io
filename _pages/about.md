---
permalink: /
title: #"academicpages is a ready-to-fork GitHub Pages template for academic personal websites"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I am a PhD student at the Princeton University Department of Economics interested in labor markets, higher education, industrial organization, market design, and microeconomic theory.

In addition to economics, I am passionate about weird music and good food.

---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

