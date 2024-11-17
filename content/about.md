---
title: About
description: |
  Le blog tech de onepoint est soutenu par Onepoint et propulsé par ()[Quarkus Roq]
layout: :theme/page
---

# À propos du blog tech de onepoint

Le blog tech de onepoint est soutenu par Onepoint et propulsé par [Quarkus Roq](https://github.com/quarkiverse/quarkus-roq) ❤️

## Authors

<div class="authors">
  <!-- authors.yml is in the data/ -->
  {#for id in cdi:authors.fields}
    {#let author=cdi:authors.get(id)}
    <!-- the author-card tag is defined in the default Roq theme -->
    {#author-card name=author.name avatar=author.avatar nickname=author.nickname profile=author.profile /}
  {/for}
</div>

