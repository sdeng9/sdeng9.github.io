---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## Journal Articles
---

{% for post in site.publications reversed %}
  {% if post.category == 'journal' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Peer Reviewed Conference Articles
---

{% for post in site.publications reversed %}
  {% if post.category == 'conference' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
