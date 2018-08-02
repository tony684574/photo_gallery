---
layout: post
title: "Bryce Canyon"
images: 
  - image_path: /images/bryce_canyon/DSCF3386.JPG
    title: none
  - image_path: /images/bryce_canyon/DSCF3401.JPG
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