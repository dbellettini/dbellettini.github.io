---
layout: page
title: Free software
tagline: "my contribution"
---
{% include JB/setup %}
I opened this blog to talk about my free software projects hosted on GitHub.

Below you can find links to my blog posts:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
