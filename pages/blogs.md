---
title: "Blogs and Articles"
layout: default
permalink: /blogs/
---

# 📝 Blogs and Articles

Here are some of my recent writings:

{% raw %}
{% for blog in site.data.profile.blogs_and_articles %}
- **[{{ blog.title }}]({{ blog.url }})** ({{ blog.year }})  
  *{{ blog.type }}*
{% endfor %}
{% endraw %}
