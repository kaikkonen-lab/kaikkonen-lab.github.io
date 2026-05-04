---
---

<div class="hero-block">
  <img src="{{ '/images/cadgen_logo.png' | relative_url }}" alt="Kaikkonen Lab background" class="hero-img">

  <div class="hero-overlay"></div>

  <div class="hero-content">
    <p class="hero-kicker">Cardiovascular Genomics • Epigenomics • Gene Regulation</p>
    <h1>Kaikkonen Lab</h1>
    <p class="hero-subtitle">
      Investigating how genetic and epigenomic regulatory mechanisms shape cardiovascular disease risk.
    </p>
  </div>
</div>

# Cardiovascular Epigenomics and Gene Regulation

The Kaikkonen Lab investigates the molecular and genetic mechanisms underlying atherosclerotic cardiovascular disease and cardiometabolic disorders. We combine cellular and genetic model systems, single-cell transcriptomics, epigenomics, high-throughput functional genomics, and computational biology to understand how gene regulation shapes cardiovascular disease risk.

Our work focuses especially on the functional interpretation of non-coding GWAS variants. Using massively parallel reporter assays, CRISPR/Cas9 perturbation, cellular models, and multi-omics analysis, we aim to connect disease-associated genetic variation to regulatory mechanisms, cell states, and biological function.

The lab also hosts a single-cell genomics core and develops integrative approaches for single-cell multiomics and spatial transcriptomics.

{% include section.html %}

## Our vision and mission

> ##### “Science and everyday life cannot and should not be separated.”  
> *— Rosalind Franklin*

{% include section.html %}

{% capture text %}

We study cardiovascular disease mechanisms through functional genomics, gene regulation, epigenomics, and variant interpretation.

{%
  include button.html
  link="research"
  text="Explore our research"
  icon="fa-solid fa-arrow-right"
  flip=true
%}

{% endcapture %}

{%
  include feature.html
  image="images/publications.jpg"
  link="research"
  title="Research"
  text=text
%}

{% capture text %}

Our projects integrate experimental models, genomics technologies, computational methods, and disease-focused biological questions.

{%
  include button.html
  link="projects"
  text="Browse projects"
  icon="fa-solid fa-arrow-right"
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

We are an interdisciplinary team working across cardiovascular biology, functional genomics, single-cell technologies, and computational analysis.

{%
  include button.html
  link="team"
  text="Meet the team"
  icon="fa-solid fa-arrow-right"
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/team.jpg"
  link="team"
  title="Team"
  text=text
%}
