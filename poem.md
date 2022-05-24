---
layout: page
title: "Poems."
author: putri novianti
---

<div class="toc">
  <h2>Daftar Puisi</h2>
  <ul class="puisi">
  {% for item in site._puisi %}

    <li class="text-title">
      <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
      </a>
    </li>
  {% endfor %}
  </ul>
</div>
