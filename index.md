---
layout: page
---
{% include JB/setup %}

<ul class="posts">
  {% for post in site.posts %}
    <li>
      <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
      <span>{{ post.date | date: "%Y-%m-%d" }}</span> 
    </li>
  {% endfor %}
</ul>


