---
title: "Publications"
permalink: "/publications/"
layout: page
---

Sharing knowledge is important to us, so we've linked some resources to help you learn how we do things in our lab. Feel free to borrow or adapt anything you like. 

(For a full list of publications see [below](#full-list-of-publications) or go to [Google Scholar](https://scholar.google.com/citations?user=JqwKipIAAAAJ&hl=en), 
[ResearchGate](https://www.researchgate.net/profile/Liu-Lei-16), [ORCID](https://orcid.org/0000-0002-1040-6026))

### Websites and Wikis

Our website is hosted with [Github Pages](https://pages.github.com/) and uses the [constrast](https://github.com/niklasbuschmann/contrast) theme.  We also keep a [Lab Wiki](https://wiki.childlanglab.com/) including our [Lab Handbook](https://wiki.childlanglab.com/resources/lab-handbook), to keep track of how we do things and share with others. Feel free to use ours as a jumping off point to create your own.


### Data Analysis

We like to analyze data in Jupyter notebooks via [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/), which is kind of like RStudio. Here is a [JupyterLab demo](https://mybinder.org/v2/gh/jupyterlab/jupyterlab-demo/master?urlpath=lab/tree/demo) and below is some more information about our lab's workflow in case you'd like to borrow it: 

- [How to analyze data with the jupyter/datascience-notebook](2021-01-09-datascience-container)
- [How to customize the jupyter/datascience-notebook container](https://www.youtube.com/watch?v=UXxUcZDSNwA&feature=youtu.be&ab_channel=KathrynSchuler)


## Full List of publications

{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}
