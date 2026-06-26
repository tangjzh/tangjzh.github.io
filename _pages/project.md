---
layout: archive
permalink: /project/
title: "Projects"
author_profile: true
redirect_from: 
  - /pj/
  - /project.html
---

{% include base_path %}

Selected research engineering projects — closed-loop embodied agents and training-data pipelines for VLA / world models.

{% for post in site.projects reversed %}
  {% include archive-single-project.html %}
{% endfor %}
