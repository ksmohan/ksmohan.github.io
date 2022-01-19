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

## Peer-reviewed journal articles

{% for post in site.journals reversed %}
  {% include archive-single.html %}
{% endfor %}

## Peer-reviewed conference publications & workshops

<ul>{% for post in site.journals reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
<!-- {% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->

## Under review

<ol>{% for post in site.journals reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ol>
<!-- {% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->
