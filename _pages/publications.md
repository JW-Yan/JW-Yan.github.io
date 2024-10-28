---
title: "Jingwen Lab - Publications"
layout: gridlay
excerpt: "Jingwen Lab -- Publications."
sitemap: false
permalink: /publications/
---

<br/>
<! -- Jump to [Journal](#journal), [Conference Proceedings](#proceedings). -->

<! -- ### Journal<a name="journal"></a> -->
### Peer reviewed 

[Complete list in Google scholar](https://scholar.google.com/citations?user=9ZIOjDQAAAAJ&hl=en)
<br/>

{% assign counter = 0 %}
{% for publi in site.data.publist_all %}
  {% assign counter = counter | plus: 1 %}
  {{ counter }}.  {{ publi.reference }} <br />
{% endfor %}

<! -- ### Conference Proceedings<a name="proceedings"></a>
{% assign counter = 0 %}
{% for publi in site.data.publist_proceeding %}
  {% assign counter = counter | plus: 1 %}
  {{ counter }}.  {{ publi.reference }} <br />
{% endfor %}
-->
