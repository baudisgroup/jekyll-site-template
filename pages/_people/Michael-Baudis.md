---
title: "Michael Baudis"
layout: default
excerpt_separator: <!--more-->
excerpt_link: https://info.baudisgroup.org/group/Michael_Baudis/
image_file: 'mbaudis.png'
author: mbaudis
categories:
  - people
  - contact
tags:
  - contacts
  - contributors
  - leads
  - developers
  - Discovery
  - Beacon
  - .featured
---

{% for static_file in site.static_files %}
  {% if static_file.path contains page.image_file %}
<img style="float: right; width: 80px;" src="{{ static_file.path | relative_url}}" />
  {% endif %}
{% endfor %}

## {{ page.title }}

Professor of Bioinformatics  
University of Zurich  
Swiss Institute of Bioinformatics  

<!--more-->

email [mbaudis@progenetix.org](mailto:mbaudis@progenetix.org)  
web [UZH](https://www.imls.uzh.ch/en/research/baudis.html)  
web [SIB](https://www.sib.swiss/michael-baudis-group)  
web [group](https://info.baudisgroup.org)  
