---
layout: post
title: "Death Valley"
images: 
  - image_path: /images/death_valley/DSCF3573.jpg
    title: none
  - image_path: /images/death_valley/IMG_9320.jpg
    title: none
  - image_path: /images/death_valley/DSCF3589.jpg
    title: non
  - image_path: /images/death_valley/DSCF3657.jpg
    title: none
  - image_path: /images/death_valley/DSCF3670.jpg
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