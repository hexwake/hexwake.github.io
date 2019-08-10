## Under Construction

<img style="float: center;" src="https://i.imgur.com/sdLBre4.png">


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}{{ page.date | date: "%m/%d/%Y" }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
