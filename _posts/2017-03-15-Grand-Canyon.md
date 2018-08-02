---
layout: post
title: "Grand Canyon"
images: 
  - image_path: /images/grand_canyon/DSCF3071.JPG
    title: none
  - image_path: /images/grand_canyon/DSCF3055-3.JPG
    title: none
  - image_path: /images/grand_canyon/IMG_0442.JPG
    title: none
  - image_path: /images/grand_canyon/DSCF3125.JPG
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