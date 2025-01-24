---
title: Home
carousels:
  - images: 
    - image: /images/home/carousel/gastronomie_team.jpg
    - image: /images/home/carousel/labo_photo1.jpg
    - image: /images/home/carousel/photo.jpg
---


# The Menger Lab

Our team was the first in Europe to establish CRISPR-Cas9 screening in vivo in primary T cells, developing a functional pipeline for the unbiased and systematic characterization of T cell limiting factors in complex immunosuppressive environments. The team now integrates additional developments in synthetic biology using genome-wide CRISPR activation modification, editing of tumour-infiltrating lymphocytes, CAR combinatorial therapies and modulating epigenetic regulators of the antitumor immune response in vivo.


{% capture text %}
Laurie is an INSERM researcher and young group leader of the Advanced-T cell therapy team (U1015) at Gustave Roussy (GR), specialized in Onco/Immunobiotechnology. She has built her career on the use of multidisciplinary approaches to conduct immunotherapeutic projects leading to translational development. In 2019, she obtained financial support from the Agence Nationale de la Recherche Jeune chercheur (ANRJCJC) Grant and in 2021 received an ATIP-Avenir (starting package, INSERM) and Gustave Roussy starting package. Her research is also feeding 2 Flagship medico-scientific programs, the precision medicine program (PRISM) and the Innovative Therapeutics emerging program.

{%
  include link.html
  link="/members/lmenger"
  text="Learn More"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature2.html
  image="images/home/laurie_menger.jpeg"
  title="Dr. Laurie Menger"
  component="portrait"
  text=text
%}

{% include section.html full=true %}
{% include carousel.html height="40" unit="%" duration="10" number="1" %}


{% include section.html%}
# Highlights

{% capture text %}
We are developing the latest advances in T-cell engineering, genome-scale editing technologies, metabolic and single-cell profiling in a context of therapeutic adoptive transfer against cancer. 

{%
  include button.html
  link="publications"
  text="See what we've published"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}
{%
  include feature.html
  image="images/home/VtdLbwNS.jpeg"
  title="Biotechnology"
  text=text
%}

{% capture text %}
Our work focuses on the study of T cells biology in immunosuppressive environments through systematic and unbiased approaches to accelerate immunotherapeutic targets discovery. Our goal is to characterize the genes and essential parameters for the development of synthetic immunology providing a new class of effective, safe and affordable treatments for oncology.

{%
  include button.html
  link="research"
  text="See our highlighted resources"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/home/mrHvlPRY.jpeg"
  title="Cancer immunotherapy"
  flip=true
  text=text
%}

{% capture text %}
We use data science to answer important questions in biology and medicine.
In all of our research, we prioritize transparency, rigor, and reproducibility.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}
{%
  include feature.html
  image="images/home/nwDbPcKC.jpeg"
  title="Biology + AI → insight"
  text=text
%}

{% include section.html %}

# Our research group is funded by
{% include section.html dark=false full=false%}

{%
  include gallery.html
  style="square"

  image1="images/home/founding/Gustave-Roussy.jpg"

  image2="images/home/founding/logo-inserm.jpg"

  image3="images/home/founding/marie_curie.jpeg"
  
  image4="images/home/founding/ligue_contre_le_cancer.jpeg"
  
  image5="images/home/founding/atip.jpeg"
  
  image6="images/home/founding/logo_institut_national_du_cancer-400x400.png"
  
  image7="images/home/founding/u_paris_saclay.png"

  image8="images/home/founding/anr_logo.jpg"

  image9="images/home/founding/PKC_logo.png"
%}
{:.center}
