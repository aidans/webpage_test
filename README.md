Hello world!

<ul>
  {% for post in site.posts %}
    <li>
      <a href="website_text/{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
