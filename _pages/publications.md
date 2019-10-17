---
title: "AliRec - Publications"
layout: gridlay
excerpt: "AliRec -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

## 2019 

{% for publi in site.data.publist19 %}

  <strong>{{ publi.title }}</strong> <br />
  <em>{{ publi.authors }} </em><br />
  <a href="{{ publi.link.url }}">{{ publi.link.display }}</a> {{ publi.news1 }}

{% endfor %}


## 2018

{% for publi in site.data.publist18 %}

  <strong>{{ publi.title }}</strong> <br />
  <em>{{ publi.authors }} </em><br />
  <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>{{ publi.news1 }}

{% endfor %}