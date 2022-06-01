---
layout: default
title: Posts
---

## Posts

<div class="tag-container">
    <span class="tags">Tags:</span>
    {% assign sorted_tags = site.tags | sort %} {% for tag in sorted_tags %} {% assign t = tag | first %}
    <a class="badge bg-insight-purple" href="/tags/#{{ t }}">{{ t }}</a>
    {% endfor %}
</div>

<ul class="posts">
  {% for post in site.categories.posts %}
    <li>
      <div class="publish-date">
        <time datetime="{{ post.date | date: '%F' }}">{{ post.date | date: "%B %-d, %Y" }}</time>
      </div>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>