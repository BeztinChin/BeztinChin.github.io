# Welcome to Beztin's Pages

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>

 [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
 [x] list syntax required (any unordered or ordered list supported)
 [x] this is a complete item
 [ ] this is an incomplete item



