---
layout: post
title: Stops
---

I will stop at these places:

{% for stop in site.data.stops %}
* {{ stop.commune }} at {{ stop.day | date: "%-d %B"}}
{% endfor %}

* [route 1]({{site.baseurl}}/assets/day-1.png)
* [route 2]({{site.baseurl}}/assets/day-2.pdf)
* [route 3]({{site.baseurl}}/assets/day-3.pdf)
* [route 4]({{site.baseurl}}/assets/day-4.pdf)
