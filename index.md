---
layout: default
---

# Welcome to My Page! 

### [GSoC 2025 Blog]({{ site.baseurl }}/gsoc2025/)
My journey through Google Summer of Code 2025. 

{% assign gsoc_posts = site.posts | where: "categories", "gsoc" | limit: 3 %}
{% for post in gsoc_posts %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

[View all GSoC posts →]({{ site.baseurl }}/gsoc2025/)
