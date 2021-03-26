---
title: Artikel
layout: single
permalink: /artikel/
toc: true
toc_label: "Jahre"
header:
  overlay_image: /images/header/site-header-flat.png
---

```
{% for article in site.articles %}
    {{article.name}}
    {{article.content}}
{% endfor %}

```

<!-- Idee: Posts-by-Tag Page verwenden, Artikel nach Tags ordnen... -->
