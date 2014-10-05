---
layout: default
title: Pathfinder Club - home
---

This is should be text about what Pathfinder is, what the pathfinder club is, who's in the club (first names only) what their characters are, and a little introduction to the writeups.

Gameplay Writeups
=================

{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; ({{ site.baseurl }}{{ post.url }})[{{ post.title }}]
    {% endfor %}
