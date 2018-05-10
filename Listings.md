---
layout: page
title: Listings
image: assets/images/pic11.jpg
---
<h2> List of Properties </h2>

<h4><ul>
  {% for post in site.posts %}
    <li>
      <a href="{{'/' | absolute_url}}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul></h4>





