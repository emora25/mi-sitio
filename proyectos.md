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
<ul>
  {% for proyecto in site.proyectos %}
    <li>
      <strong>{{ proyecto.title }}</strong> - {{ proyecto.descripcion }} <br />
      Fecha: {{ proyecto.fecha }}
    </li>
  {% endfor %}
</ul>
