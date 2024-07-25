---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a computer scientist from Aalborg University, working on recommender systems. 

Publications
======
<ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
{% endfor %}</ul>
