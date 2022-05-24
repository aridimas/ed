---
layout: default
title: "Poems."
---

<div class="toc">
  <h1>Daftar Puisi</h1>
  <ul class="puisi">
  {% for item in site.puisi %}

    <li class="text-title">
      <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
      </a>
    </li>
  {% endfor %}
  </ul>
</div>
