---
layout: default
title: صفحه اصلی
---

سلام! من سوگند هستم 👋

## نمونه کارها

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%Y/%m/%d" }}
{% endfor %}
