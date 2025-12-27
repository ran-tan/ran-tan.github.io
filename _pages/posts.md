---
title: "Posts"
layout: single
permalink: /posts/
author_profile: true
---

Here you'll find my blog posts covering various topics in software engineering, machine learning, data systems, and related fields.

---

## Recent Posts

{% for post in site.posts limit: 10 %}
### [{{ post.title }}]({{ post.url }})
- {{ post.date | date: "%B %d, %Y" }}
{% for category in post.categories %}
- {{ category }}
{% endfor %}
{% endfor %}
