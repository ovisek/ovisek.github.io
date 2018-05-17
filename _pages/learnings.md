---
layout: archive
title: Daily Learnings
permalink: /learnings/
---

<ul>
{% for item in site.learnings %}
<li>
<h1>      <a href="{{ item.url }}"> {{ item.title }} </a> </h1>
	{{ item.content }}
</li>
{% endfor %}
</ul>
{% include paginator.html %}
