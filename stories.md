---
layout: page
title: Stories
---

{% for story in site._stories %}
  * {{ story.date | date_to_string }} &raquo; [ {{ story.title }} ]({{ story.url }})
{% endfor %}