---
layout: default
---
<div style="text-align: center"><img src="https://i.imgur.com/sdLBre4.png" width="100" /></div>


{% for post in site.posts %}
  <a href="{{ post.url }}">
	{{ post.title }}
  </a>
  {{ post.excerpt }}
  {{ post.date | date: "%m/%d/%Y" }}
{% endfor %}