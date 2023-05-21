---
title: Team
nav:
  order: 1
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

Our team is expanding! Please email azo2104@cumc.columbia.edu for opportunities to join.

{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}
{:.center}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: postdoc"
%}
{:.center}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
%}
{:.center}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad"
%}
{:.center}

{% include section.html background="images/banner.jpg" dark=true%}


{% include section.html %}

## Join

{% include section.html %}
