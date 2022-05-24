---
layout: page
title: "Poems."
author: putri novianti
---

<div class="toc">
  <h2>Daftar Puisi</h2>
  <ul class="poem">
  {% for item in site.puisi %}

    <li>
      <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
      </a>
    </li>
  {% endfor %}
  </ul>
</div>
