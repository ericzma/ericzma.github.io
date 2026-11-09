---
layout: page
title: Eric (Zhiqiang) Ma
nav_exclude: true
---

I am a technical professional who combines hands-on expertise in designing
complex systems (financial, distributed, blockchain) with proven experience in
leading engineering teams and managing large-scale software projects.

Find me on [LinkedIn](https://www.linkedin.com/in/ericzma/).

## More about Eric

I received my PhD degree from the
[Department of Computer Science and Engineering](https://www.cse.ust.hk) of
[The Hong Kong University of Science and Technology](https://www.ust.hk) in
2014 and the bachelor's degree in Computer Science from
[Fudan University](http://www.fudan.edu.cn/en/) in 2009.

Find more which I don't list here:
[Search "Eric Zhiqiang Ma"](https://www.google.com/search?q=%22eric+zhiqiang+ma%22)
or
[Search "Zhiqiang Ma" "ust"](https://www.google.com/search?q=%22zhiqiang+ma%22+%22ust%22).

## Contact

Email: zma [at] [this website domain]

## Recent Posts

{% for post in site.posts limit: 10 %}
<article class="recent-post">
  <h3><a href="{{ post.url | relative_url }}">{{ post.title | escape }}</a></h3>
  <p class="meta"><time>{{ post.date | date: "%B %-d, %Y" }}</time> &middot; {{ post.author | default: site.author | escape }}</p>
</article>
{% endfor %}

<p><a href="{{ '/posts/' | relative_url }}">Browse all posts &rarr;</a></p>
