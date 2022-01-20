---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% include base_path %}

<!-- {% if author.googlescholar %} -->
  You can also find my articles on <u><a href="ttps://scholar.google.com/citations?user=hNX1L8EAAAAJ&hl=en">my Google Scholar profile</a>.</u>
<!-- {% endif %} -->

## Peer-reviewed journal articles
You can also find my articles on <u><a href="ttps://scholar.google.com/citations?user=hNX1L8EAAAAJ&hl=en">my Google Scholar profile</a>.</u>
<ol>{% for post in site.journals reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ol>

## Peer-reviewed conference publications & workshops

<ol>{% for post in site.confWsps reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ol>

<!-- ## Under review

<ol>{% for post in site.underReview reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ol> -->
