## Under Construction

![Laughing Man](https://i.imgur.com/sdLBre4.png)


{% for post in site.posts %}
  <a href="{{ post.url }}">
	{{ post.title }}
  </a>
  {{ post.excerpt }}
  {{ post.date | "%m/%d/%Y" }}
{% endfor %}