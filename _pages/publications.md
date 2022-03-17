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

{% for publi in site.data.publist %}
  {{ publi.title }} <br />
{% endfor %}

## Conference Proceedings<a name="proceedings"></a>
{% for publi in site.data.publist_proceeding %}
  {{ publi.reference }} <br />
{% endfor %}
