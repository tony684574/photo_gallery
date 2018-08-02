---
layout: post
title: "Salt Lake City"
images: 
  - image_path: /images/salt_lake_city/DSCF2301.JPG
    title: none
  - image_path: /images/salt_lake_city/IMG_9295.JPG
    title: none
---

<ul>
  {% for item in page.images %} <br>
    <li>
      <a href="{{ item.link }}">
        <img width="500" src="{{ item.image_path }}" alt="{{ item.title }}" class="img-response">
      </a>
    </li>
  {% endfor %}
</ul>