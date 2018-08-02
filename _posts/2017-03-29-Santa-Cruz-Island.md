---
layout: post
title: "Santa Cruz Island"
images: 
  - image_path: /images/santa_cruz_island/fun_pic.jpg
    title: none
  - image_path: /images/santa_cruz_island/clear_bones.jpg
    title: none
  - image_path: /images/santa_cruz_island/heading_back.jpg
    title: none
  - image_path: /images/santa_cruz_island/santa_cruz.jpg
    title: none
  - image_path: /images/santa_cruz_island/Magenta_Chinese_Harbor.jpg
    title: none
  - image_path: /images/santa_cruz_island/prisoners_harbor.jpg
    title: none
  - image_path: /images/santa_cruz_island/rough_ride.jpg
    title: none
  - image_path: /images/santa_cruz_island/spring_twilight.jpg
    title: none
  - image_path: /images/santa_cruz_island/sunset_campground_malibu.jpg
    title: none
  - image_path: /images/santa_cruz_island/wild_flowers.jpg
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