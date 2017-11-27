---
layout: default
title: 基于模式识别的预估技术
---

# {{ page.title }}
## 最新文章

{% for post in site.posts %}
- {{ post.date | date_to_string }} [ {{ post.title }} ]( {{ site.baseurl }}{{ post.url }} )
{% endfor %}
