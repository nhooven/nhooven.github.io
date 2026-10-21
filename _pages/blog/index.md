---
layout: single
title: Blog posts
permalink: /blog/
---

Stay tuned for some posts!

[comment]: Loop to display recent posts (all posts?)
<ul>
  {% for post in site.posts %}
    <li>
	
      <a href="{{ post.url }}">{{ post.title }}</a>
	  {{ post.excerpt }}
	  
    </li>
  {% endfor %}
</ul>