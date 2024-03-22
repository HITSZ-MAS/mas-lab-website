---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

## Teacher

{% include list.html data="members" component="portrait" filters="role: prof, alumni: false" %}
{% include list.html data="members" component="portrait" filters="role: ap, alumni: false" %}
{% include list.html data="members" component="portrait" filters="role: assocprof, alumni: false" %}


{% include section.html %}

## PhD Student

{% include list.html data="members" component="portrait" filters="role: phd, alumni: false" %}

{% include section.html %}

## Graduate Student

{% include list.html data="members" component="portrait" filters="role: graduate, alumni: false" %}

{% include section.html %}

## Alumni

{% include list.html data="members" component="portrait" filters="role: phd, alumni: true" %}
{% include list.html data="members" component="portrait" filters="role: graduate, alumni: true" %}

{% include section.html background="images/background.jpg" dark=true %}

{% include section.html %}

{% capture content %}

{% include figure.html image="images/maslab/maslab1.jpg" %}
{% include figure.html image="images/maslab/maslab2.jpg" %}
{% include figure.html image="images/maslab/maslab3.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
