---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<ul>
{% for post in site.publications reversed %}
  <li> <b>{{ post.title }}</b>,
       {% if post.authors %}{{ post.authors }},{{ %endif }}
       <i>{{ post.short_venue }}</i>n</li>
{% endfor %}
</ul>


<!---
# {% for post in site.publications reversed %}
#  {% include archive-single-publication-line.html %}
# {% endfor %}
--->
