---
title: "Jingwen Lab - Publications"
layout: gridlay
excerpt: "Jingwen Lab -- Publications."
sitemap: false
permalink: /publications/
---

# Publications

Jump to [Journal](#journal), [Conference Proceedings](#proceedings).

## Journal<a name="journal"></a>
{% mycounter = 0 %}
{% for publi in site.data.publist_journal %}

  {% mycounter = mycounter + 1 %}
  {{ mycounter }}. {{ publi.reference }} <br />
  
{% endfor %}

## Conference Proceedings<a name="proceedings"></a>
{% mycounter = 0 %}
{% for publi in site.data.publist_proceeding %}
  {{ publi.reference }} <br />
{% endfor %}
