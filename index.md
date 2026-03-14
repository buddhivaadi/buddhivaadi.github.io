---
layout: default
title: Home
---

# A Student of Logic

Welcome.

This blog is a record of inquiry. I examine ideas — religious, philosophical, political, and civilizational — through the lens of rational analysis.

Truth is served by **clarity of thought and validity of reasoning**, not by sentiment, authority, or popularity.

---

## Essays

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
