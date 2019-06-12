---
layout: archive
permalink: /blog/
title: "Inside PhoboxHQ"
author_profile: true
---

{% for post in site.posts %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% include archive-single.html %}
{% endfor %}
