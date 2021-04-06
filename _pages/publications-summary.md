---
layout: archive
title: "Publications Summary"
permalink: /publications-summary/
author_profile: true
---

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single-publication-line.html %}
{% endfor %}
