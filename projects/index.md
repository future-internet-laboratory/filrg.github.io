---
title: Projects
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}**Projects**

## Looking for more?
Explore our latest software tools, open datasets, and research prototypes.  
From cloud computing to network security and immersive multimedia, these projects drive our mission forward.


{% include tags.html tags="library, software, dataset, resource" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
