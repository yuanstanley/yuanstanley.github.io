---
layout: default
title: Home
---

# Hi, I'm Stanley 👋

*(Edit this in `index.md`: a few sentences about who you are, what you work on, and what you're interested in.)*

## Writing

{% if site.posts.size > 0 %}
<ul class="post-list">
{% for post in site.posts %}
  <li><span class="meta">{{ post.date | date: "%b %-d, %Y" }}</span> <a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
{% else %}
<p class="meta">Nothing here yet.</p>
{% endif %}
