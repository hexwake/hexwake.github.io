## Under Construction

![Laughing Man](https://i.imgur.com/sdLBre4.png)


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}{{ date: ‘%Y %m %d’ }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

{% for post in site.posts %}

    {% capture day %}{{ post.date | date: '%m%d%Y' }}{% endcapture %}
    {% capture nday %}{{ post.next.date | date: '%m%d%Y' }}{% endcapture %}

    {% if day != nday %}
        <h5 class="date">{{ post.date | date: "%A, %B %e, %Y" }}</h5>
    {% endif %}
    {{ post.content }}
    <hr>

{% endfor %}