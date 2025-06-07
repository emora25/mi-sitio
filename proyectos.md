---
layout: page
title: Proyectos
---

# Mis Proyectos

<ul>
  {% for proyecto in site.proyectos %}
    <li>{{ proyecto.title }}</li>
  {% endfor %}
</ul>
