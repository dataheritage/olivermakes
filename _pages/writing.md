---
title: Writing
layout: category
category: index
description: 'A repository of writing and notes on archiving, technology, and other topics, by Oliver Pattison.'
permalink: /writing/

---

{% for post in site.categories.writing limit:8 %}
{% include block/item.html %}
{% endfor %}
{% include block/index-nav.html %}
