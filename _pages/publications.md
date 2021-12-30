---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<ol>
{% for post in site.publications reversed %}
  <li><b>{{ post.title  | remove: "<p>" | remove: "</p>" }}</b></li>
{% endfor %}
</ol>



<ol>
{% for post in site.publications reversed %}
  <li><b>{{ post.title }}</b>, {{ post.authors }}, <i>{{ post.venue }} {{ post.year }}<i></li>
{% endfor %}
</ol>


<!---
# {% for post in site.publications reversed %}
#  {% include archive-single-publication-line.html %}
# {% endfor %}
--->
