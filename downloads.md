---
layout: page
title: Downloads
permalink: /downloads/
---
## Contabilidade
Arquivos disponibilizados pelo professor de Contabilidade.

{% assign path = site.baseurl %}
{% capture path %}"/public/downloads/contabilidade"{% endcapture %}

{% for file in site.data.files %}
[{{ file.title }}]({{ path | append: file.name }})
{% endfor %}