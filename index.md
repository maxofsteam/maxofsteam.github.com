---
layout: page
title: Welcome to Max's Blog
tagline: I dont give a fuck
---
#<a href="http://blog.maxsblog.de/about.html">About Me</a>

##Here are my posts:
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
 </ul>

 