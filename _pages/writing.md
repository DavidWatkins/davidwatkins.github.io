---
layout: archive
title: "Writing"
permalink: /writing/
author_profile: true
---

{% include base_path %}

Essays on robotics, embodied AI, and data collection. Most are co-authored with
[Stefanie Tellex](https://cs.brown.edu/people/stellex/) at
[What to Tell the Robot](https://whattotelltherobot.com/).

{% for post in site.writing reversed %}
  {% include archive-single.html %}
{% endfor %}
