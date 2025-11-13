---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact


{%
  include button.html
  type="email"
  text="banabithi.bose@gmail.com"
  link=""
%}
{%
  include button.html
  type=""
  text=""
  link=""
%}
{%
  include button.html
  type=""
  tooltip=""
  link=""
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image=""
  caption=""
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image=""
  caption=""
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}

{% endcapture %}

{% capture col2 %}

{% endcapture %}

{% capture col3 %}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
