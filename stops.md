---
layout: post
title: Stops
---

I will stop at these places:

{% for stop in site.data.stops %}
* {{ stop.commune }} at {{ stop.day | date: "%-d %B"}}
{% endfor %}
