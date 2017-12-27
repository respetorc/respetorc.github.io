---
layout: common
permalink: /noticias/repercusiones/
title: Repercusiones
---

## Televisión

## Radio

## Diarios

{% for repercusion in site.data.repercusiones %}
  {{ repercusion.plataforma }}
{% endfor %}
