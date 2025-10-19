---
layout: default
title: Home
---

# {{ site.title }}

{{ site.description }}

## Latest Posts

{% if site.posts and site.posts.size > 0 %}
<ul>
{% for post in site.posts %}
  <li>
    <span>{{ post.date | date: "%b %d, %Y" }}</span>
    — <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
{% else %}
<p>No posts yet. Add markdown files to <code>_posts/</code> named like <code>YYYY-MM-DD-title.md</code>.</p>
{% endif %}

<p>
  <a href="{{ '/about/' | relative_url }}">About</a>
  · <a href="{{ '/feed.xml' | relative_url }}">RSS</a>
  · <a href="https://github.com/utr491">GitHub</a>
  · <a href="/resume.pdf">Resume</a>
  
</p>


