---
layout: default
title: Home
---

I am an academic researcher and lecturer, with 10 years' experience in qualitative humanities and social science research and education. My work has been people-centric, from life-histories to focus groups, bridging diverse communities and stakeholders, with outputs including: video documentary, blog, report, academic essay.

<div class="row">
{% for page in site.pages %}
{% if page.featured == true %}
{% include pagebox.html %}
{% endif %}
{% endfor %}
</div>
