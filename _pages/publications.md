---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?view_op=list_works&hl=zh-CN&hl=zh-CN&user=JOIva1oAAAAJ&sortby=pubdate)

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
