---
layout: page
#title: stay hungry, stay foolish!
#tagline: Supporting tagline
---
{% include JB/setup %}

Again, you can't connect the dots looking forward; you can only connect them looking backwards. So you have to trust that the dots will somehow connect in your future. You have to trust in something - your gut, destiny, life, karma, whatever.


<ul class="posts">
  {% for post in site.posts %}
    <h5><li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li></h5>
  {% endfor %}
</ul>


