---
title: "Pravy Prerana"
layout: default
---

# Welcome to My Website 🌸

Hi, I'm **Pravy Prerana**!  
This is my personal GitHub Pages site.

## About Me
I’m passionate about [add your interests here].

## Contact
You can reach me at:  
- GitHub: [My GitHub Profile](https://github.com/PravyPrerana-1610)



## 📝 Blogs and Articles
Here are some of my writings:

{% for blog in site.data.profile.blogs_and_articles %}
- **[{{ blog.title }}]({{ blog.url }})** ({{ blog.year }})  
  *{{ blog.type }}*
{% endfor %}

---

## 🎨 My Paintings
{% for painting in site.data.profile.paintings %}
### {{ painting.title }} ({{ painting.year }})

![{{ painting.title }}]({{ painting.image_url }})

{{ painting.description }}

---

{% endfor %}
