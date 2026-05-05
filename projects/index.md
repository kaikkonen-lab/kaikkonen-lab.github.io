---
title: Projects
nav:
  order: 2
  tooltip: Ongoing and past research in the Kaikkonen Lab
---

<style>
.research-hero {
  padding: 3.2rem 2rem;
  border-radius: 24px;
  background: linear-gradient(135deg, #06264f 0%, #0b5570 55%, #0a3f46 100%);
  color: white;
  margin: 1rem 0 2.5rem 0;
}

.research-hero h1 {
  color: white;
  font-size: 3rem;
  margin: 0 0 1rem 0;
}

.research-hero p {
  max-width: 900px;
  font-size: 1.15rem;
  line-height: 1.7;
  margin: 0;
  color: rgba(255, 255, 255, 0.92);
}

.research-pathway {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  gap: 0.9rem;
  margin: 2rem 0 3rem 0;
}

.pathway-item {
  background: #ffffff;
  border: 1px solid #dbe7ef;
  border-radius: 18px;
  padding: 1.1rem;
  text-align: center;
  box-shadow: 0 8px 24px rgba(10, 40, 70, 0.08);
}

.pathway-icon {
  font-size: 2rem;
  margin-bottom: 0.5rem;
}

.pathway-item strong {
  display: block;
  color: #08224a;
  margin-bottom: 0.3rem;
}

.pathway-item span {
  color: #5c7085;
  font-size: 0.9rem;
}

.project-card {
  border: 1px solid #dbe7ef;
  border-radius: 22px;
  padding: 1.6rem;
  margin: 1.4rem 0;
  background: linear-gradient(180deg, #ffffff 0%, #f8fbfd 100%);
  box-shadow: 0 10px 28px rgba(8, 34, 74, 0.07);
}

.project-card h2 {
  margin-top: 0;
  color: #08224a;
}

.project-label {
  display: inline-block;
  padding: 0.25rem 0.7rem;
  border-radius: 999px;
  background: #e6f4f4;
  color: #006d77;
  font-size: 0.82rem;
  font-weight: 700;
  margin-bottom: 0.7rem;
}

.project-links {
  margin-top: 1rem;
}

.project-links a {
  display: inline-block;
  margin: 0.25rem 0.35rem 0.25rem 0;
  padding: 0.5rem 0.8rem;
  border-radius: 999px;
  border: 1px solid #cbdbe8;
  background: #ffffff;
  color: #08224a;
  text-decoration: none;
  font-weight: 700;
  font-size: 0.9rem;
}

.project-links a:hover {
  background: #08224a;
  color: white;
}

.foundational-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 1rem;
  margin: 1.5rem 0 2.5rem 0;
}

.foundation-card {
  padding: 1.3rem;
  border-radius: 18px;
  background: #ffffff;
  border: 1px solid #dbe7ef;
  box-shadow: 0 8px 22px rgba(8, 34, 74, 0.06);
}

.foundation-card h3 {
  margin-top: 0;
  color: #08224a;
}

.vision-box {
  border-radius: 24px;
  padding: 2rem;
  background: linear-gradient(135deg, #691737 0%, #08224a 100%);
  color: white;
  margin: 2.5rem 0;
}

.vision-box h2 {
  color: white;
  margin-top: 0;
}

.vision-path {
  font-size: 1.2rem;
  font-weight: 800;
  line-height: 1.8;
}

@media (max-width: 900px) {
  .research-pathway,
  .foundational-grid {
    grid-template-columns: 1fr;
  }

  .research-hero h1 {
    font-size: 2.2rem;
  }
}
</style>

<div class="research-hero">
  <h1>Research Projects</h1>
  <p>
    The Kaikkonen Lab investigates how genetic variation shapes cardiovascular disease mechanisms and how this knowledge can be translated into better prediction, prevention, and treatment. Our work connects genetic discovery, functional genomics, single-cell and spatial biology, computational modelling, and translational medicine.
  </p>
</div>

## Research at a Glance

<div class="research-pathway">
  <div class="pathway-item">
    <div class="pathway-icon">🧬</div>
    <strong>Genetic Variation</strong>
    <span>GWAS, loci, variants</span>
  </div>

  <div class="pathway-item">
    <div class="pathway-icon">🎯</div>
    <strong>Causal Prioritization</strong>
    <span>fine-mapping and regulatory variants</span>
  </div>

  <div class="pathway-item">
    <div class="pathway-icon">🔬</div>
    <strong>Functional Mechanisms</strong>
    <span>MPRA, CRISPR, enhancers</span>
  </div>

  <div class="pathway-item">
    <div class="pathway-icon">🧫</div>
    <strong>Cellular Context</strong>
    <span>single-cell and spatial omics</span>
  </div>

  <div class="pathway-item">
    <div class="pathway-icon">❤️</div>
    <strong>Clinical Translation</strong>
    <span>risk, mechanisms, therapy</span>
  </div>
</div>

---

## Ongoing Research Programs

<div class="project-card" id="miracle">
  <span class="project-label">Ongoing · 2023–2027</span>
  <h2>MIRACLE</h2>
  <p>
    MIRACLE focuses on understanding how genetic risk contributes to cardiovascular disease mechanisms and disease progression.
  </p>

  <p><strong>Scientific focus:</strong></p>
  <ul>
    <li>genetic risk interpretation</li>
    <li>causal variant discovery</li>
    <li>multi-omics integration</li>
    <li>pathway-level mechanisms</li>
    <li>cardiovascular risk prediction</li>
  </ul>

  <div class="project-links">
    <a href="https://uefconnect.uef.fi/en/minna.kaikkonen-maatta/" target="_blank">Minna’s UEF profile</a>
    <a href="#finemapping">Fine-mapping</a>
    <a href="#multimodal">Translation</a>
  </div>
</div>

<div class="project-card" id="secret">
  <span class="project-label">ERC project</span>
  <h2>SECRET</h2>
  <p>
    SECRET aims to functionally dissect causal regulatory variants in atherosclerotic cardiovascular disease.
  </p>

  <p><strong>Scientific focus:</strong></p>
  <ul>
    <li>non-coding disease variants</li>
    <li>CRISPRi and CRISPRa perturbations</li>
    <li>endothelial and smooth muscle cell models</li>
    <li>enhancer-to-gene regulation</li>
    <li>disease-relevant regulatory networks</li>
  </ul>

  <div class="project-links">
    <a href="https://uefconnect.uef.fi/en/cardiovascular-genomics-kaikkonen-lab/" target="_blank">Lab research profile</a>
    <a href="#regulation">Gene regulation</a>
    <a href="#singlecell">Cellular context</a>
  </div>
</div>

<div class="project-card" id="singlecell">
  <span class="project-label">Single-cell · Spatial biology</span>
  <h2>Single-Cell and Spatial Genomics</h2>
  <p>
    This research direction maps cardiovascular disease at cell-type and spatial resolution.
  </p>

  <p><strong>Scientific focus:</strong></p>
  <ul>
    <li>single-cell RNA-seq</li>
    <li>single-cell ATAC-seq and multiome</li>
    <li>spatial transcriptomics</li>
    <li>disease-associated cell states</li>
    <li>spatial organization of vascular pathology</li>
  </ul>

  <div class="project-links">
    <a href="https://uefconnect.uef.fi/en/cardiovascular-genomics-kaikkonen-lab/" target="_blank">Research group</a>
    <a href="#multimodal">Multimodal integration</a>
  </div>
</div>

<div class="project-card" id="finemapping">
  <span class="project-label">Variant-to-function</span>
  <h2>Functional Fine-Mapping of GWAS Variants</h2>
  <p>
    This project area translates statistical disease associations into experimentally testable biological mechanisms.
  </p>

  <p><strong>Scientific focus:</strong></p>
  <ul>
    <li>GWAS locus interpretation</li>
    <li>causal variant prioritization</li>
    <li>MPRA-based enhancer testing</li>
    <li>CRISPR-based validation</li>
    <li>target gene mapping</li>
  </ul>

  <div class="project-links">
    <a href="#secret">SECRET</a>
    <a href="#regulation">Enhancer biology</a>
    <a href="#miracle">MIRACLE</a>
  </div>
</div>

<div class="project-card" id="multimodal">
  <span class="project-label">Computational · Translational</span>
  <h2>Multimodal Approaches for Translational Cardiovascular Genomics</h2>
  <p>
    This emerging direction integrates molecular, cellular, spatial, genetic, and clinical data to connect mechanism with phenotype.
  </p>

  <p><strong>Scientific focus:</strong></p>
  <ul>
    <li>genomics and epigenomics</li>
    <li>transcriptomics and spatial data</li>
    <li>clinical data integration</li>
    <li>machine learning and computational modelling</li>
    <li>mechanism-aware prediction</li>
  </ul>

  <div class="project-links">
    <a href="https://uefconnect.uef.fi/en/minna.kaikkonen-maatta/" target="_blank">UEF profile</a>
    <a href="#singlecell">Single-cell data</a>
    <a href="#miracle">Risk prediction</a>
  </div>
</div>

<div class="project-card" id="regulation">
  <span class="project-label">Core biology</span>
  <h2>Gene Regulatory Mechanisms in Cardiovascular Disease</h2>
  <p>
    A central goal of the lab is to understand how regulatory elements, enhancers, and transcriptional programs control disease-relevant cellular phenotypes.
  </p>

  <p><strong>Scientific focus:</strong></p>
  <ul>
    <li>enhancer function</li>
    <li>enhancer RNAs</li>
    <li>chromatin regulation</li>
    <li>inflammatory gene programs</li>
    <li>variant-to-gene mechanisms</li>
  </ul>

  <div class="project-links">
    <a href="#secret">Regulatory variants</a>
    <a href="#finemapping">Variant-to-function</a>
  </div>
</div>

---

## Previous and Foundational Research

<div class="foundational-grid">
  <div class="foundation-card">
    <h3>Enhancer Biology</h3>
    <p>
      Foundational work on enhancers and enhancer RNAs in transcriptional regulation and inflammatory gene expression.
    </p>
  </div>

  <div class="foundation-card">
    <h3>Genomic Dissection of Atherosclerosis</h3>
    <p>
      Application of next-generation sequencing technologies to identify regulatory mechanisms in cardiovascular disease.
    </p>
  </div>

  <div class="foundation-card">
    <h3>Polygenic Disease Architecture</h3>
    <p>
      Research linking genetic variation, disease-associated cell states, and heritability in cardiovascular disease.
    </p>
  </div>

  <div class="foundation-card">
    <h3>Variant-to-Function Mapping</h3>
    <p>
      Development of frameworks connecting non-coding variants to regulatory elements, target genes, and disease mechanisms.
    </p>
  </div>
</div>

<div class="vision-box">
  <h2>Research Vision</h2>
  <div class="vision-path">
    Genetic variation → Regulatory function → Cellular mechanisms → Disease biology → Clinical translation
  </div>
  <p>
    The long-term goal of our research is to bridge the gap between genetic association and disease mechanism by combining experimental genomics, single-cell technologies, computational biology, and translational cardiovascular research.
  </p>
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
