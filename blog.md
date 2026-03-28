---
layout: home
title: Blog
permalink: /blog/
---

Welcome to our blog! Here we share updates, thoughts, and technical details about the Binoio Family of Apps.

## Recent Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
