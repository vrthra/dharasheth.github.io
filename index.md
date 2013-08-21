---
layout: page
title: My Lens
tagline: "life in focus."
---
{% include JB/setup %}

<!--
## Food Connection

{% gist 3606472 %}

## Life and Companion

{% gist 3716742 %}
-->

## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

