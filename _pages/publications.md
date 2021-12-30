---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---



<ul>
{% for post in site.publications reversed %}
  <li> <b>{{ post.title }}</b>,<br>
       {% if post.authors %}{{ post.authors }},{% endif %}
       <i>{% if post.shortvenue %}{{ post.shortvenue }}{% else %} working paper{% endif %}</i>.<br>
    {% if post.paperurl and post.paperurl != "" %}<a href='{{ post.paperurl }}' target='_blank'>[paper]</a> {% endif %}
    {% if post.video and post.video != ""%}<a href='{{ post.video }}' target='_blank' >[video]</a> {% endif %} </li>
{% endfor %}
</ul>





<!---
# {% for post in site.publications reversed %}
#  {% include archive-single-publication-line.html %}
# {% endfor %}
--->
