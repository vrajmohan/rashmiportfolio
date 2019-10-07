---
layout: page
title: Work
permalink: /work/
---

{% for work in site.data.work %}
<a href="{{ work.permalink }}"><img src="{{ work.image }}" width="82" height="86" title="{{ work.category }}">{{ work.category }} </a>
{% endfor %}
