---
title: Recipes
layout: home
---

<ul>
  {% for recipe in site.recipes %}
    <li>
      <a href="{{ recipe.url }}"> {{recipe.name}} </a>
    </li>
  {% endfor %}
</ul>

