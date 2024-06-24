---
layout: page
title: "Publications"
permalink: /publications/
---

# Publications

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% for post in site.publications reversed %}
  {% include publication.html %}
{% endfor %}

<sup>*</sup> Equal authorship