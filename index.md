---
layout: default
title: About
---

# Hi, I'm Stanley 👋

Welcome to my corner of the internet. *(Edit this in `index.md` — add a sentence or two about who you are, what you work on, and what you're interested in.)*

## What I'm up to

- Something I'm working on
- Something I'm learning
- Something I'm excited about

## Recent posts

<ul class="post-list">
{% for post in site.posts limit:5 %}
  <li><span class="meta">{{ post.date | date: "%b %-d, %Y" }}</span> <a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
