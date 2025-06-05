---
layout: default
---

# Welcome to My Page! 

## Featured Project

### [GSoC 2025 Blog]({{ site.baseurl }}/gsoc2025/)
Follow my journey through Google Summer of Code 2025. 

## Latest GSoC Updates

{% assign gsoc_posts = site.posts | where: "categories", "gsoc" | limit: 3 %}
{% for post in gsoc_posts %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

[View all GSoC posts →]({{ site.baseurl }}/gsoc2025/)
