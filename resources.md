---
layout: page
title: Resources
permalink: /resources/
---

# Resources & Blog

Welcome to the Resources section! Here, you'll find insights, strategies, and best practices for scaling your service business with technology.

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) – {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
