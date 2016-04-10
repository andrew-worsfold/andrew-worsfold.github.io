---
layout: default
title: Archive
---

<div class="archive">

{% for post in site.posts  %}

{% capture this_year %}{{ post.date | date: "%Y" }}{% endcapture %}
{% capture next_year %}{{ post.previous.date | date: "%Y" }}{% endcapture %}

{% if forloop.first %}
<h2>{{this_year}}</h2>
{% endif %}

<div class="archive-item">
    <span class="post-date archive-date">{{ post.date | date: '%B %d, %Y' }}</span>
    <a href="{{ post.url }}" class="archive-title">{{ post.title }}</a>
</div>

{% endfor %}

</div>