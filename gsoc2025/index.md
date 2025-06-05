---
layout: default
---

# GSoC 2025 Blog

On this blog, I will regularly document my progress on my GSoC 2025 project. 

## Weekly Updates

{% assign gsoc_posts = site.posts | where: "categories", "gsoc" %}
{% if gsoc_posts.size > 0 %}
{% for post in gsoc_posts %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
{% else %}
- [Week 1: Getting Started]({{ site.baseurl }}/gsoc/week-1/) - June 05, 2025
{% endif %}

