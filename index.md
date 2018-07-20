# Welcome to Beztin's Pages

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.excerpt }}</p>
      <p>{{ post.date|date_to_string }}</p>
    </li>
  {% endfor %}
</ul>



