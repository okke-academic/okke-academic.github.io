---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}
Try 1
{% for post in site.publications reversed %}
  1. {{ post.title  | remove: "<p>" | remove: "</p>" }}
{% endfor %}

Try 2
<ol>
{% for post in site.publications reversed %}
  <li>{{ post.title  | remove: "<p>" | remove: "</p>" }}</li>
{% endfor %}
</ol>


Try 3
<ol>
{% for post in site.publications reversed %}
  <li>{{ post.title | markdownify | remove: "<p>" | remove: "</p>" }}</li>
{% endfor %}
</ol>


<!---
# {% for post in site.publications reversed %}
#  {% include archive-single-publication-line.html %}
# {% endfor %}
--->
