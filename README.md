Hello world!

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
