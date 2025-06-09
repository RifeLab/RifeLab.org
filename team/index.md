---
title: Team
nav:
  order: 1
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role == 'pi'" %}
{% include list.html data="members" component="portrait" filters="role == 'programmer' and group != 'alum'" %}
{% include list.html data="members" component="portrait" filters="role == 'engineer' and group != 'alum'" %}
{% include list.html data="members" component="portrait" filters="role == 'postdoc' and group != 'alum'" %}
{% include list.html data="members" component="portrait" filters="role == 'phd' and group != 'alum'" %}
{% include list.html data="members" component="portrait" filters="role == 'undergrad' and group != 'alum'" %}
{% include list.html data="members" component="portrait" filters="role == 'highschool' and group != 'alum'" %}
{% include list.html data="members" component="portrait" filters="role == 'mascot' and group != 'alum'" %}

{% include section.html dark=true %}

We work with a wide range of outstanding groups from around the world, and we're always on the lookout for new and unique perspectives.

{%
  include button.html
  icon="fa-solid fa-handshake-angle"
  text="Join the Team"
  link="join"
  style="button"
%}

{% include section.html %}

## Alumni
{% include list.html data="members" component="portrait" filter="group == 'alum'" style="small"%}

{% include section.html %}