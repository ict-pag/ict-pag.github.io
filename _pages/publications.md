---
title: "ICT-PAG - Publications"
layout: gridlay
excerpt: "ICT-PAG -- Publications."
sitemap: false
permalink: /publications/
---


## Publications

Papers by ICT-PAG members (Since 2018)

<!-- ### 2024 -->

<!-- <h4 style='color: #148F77'>[Journal]</h4>

{% for publi in site.data.joulist_2024 %}

  <b>{{ publi.title }}</b> <br />
  {{ publi.authors }} <br />
  <em>{{ publi.venue }}</em> <br />
  <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
  <a href="{{ publi.code.url }}">{{ publi.code.display }}</a>

{% endfor %} -->

<!-- <h4 style='color: #148F77'>[Conference]</h4> -->

{% for publi in site.data.publist %}

  <b>{{ publi.title }}</b> <br />
  {{ publi.authors }} <br />
  <em>{{ publi.venue }}</em> <br />
  <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
  <a href="{{ publi.code.url }}">{{ publi.code.display }}</a>

{% endfor %}

