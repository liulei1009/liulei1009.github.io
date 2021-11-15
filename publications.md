---
title: "Publications"
permalink: "/publications/"
layout: page
---

Sharing knowledge is important to us, so we've linked some resources to help you learn how we do things in our lab. Feel free to borrow or adapt anything you like. 

(For a full list of publications see [below](#full-list-of-publications) or go to [Google Scholar](https://scholar.google.com/citations?user=JqwKipIAAAAJ&hl=en), 
[ResearchGate](https://www.researchgate.net/profile/Liu-Lei-16), [ORCID](https://orcid.org/0000-0002-1040-6026))

### Full List of publications

{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}
