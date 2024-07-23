---
---

# bosebDESCRIPTION=Dr. Banabithi Bose is a postdoctoral research scientist in the Department of Genetic Medicine, at Northwestern University, Chicago, IL. She completed her Ph.D. from Marquette University, Milwaukee, WI under the supervision of Dr. Serdar Bozdag and currently working with Dr. Barbara Stranger  at Northwestern. Dr. Bose is in the field of interdisciplinary studies that applies mathematics, statistics, and computer science to actionable knowledge in computational genomics, bioinformatics, computational biology, and biomedical data science. The core objective of her research is to leverage the integration of genetic, genomic, epigenomic, and clinical datasets utilizing statistical genetics, artificial intelligence, and machine learning methods to pave the path toward personalized medicine models in complex diseases, such as cancer.



{% include section.html %}

## Highlights

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
