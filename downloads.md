---
layout: page
title: Downloads
permalink: /downloads/
---
## Contabilidade
Arquivos disponibilizados pelo professor de Contabilidade.

{% assign path = site.baseurl | append: '/public/downloads/contabilidade/' %}

{% for file in site.data.files %}
[{{ file.title }}]({{ path | append: file.name }})
{% endfor %}