---
layout: home
published: true
title: Home Page
---
## h2
<ul>
  {% for post in site.posts %}
	<li>
	  <a href="{{ post.url }}">{{ post.title }}</a>
	  {{ post.excerpt }}
	</li>
  {% endfor %}
</ul>
<hr>
