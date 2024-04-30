---
layout: archive
title: "Workshop Organization"
permalink: /workshops/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">I have co-organized two conference workshops.</div>
{% endif %}

{% include base_path %}

{% for post in site.workshops reversed %}
  {% include archive-single.html %}
{% endfor %}
