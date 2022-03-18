---
title: "Jingwen Lab - Publications"
layout: gridlay
excerpt: "Jingwen Lab -- Publications."
sitemap: false
permalink: /publications/
---

<br/>
Jump to [Journal](#journal), [Conference Proceedings](#proceedings).

## Journal<a name="journal"></a>
{% assign counter = 0 %}
{% for publi in site.data.publist_journal %}
  {% assign counter = counter | plus: 1 %}
  {{ counter }}.  {{ publi.reference }} <br />
{% endfor %}

## Conference Proceedings<a name="proceedings"></a>
{% assign counter = 0 %}
{% for publi in site.data.publist_proceeding %}
  {% assign counter = counter | plus: 1 %}
  {{ counter }}.  {{ publi.reference }} <br />
{% endfor %}
