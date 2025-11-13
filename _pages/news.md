---
layout: collection
title: "News"
collection: news
permalink: /news/
author_profile: true
entries_layout: list
---

<ul>
{% assign items = site.news | sort: "date" | reverse %}
{% for item in items %}
  <li>
    <a href="{{ item.url | relative_url }}">{{ item.title }}</a>
    <span> — {{ item.date | date: "%Y-%m-%d" }}</span>
  </li>
{% endfor %}
</ul>
