---
layout: default
title: Pathfinder Club - home
---

Gameplay Writeups
-----------------

This is should be text about what Pathfinder is, what the pathfinder club is, who's in the club (first names only) what their characters are, and a little introduction to the writeups.

  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
</div>
