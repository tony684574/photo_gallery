---
layout: post
title: "Lake Isabella"
images: 
  - image_path: /images/lake_isabella/DSCF3688.JPG
    title: none
  - image_path: /images/lake_isabella/DSCF3710.JPG
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