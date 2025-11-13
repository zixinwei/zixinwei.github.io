---
layout: collection
title: "News"
collection: news
permalink: /news/
author_profile: true
entries_layout: list
---

{% include base_path %}

<ul>{% for post in site.news reversed %}
{% include archive-single-talk-cv.html  %}
{% endfor %}</ul>
