---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We are located at Charité - Universitätsmedizin Berlin. 

{%
  include button.html
  type="email"
  text="livius.penter@charite.de"
  link="livius.penter@charite.de"
%}
{%
  include button.html
  type="phone"
  text="+49 30 450 553 192"
  link="+49 30 450 553 192"
%}
{%
  include button.html
  type="address"
  tooltip="Find us on googlemaps"
  link="[https://www.google.com/maps](https://goo.gl/maps/rKx5xR6niy4bjL7A9)"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
