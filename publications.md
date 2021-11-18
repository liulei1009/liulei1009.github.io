---
title: "Publications"
permalink: "/publications/"
layout: page
---

For a full list of publications go to [ResearchGate](https://www.researchgate.net/profile/Liu-Lei-16), [Google Scholar](https://scholar.google.com/citations?user=JqwKipIAAAAJ&hl=en), or [ORCID](https://orcid.org/0000-0002-1040-6026).

### Selected Publications

{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}
