---
title: "Practice Notes"
layout: default
prev_section: index.html
next_section: what-is-a-playbook.html
---

## Posts

<div class="tag-container">
    <span class="tags">Tags:</span>
    {% assign sorted_tags = site.tags | sort %} {% for tag in sorted_tags %} {% assign t = tag | first %}
    <a class="badge bg-insight-purple" href="/tags/#{{ t }}">{{ t }}</a>
    {% endfor %}
</div>
see

## <https://github.com/Insight-Services-APAC/playbook/discussions>
