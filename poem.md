---
layout: page
title: "Poems."
author: putri novianti
---

<div class="toc">
  <h2>Daftar Puisi</h2>
  <ul class="texts">
  {% for item in site.texts %}

    <li class="text-title">
      <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
      </a>
    </li>
  {% endfor %}
  </ul>
</div>
