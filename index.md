## Under Construction

![Laughing Man](https://i.imgur.com/sdLBre4.png)


{% for post in site.posts %}
  <a href="{{ post.url }}">
    <h2>{{ post.title }}</h2>
  </a>
  <p>{{ post.date | date_to_string }}</p>
  {{ post.excerpt }}
{% endfor %}