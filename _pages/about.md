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
permalink: /
title: "[Market Design for a Monopsonistic Labor Market](http://jesse-silbert.github.io/files/job_matching_without_wage_discrimination.pdf) (with [Wilbur Townsend](https://wilburtownsend.github.io))"
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'When firms have monopsony power, labor markets can be inefficient. This paper asks whether centralized matching can make monopsonistic labor markets more efficient. We construct a job-matching model with fungible workers in which each firm must pay all its workers the same salary. This restriction generates monopsonistic inefficiencies: while the core contains efficient allocations, it can contain inefficient alloca- tions as well. Workers prefer an efficient core allocation over any other core allocation. Firms prefer inef- ficient core allocations in which they pay lower salaries and thus extract greater profits. When production technologies are public information, a strategyproof mechanism can elicit how workers value employment, and thus implement an efficient core allocation. However, no strategyproof mechanism can elicit firms’ production technologies. Thus centralized matching can improve monopsonistic labor markets when the market designer observes production.'
date: 2021
---
This paper is about the number 1. The number 2 is left for future work.

author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

