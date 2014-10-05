---
layout: default
title: Welcome to Pathfinder Club!
---

<div id="sidebar">
<h2>Gameplay Writeups</h2>
<ul>
{% for post in site.posts %}
{{ post.date | date_to_string }}<br/><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    {% endfor %}
</ul>
</div>

<!-- all changes should happen below this point -->

This should be text about what Pathfinder is, what the pathfinder club is, who's in the club (first names only) what their characters are, and a little introduction to the writeups.
