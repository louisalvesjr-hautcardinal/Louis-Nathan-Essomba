---
title: "Applied Works (Projects)"
layout: page
permalink: /applied-works/
---

# Applied Works (Projects)

Each project has its own section with multiple posts.

{% for item in site.projects %}
- **{{ item.title }}**  
  [Visit project]({{ item.url }})
{% endfor %}
