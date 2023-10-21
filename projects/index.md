---
title: Projects
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

{%
  include citation.html
  lookup="doi:10.1158/2159-8290.CD-21-0276"
  style="rich"
%}

{%
  include citation.html
  lookup="doi:10.1158/0008-5472.CAN-22-0275"
  style="rich"
%}




## Featured

{% include list.html component="card" data="projects" filters="group: featured" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filters="group: " style="small" %}
