---
title: Software
nav:
  order: 4
  tooltip: Tools
---

# {% include icon.html icon="fa-solid fa-users" %}Software

Dr. Bose has developed multiple open-source computational frameworks to advance precision oncology and reproducible science. Her tools include **GXwasR**, for sex-aware genome-wide association studies; **miRDriver**, for identifying regulatory microRNA–gene interactions in cancer; **CTDPathSim** and **CTDpathSim2.0**, for prioritizing biologically relevant preclinical models that mirror patient tumors; and **PDDRNet-MH**, a multiplex heterogeneous network framework for predicting patient-specific drug responses. Each tool is accompanied by extensive documentation and tutorials, enabling transparent, reproducible multi-omics and pharmacogenomic analyses that bridge discovery and clinical translation.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}


{% include section.html %}

{% capture content %}

{% include figure.html image="images/icon.png" %}
{% include figure.html image="images/icon.png" %}
{% include figure.html image="images/icon.png" %}
{% include figure.html image="images/icon.png" %}
{% include figure.html image="images/icon.png" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
