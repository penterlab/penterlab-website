---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We are hiring at all levels (technician, MD or PhD student, and postdoc)! 
Please reach out to Livius Penter ([livius.penter@charite.de](mailto:livius.penter@charite.de)) to get in touch.

You can find us in the heart of Berlin, Germany at beautiful 
[Campus Virchow Klinikum](https://www.charite.de/en/charite/campuses/campus_virchow_klinikum/)
of [Charité - Universitätsmedizin Berlin](https://www.charite.de/en/). 

AG Penter <br>
Medizinische Klinik m.S. Hämatologie, Onkologie und Tumorimmunologie<br>
Campus Virchow-Klinikum <br>
Augustenburger Platz 1<br>
13353 Berlin <br>
Germany

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
  link="https://goo.gl/maps/rKx5xR6niy4bjL7A9"
%}

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1586.317459022627!2d13.3442850192794!3d52.5417822486385!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47a8517966016ab1%3A0xb24e3e213b8bcc17!2sCharit%C3%A9%20Campus%20Virchow%20Clinic!5e0!3m2!1sen!2sus!4v1685825943258!5m2!1sen!2sus" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/CVK_spring.jpeg"
  caption="Campus Virchow Klinikum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/CVK_winter.jpeg"
  caption="Charité - Universitätsmedizin Berlin"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% comment %}

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
{% endcomment %}
