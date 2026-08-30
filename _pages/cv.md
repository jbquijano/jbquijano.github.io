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
* B.S. in Biology, University of the Philippines, Baguio 2013
* M.S. in Marine Science, Marine Science Institute, University of the Philippines, Diliman 2025

Work experience
======
* 2022-2025: Student researcher
  * Marine Molecular Biology Laboratory
  * Duties included: Coral selective breeding, Symbiodiniaceae culturing
  * Supervisor: Dr. Cecilia Conaco

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
