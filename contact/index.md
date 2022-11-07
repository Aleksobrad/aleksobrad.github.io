---
title: Contact
nav:
  order: 4
  tooltip: Email, address, and location
---

# <i class="fas fa-envelope"></i>Contact

Our lab is part of the [Department of Medicine](), at the [Columbia University Irving Medical Center]().
We are located on the 9th floor of the [Herbert Irving Cancer Research Center]().

{%
  include link.html
  type="email"
  icon=""
  text="azo2104@cumc.columbia.edu"
  tooltip=""
  link="azo2104@cumc.columbia.edu"
  style="button"
%}
{:.center}
{%
  include link.html
  type="address"
  icon=""
  text="Google Maps"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/The+Herbert+Irving+Comprehensive+Cancer+Center/@40.8409651,-73.9433855,15z/data=!4m2!3m1!1s0x0:0x30e7341a8bf900d6?sa=X&ved=2ahUKEwjD-9DI_5v7AhXdl4kEHRjIDPYQ_BJ6BAhqEAU"
  style="button"
%}
{:.center}

{% include section.html %}

{% capture col1 %}
{%
  include figure.html
  image=["images/ColumbiaUniversityMedicalCenter.jpeg"]
  caption="Columbia University Irving Medical Center"
%}
{% endcapture %}
{% capture col2 %}
{%
  include figure.html
  image=["images/medicine.gif"]
  caption="Department of Medicine"
%}
{% endcapture %}
{% include two-col.html col1=col1 col2=col2 %}
