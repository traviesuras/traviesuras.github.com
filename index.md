---
layout: page
title: Simple machines
tagline: Some unpretentious software
---
{% include JB/setup %}

# What to expect?

You shouldn't expect to find on my GitHub repo software to change the
world. This is just a collection of simple software, created either
for educational purposes or for my own use.

On this blog I'll be talking mostly about the code. But, please send
comments (and bug reports) if you can contribute.

## The posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

