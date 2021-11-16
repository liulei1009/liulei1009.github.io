---
title: "Publications"
permalink: "/publications/"
layout: page
---

For a full list of publications go to [Google Scholar](https://scholar.google.com/citations?user=JqwKipIAAAAJ&hl=en), 
[ResearchGate](https://www.researchgate.net/profile/Liu-Lei-16), or [ORCID](https://orcid.org/0000-0002-1040-6026). {title: Mail, icon: envelope, url: "mailto:lei.liu@colorado.edu"}

### Selected Publications

{% for publi in site.data.publist %}

  * {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}



<!-- ###
<b style=\"color: #f45;\">&lt;3</b>
{title: Mail, icon: envelope, url: "mailto:lei.liu@colorado.edu"}

external:                  # shows a footer with social links - for available icons see fontawesome.com/icons
  - {title: Mail, icon: envelope, url: "mailto:lei.liu@colorado.edu"}
  - {title: Github, icon: github, url: "https://github.com/niklasbuschmann/contrast"}
  - {title: Researchgate, icon: researchgate, url: "https://www.researchgate.net/profile/Liu-Lei-16"}
  - {title: ORCID, icon: orcid, url: "https://orcid.org/0000-0002-1040-6026"}
  - {title: GOOGLE, icon: google, url: "https://scholar.google.com/citations?user=JqwKipIAAAAJ&hl=en"} -->
