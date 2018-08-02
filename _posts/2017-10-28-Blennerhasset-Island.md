---
layout: post
title: "Blennerhasset Island"
images: 
  - image_path: /images/blennerhasset_island/DSCF5669.jpg
    title: Beaufiful Greens and Blues
  - image_path: /images/blennerhasset_island/DSCF5671.jpg
    title: Beaufiful Greens and Hues
  - image_path: /images/blennerhasset_island/DSCF5706.jpg
    title: Beaufiful Greens and Trues
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