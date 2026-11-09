---
layout: page
title: Posts
---

<ul class="posts">
{% for post in site.posts %}
  <li><time>{{ post.date | date: "%Y-%m-%d" }}</time><a href="{{ post.url | relative_url }}">{{ post.title | escape }}</a></li>
{% endfor %}
</ul>

---

All content is provided for information reference only, without warranty of
any kind. Please read the [Terms and Policy](/terms/) for the full disclaimer.
