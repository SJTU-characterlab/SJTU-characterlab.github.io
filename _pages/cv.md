---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* 2006/09–2010/07: University of Electronic Science and technology, Bachelor
* 2020/09-2011/09: University College London, Master
* 2011/09-2015/02: University College London, PhD

Work experience
======
* 2015/02-2017/09: University College London, Postdoc
* 2017/09-2019/10: Disney Research Los Angeles, Associate Research Scientist
* 2019/11-Present: Shanghai Jiao Tong University, Associate Professor

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
