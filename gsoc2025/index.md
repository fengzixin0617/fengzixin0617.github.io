---
layout: default
---

# GSoC 2025 Blog

On this blog, I will regularly document my progress on my GSoC 2025 project. 

## Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

