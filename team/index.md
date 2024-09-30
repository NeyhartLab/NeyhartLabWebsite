---
title: Team
nav:
  order: 1
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi, group: " %}
{% include list.html data="members" component="portrait" filters="role: technician, group: " %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: " %}
{% include list.html data="members" component="portrait" filters="role: phd, group: " %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: " %}
{% include list.html data="members" component="portrait" filters="role: intern, group: " %}
{% include list.html data="members" component="portrait" filters="role: mascot, group: " %}

{% include section.html background="images/backgrounds/background-extra.jpg" dark=true %}

We prize diversity in the expertise, perspectives, and interests of our research group. Interested in working with us? Click "Join the Team" below.

{%
  include button.html
  icon="fa-solid fa-handshake-angle"
  text="Join the Team"
  link="join"
  style="button"
%}
{% include section.html %}


## Alumni

{% include list.html data="members" component="portrait" filters="role: pi, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: technician, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: phd, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: intern, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: mascot, group: alum" style="small" %}

{% include section.html %}