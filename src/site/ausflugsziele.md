---
title: Ausflugsziele in der Nähe von Ladbergen
layout: layouts/base.njk
---

<iframe src="https://www.google.com/maps/d/u/0/embed?mid=1_IW4GF8CfEiT3CtQh6Bq8g1B1QlGUXtV&ehbc=2E312F" width="640" height="480"></iframe>

## Hofläden

<ul class="list-ausflugsziele">
{%- for ziel in alle_ausflugsziele -%}
  <li>
    {{ loop.index }}
    <strong>{{ ziel.properties.name }}</strong> - {{ ziel.properties.description }}
  </li>
{%- endfor -%}
</ul>
