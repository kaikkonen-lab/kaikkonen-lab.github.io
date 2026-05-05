---
title: Projects
nav:
  order: 2
  tooltip: Ongoing and past research in the Kaikkonen Lab
---

<style>
.project-hero {
  padding: 4.5rem 2rem;
  border-radius: 28px;
  background:
    radial-gradient(circle at 20% 20%, rgba(0, 156, 170, 0.20), transparent 30%),
    radial-gradient(circle at 80% 10%, rgba(130, 80, 180, 0.18), transparent 35%),
    linear-gradient(135deg, #061b3a 0%, #0b355f 55%, #123f4c 100%);
  color: white;
  margin-bottom: 3rem;
  overflow: hidden;
  position: relative;
}

.project-hero h1 {
  font-size: clamp(2.3rem, 5vw, 4.8rem);
  line-height: 1.05;
  margin-bottom: 1rem;
  max-width: 900px;
}

.project-hero p {
  font-size: 1.2rem;
  max-width: 850px;
  color: rgba(255,255,255,0.88);
}

.research-flow {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  gap: 0.8rem;
  margin: 2.5rem 0 3.5rem;
}

.flow-step {
  background: #ffffff;
  border: 1px solid #dfe7ef;
  border-radius: 22px;
  padding: 1.2rem;
  text-align: center;
  box-shadow: 0 10px 28px rgba(10, 40, 70, 0.07);
}

.flow-step .icon {
  font-size: 2rem;
  margin-bottom: 0.6rem;
}

.flow-step strong {
  display: block;
  color: #08224a;
  margin-bottom: 0.35rem;
}

.flow-step span {
  color: #58708a;
  font-size: 0.92rem;
}

.project-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1.3rem;
  margin: 2rem 0 3rem;
}

.project-card {
  background: #ffffff;
  border: 1px solid #dce7f1;
  border-radius: 26px;
  padding: 1.6rem;
  box-shadow: 0 12px 35px rgba(8, 34, 74, 0.08);
  transition: transform 0.25s ease, box-shadow 0.25s ease;
}

.project-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 18px 45px rgba(8, 34, 74, 0.14);
}

.project-card h2 {
  margin-top: 0;
  color: #08224a;
}

.project-tag {
  display: inline-block;
  padding: 0.25rem 0.65rem;
  border-radius: 999px;
  background: #e8f4f6;
  color: #006d77;
  font-size: 0.82rem;
  font-weight: 700;
  margin-bottom: 0.9rem;
}

.project-card ul {
  padding-left: 1.1rem;
}

.project-card li {
  margin-bottom: 0.35rem;
}

.project-links {
  margin-top: 1rem;
  display: flex;
  flex-wrap: wrap;
  gap: 0.6rem;
}

.project-links a {
  text-decoration: none;
  padding: 0.55rem 0.85rem;
  border-radius: 999px;
  border: 1px solid #c9d8e6;
  color: #08224a;
  font-weight: 700;
  font-size: 0.9rem;
  background: #f7fbff;
}

.project-links a:hover {
  background: #08224a;
  color: white;
}

.past-projects {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 1rem;
  margin: 2rem 0 3rem;
}

.past-card {
  border-radius: 22px;
  padding: 1.2rem;
  background: linear-gradient(180deg, #ffffff 0%, #f4f8fb 100%);
  border: 1px solid #dfe7ef;
}

.past-card h3 {
  margin-top: 0;
  color: #08224a;
}

.vision-box {
  border-radius: 28px;
  padding: 2.2rem;
  color: white;
  background:
    linear-gradient(135deg, rgba(105, 23, 55, 0.95), rgba(6, 27, 58, 0.98)),
    radial-gradient(circle at top right, rgba(0, 180, 190, 0.35), transparent 35%);
  margin: 3rem 0;
}

.vision-box h2 {
  color: white;
  margin-top: 0;
}

.vision-path {
  font-size: 1.25rem;
  font-weight: 800;
  letter-spacing: 0.02em;
}

@media (max-width: 900px) {
  .research-flow,
  .project-grid,
  .past-projects {
    grid-template-columns: 1fr;
  }

  .project-hero {
    padding: 3rem 1.4rem;
  }
}
</style>

<div class="project-hero">

# Research Projects

The Kaikkonen Lab investigates how **genetic variation shapes cardiovascular disease mechanisms** and how this knowledge can be translated into better prediction, prevention, and treatment.

Our work connects **genetic discovery, functional genomics, single-cell and spatial biology, computational modelling, and translational medicine**.

</div>

## Research at a Glance

<div class="research-flow">

<div class="flow-step">
<div class="icon">🧬</div>
<strong>Genetic variation</strong>
<span>GWAS, loci, variants</span>
</div>

<div class="flow-step">
<div class="icon">🎯</div>
<strong>Causal prioritization</strong>
<span>fine-mapping, regulatory variants</span>
</div>

<div class="flow-step">
<div class="icon">🔬</div>
<strong>Functional mechanisms</strong>
<span>MPRA, CRISPR, enhancers</span>
</div>

<div class="flow-step">
<div class="icon">🧫</div>
<strong>Cellular context</strong>
<span>single-cell and spatial omics</span>
</div>

<div class="flow-step">
<div class="icon">❤️</div>
<strong>Clinical translation</strong>
<span>risk, mechanisms, therapy</span>
</div>

</div>

---

## Ongoing Research Programs

<div class="project-grid">

<div class="project-card" id="miracle">
<span class="project-tag">Ongoing · 2023–2027</span>

## MIRACLE

MIRACLE focuses on understanding how genetic risk contributes to cardiovascular disease mechanisms and disease progression.

**Scientific focus**

- genetic risk interpretation  
- causal variant discovery  
- multi-omics integration  
- pathway-level mechanisms  
- cardiovascular risk prediction  

<div class="project-links">
<a href="https://uefconnect.uef.fi/en/minna.kaikkonen-maatta/" target="_blank">Minna’s UEF profile</a>
<a href="#finemapping">Fine-mapping</a>
<a href="#multimodal">Translation</a>
</div>

</div>

<div class="project-card" id="secret">
<span class="project-tag">ERC project</span>

## SECRET

SECRET aims to functionally dissect causal regulatory variants in atherosclerotic cardiovascular disease.

**Scientific focus**

- non-coding disease variants  
- CRISPRi and CRISPRa perturbations  
- endothelial and smooth muscle cell models  
- enhancer-to-gene regulation  
- disease-relevant regulatory networks  

<div class="project-links">
<a href="https://uefconnect.uef.fi/en/cardiovascular-genomics-kaikkonen-lab/" target="_blank">Lab research profile</a>
<a href="#regulation">Gene regulation</a>
<a href="#singlecell">Cellular context</a>
</div>

</div>

<div class="project-card" id="singlecell">
<span class="project-tag">Single-cell · Spatial biology</span>

## Single-Cell and Spatial Genomics

This research direction maps cardiovascular disease at cell-type and spatial resolution.

**Scientific focus**

- single-cell RNA-seq  
- single-cell ATAC-seq and multiome  
- spatial transcriptomics  
- disease-associated cell states  
- spatial organization of vascular pathology  

<div class="project-links">
<a href="https://uefconnect.uef.fi/en/cardiovascular-genomics-kaikkonen-lab/" target="_blank">Research group</a>
<a href="#multimodal">Multimodal integration</a>
</div>

</div>

<div class="project-card" id="finemapping">
<span class="project-tag">Variant-to-function</span>

## Functional Fine-Mapping of GWAS Variants

This project area translates statistical disease associations into experimentally testable biological mechanisms.

**Scientific focus**

- GWAS locus interpretation  
- causal variant prioritization  
- MPRA-based enhancer testing  
- CRISPR-based validation  
- target gene mapping  

<div class="project-links">
<a href="#secret">SECRET</a>
<a href="#regulation">Enhancer biology</a>
<a href="#miracle">MIRACLE</a>
</div>

</div>

<div class="project-card" id="multimodal">
<span class="project-tag">Computational · Translational</span>

## Multimodal Approaches for Translational Cardiovascular Genomics

This emerging direction integrates molecular, cellular, spatial, genetic, and clinical data to connect mechanism with phenotype.

**Scientific focus**

- genomics and epigenomics  
- transcriptomics and spatial data  
- clinical data integration  
- machine learning and computational modelling  
- mechanism-aware prediction  

<div class="project-links">
<a href="https://uefconnect.uef.fi/en/minna.kaikkonen-maatta/" target="_blank">UEF profile</a>
<a href="#singlecell">Single-cell data</a>
<a href="#miracle">Risk prediction</a>
</div>

</div>

<div class="project-card" id="regulation">
<span class="project-tag">Core biology</span>

## Gene Regulatory Mechanisms in Cardiovascular Disease

A central goal of the lab is to understand how regulatory elements, enhancers, and transcriptional programs control disease-relevant cellular phenotypes.

**Scientific focus**

- enhancer function  
- enhancer RNAs  
- chromatin regulation  
- inflammatory gene programs  
- variant-to-gene mechanisms  

<div class="project-links">
<a href="#secret">Regulatory variants</a>
<a href="#finemapping">Variant-to-function</a>
</div>

</div>

</div>

---

## Previous and Foundational Research

<div class="past-projects">

<div class="past-card">

### Enhancer Biology

Foundational work on enhancers and enhancer RNAs in transcriptional regulation and inflammatory gene expression.

</div>

<div class="past-card">

### Genomic Dissection of Atherosclerosis

Application of next-generation sequencing technologies to identify regulatory mechanisms in cardiovascular disease.

</div>

<div class="past-card">

### Polygenic Disease Architecture

Research linking genetic variation, disease-associated cell states, and heritability in cardiovascular disease.

</div>

<div class="past-card">

### Variant-to-Function Mapping

Development of frameworks connecting non-coding variants to regulatory elements, target genes, and disease mechanisms.

</div>

</div>

<div class="vision-box">

## Research Vision

<div class="vision-path">
Genetic variation → Regulatory function → Cellular mechanisms → Disease biology → Clinical translation
</div>

<br>

The long-term goal of our research is to bridge the gap between genetic association and disease mechanism by combining experimental genomics, single-cell technologies, computational biology, and translational cardiovascular research.

</div>

---

## Explore More

{%
  include button.html
  icon="fa-solid fa-user-group"
  text="Meet the team"
  link="team"
  style="button"
%}

{%
  include button.html
  icon="fa-solid fa-envelope"
  text="Contact us"
  link="contact"
  style="button"
%}

{%
  include button.html
  icon="fa-solid fa-newspaper"
  text="Publications"
  link="publications"
  style="button"
%}
