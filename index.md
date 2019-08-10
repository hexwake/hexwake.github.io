---
layout: default
---
![Laughing Man](https://i.imgur.com/sdLBre4.png){: .center-image }


{% for post in site.posts %}
  <a href="{{ post.url }}">
	{{ post.title }}
  </a>
  {{ post.excerpt }}
  {{ post.date | date: "%m/%d/%Y" }}
{% endfor %}