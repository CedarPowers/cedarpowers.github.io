---
layout: home
---
<h3>Hello! Welcome to my little website.</h3>
Here are my latest posts:

<ul>
{% for post in site.posts %}
  <h2>
    <a href="{{ post.url }}">
      {{ post.title }}
    </a>
  </h2>
{% endfor %}
</ul>
