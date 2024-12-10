---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
---

<ul>
  <li>Recipes:
    <ul>
    {% for recipe in site.recipes %}
      <li>
        <a href="{{ recipe.url }}"> {{recipe.name}} </a>
      </li>
    {% endfor %}
    </ul>
  </li>
</ul>