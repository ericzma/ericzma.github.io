---
layout: page
title: Posts
---

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }}) — {{ post.date | date_to_string }}
{% endfor %}
