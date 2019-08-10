## Under Construction

![Laughing Man](https://i.imgur.com/sdLBre4.png)


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>