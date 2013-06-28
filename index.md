---
published: true
layout: page
title: "PHAT LANs!"
tagline: nerds...
---

Welcome to PHAT LANs.  We are a group of friends in the midwest that love to play video games.  We host LAN parties the first weekend of every month.  Information about our group and those parties can be found here.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
