---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<ul>
{% for post in site.publications reversed %}
  <li> <b>{{ post.title }}</b>,
       {% if post.authors %}{{ post.authors }},{% endif %}
       <i>{{ post.shortvenue }}</i>. 
    {% if post.paperurl %}<a href='{{ post.paperurl }}'>[paper]</a> {% endif %}
    {% if post.video %}<a href='{{ post.video }}'>[video]</a> {% endif %} </li>
{% endfor %}
</ul>


<!---
# {% for post in site.publications reversed %}
#  {% include archive-single-publication-line.html %}
# {% endfor %}
--->
