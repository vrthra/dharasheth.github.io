---
layout: page
title: My Lens
tagline: "life in focus."
---
{% include JB/setup %}

<img src="https://raw.github.com/dhakkada/dhakkada.github.io/master/images/dha2.jpeg" alt="Dhara" style="float:left; width: 80px;
    -webkit-border-radius: 10px;
    -moz-border-radius: 10px;
    border-radius: 10px;
    margin: 10px 10px 10px 10px;
"/>

**Dhara Sheth** is a School Counseling graduate from Portland State University, with a background in Counseling Psychology and Education. As a volunteer in Portland, she participates in activities organized by SAWERA, IRCO, Blanchet House, and Oregon Food Bank. She believes in non-violence, and being an Indian national she enjoys cooking different Indian dishes. In her free time, she enjoys reading, hiking, playing games, and listening to music.

## Posts <a href='https://github.com/dhakkada/dhakkada.github.io/tree/master/_posts/mylens'>.</a>

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

