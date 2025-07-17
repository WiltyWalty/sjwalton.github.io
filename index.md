---
layout: default
title: Home
---

I am an academic researcher and lecturer, with 10 years' experience in qualitative humanities and social science research and education. My work has been people-centric, from life-histories to focus groups, bridging diverse communities and stakeholders, with outputs including: video documentary, blog, report, academic essay.

## Featured Posts

<div class="row">
{% for post in site.posts %}
{% if post.featured == true %}
{% include featuredbox.html %}
{% endif %}
{% endfor %}
</div>

## Recent Posts

<div class="row">
{% for post in site.posts limit:6 %}
{% include postbox.html %}
{% endfor %}
</div>