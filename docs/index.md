---
layout: default
title: "MS Capstone Blog"
---

# Welcome to my MS Capstone Blog!

This blog will update weekly with any project updates/learnings. Below are the most recent posts (newest at the top):

{% for post in site.posts %}
1. ## [{{ post.title }}]({{ post.url | relative_url }})
   *{{ post.date | date: "%B %d, %Y" }}*
   
   {{ post.excerpt }}
   
   ---
{% endfor %}
