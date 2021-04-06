---
layout: archive
title: "Publications Summary"
permalink: /publications-summary/
author_profile: true
---

{% include base_path %}

{% for post in site.publications reversed %}
  * **{% post.title %}**, {% post.venue %}, {% post.year %}. Okke
{% endfor %}
