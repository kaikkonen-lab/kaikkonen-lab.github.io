---
title: Projects
nav:
  order: 2
  tooltip: Ongoing and past research in the Kaikkonen Lab
---

<style>
.projects-page {
  --navy: #06264f;
  --blue: #0b5f7a;
  --teal: #00a6a6;
  --mint: #e9f7f6;
  --berry: #7b1e4a;
  --ink: #102033;
  --muted: #5f7185;
  --line: #dce8ef;
  --soft: #f7fbfd;
}

.projects-hero {
  position: relative;
  overflow: hidden;
  padding: 4.5rem 2.2rem;
  border-radius: 32px;
  color: white;
  background:
    radial-gradient(circle at 15% 20%, rgba(0, 210, 190, 0.35), transparent 26%),
    radial-gradient(circle at 85% 15%, rgba(180, 60, 120, 0.30), transparent 28%),
    linear-gradient(135deg, #061a3a 0%, #083e67 48%, #0b5f62 100%);
  margin: 1rem 0 3rem;
}

.projects-hero::after {
  content: "";
  position: absolute;
  right: -120px;
  bottom: -140px;
  width: 420px;
  height: 420px;
  border-radius: 50%;
  border: 34px solid rgba(255,255,255,0.08);
}

.projects-hero h1 {
  position: relative;
  z-index: 1;
  color: white;
  font-size: clamp(2.4rem, 5vw, 5rem);
  line-height: 1.02;
  max-width: 920px;
  margin: 0 0 1.2rem;
}

.projects-hero p {
  position: relative;
  z-index: 1;
  max-width: 880px;
  font-size: 1.2rem;
  line-height: 1.75;
  color: rgba(255,255,255,0.92);
}

.hero-pills {
  position: relative;
  z-index: 1;
  display: flex;
  flex-wrap: wrap;
  gap: .7rem;
  margin-top: 1.6rem;
}

.hero-pills a {
  color: white;
  text-decoration: none;
  border: 1px solid rgba(255,255,255,0.35);
  background: rgba(255,255,255,0.12);
  padding: .55rem .9rem;
  border-radius: 999px;
  font-weight: 700;
}

.hero-pills a:hover {
  background: white;
  color: var(--navy);
}

.research-map {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  gap: 1rem;
  margin: 2rem 0 3rem;
}

.map-node {
  position: relative;
  padding: 1.25rem 1rem;
  border-radius: 24px;
  background: white;
  border: 1px solid var(--line);
  box-shadow: 0 12px 28px rgba(6, 38, 79, 0.08);
  text-align: center;
  transition: transform .25s ease, box-shadow .25s ease;
}

.map-node:hover {
  transform: translateY(-6px);
  box-shadow: 0 20px 42px rgba(6, 38, 79, 0.14);
}

.map-node .icon {
  font-size: 2.2rem;
  margin-bottom: .7rem;
}

.map-node h3 {
  font-size: 1rem;
  color: var(--navy);
  margin: 0 0 .35rem;
}

.map-node p {
  margin: 0;
  font-size: .9rem;
  color: var(--muted);
  line-height: 1.45;
}

.section-kicker {
  color: var(--teal);
  font-weight: 900;
  letter-spacing: .08em;
  text-transform: uppercase;
  font-size: .82rem;
  margin-top: 2.5rem;
}

.projects-heading {
  color: var(--navy);
  font-size: 2.2rem;
  margin: .3rem 0 1rem;
}

.project-stack {
  display: grid;
  gap: 1.4rem;
  margin: 1.5rem 0 3rem;
}

.project-feature {
  display: grid;
  grid-template-columns: 0.85fr 1.4fr;
  gap: 1.4rem;
  align-items: stretch;
  border: 1px solid var(--line);
  border-radius: 30px;
  background: white;
  box-shadow: 0 14px 34px rgba(6, 38, 79, 0.08);
  overflow: hidden;
}

.project-symbol {
  display: flex;
  align-items: center;
  justify-content: center;
  min-height: 260px;
  background:
    radial-gradient(circle at 30% 25%, rgba(0, 166, 166, .22), transparent 32%),
    linear-gradient(145deg, #f3fbfb, #eef4fb);
}

.symbol-orbit {
  width: 170px;
  height: 170px;
  border: 3px solid rgba(11, 95, 122, .25);
  border-radius: 50%;
  position: relative;
}

.symbol-orbit::before {
  content: "";
  position: absolute;
  inset: 34px;
  border-radius: 50%;
  border: 3px dashed rgba(123, 30, 74, .35);
}

.symbol-orbit::after {
  content: "♥";
  position: absolute;
  inset: 50px;
  border-radius: 50%;
  background: linear-gradient(135deg, var(--berry), #b43b6b);
  color: white;
  font-size: 3rem;
  display: flex;
  align-items: center;
  justify-content: center;
}

.project-body {
  padding: 1.8rem;
}

.project-tag {
  display: inline-block;
  color: #006d77;
  background: var(--mint);
  padding: .3rem .75rem;
  border-radius: 999px;
  font-size: .82rem;
  font-weight: 900;
  margin-bottom: .7rem;
}

.project-body h2 {
  color: var(--navy);
  font-size: 1.8rem;
  margin: 0 0 .7rem;
}

.project-body p {
  color: var(--ink);
  line-height: 1.7;
}

.focus-list {
  display: flex;
  flex-wrap: wrap;
  gap: .5rem;
  margin: 1rem 0;
}

.focus-list span {
  background: var(--soft);
  border: 1px solid var(--line);
  color: var(--navy);
  padding: .45rem .7rem;
  border-radius: 999px;
  font-weight: 700;
  font-size: .9rem;
}

.project-actions {
  margin-top: 1rem;
}

.project-actions a {
  display: inline-block;
  margin: .25rem .35rem .25rem 0;
  padding: .55rem .9rem;
  border-radius: 999px;
  text-decoration: none;
  background: var(--navy);
  color: white;
  font-weight: 800;
  font-size: .9rem;
}

.project-actions a.secondary {
  background: white;
  color: var(--navy);
  border: 1px solid var(--line);
}

.project-actions a:hover {
  background: var(--teal);
  color: white;
}

.foundation-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 1rem;
  margin: 1.5rem 0 3rem;
}

.foundation-card {
  border-radius: 24px;
  padding: 1.3rem;
  background: linear-gradient(180deg, white, #f7fbfd);
  border: 1px solid var(--line);
  box-shadow: 0 10px 26px rgba(6, 38, 79, 0.06);
}

.foundation-card h3 {
  color: var(--navy);
  margin-top: 0;
}

.foundation-card p {
  color: var(--muted);
  line-height: 1.6;
}

.vision-panel {
  padding: 2.4rem;
  border-radius: 30px;
  color: white;
  background:
    radial-gradient(circle at 85% 20%, rgba(0, 200, 190, .30), transparent 32%),
    linear-gradient(135deg, #68153d, #061b3a 72%);
  margin: 3rem 0;
}

.vision-panel h2 {
  color: white;
  margin-top: 0;
  font-size: 2rem;
}

.vision-route {
  font-size: 1.25rem;
  font-weight: 900;
  line-height: 1.8;
  margin: 1rem 0;
}

.bottom-actions {
  display: flex;
  flex-wrap: wrap;
  gap: .8rem;
  margin: 2rem 0;
}

.bottom-actions a {
  background: var(--navy);
  color: white;
  text-decoration: none;
  padding: .75rem 1.05rem;
  border-radius: 999px;
  font-weight: 800;
}

.bottom-actions a:hover {
  background: var(--teal);
}

@media (max-width: 950px) {
  .research-map,
  .foundation-grid {
    grid-template-columns: 1fr;
  }

  .project-feature {
    grid-template-columns: 1fr;
  }

  .project-symbol {
    min-height: 190px;
  }
}
</style>

<div class="projects-page">

<section class="projects-hero">
  <h1>From genetic discovery to cardiovascular disease mechanisms</h1>
  <p>
    The Kaikkonen Lab investigates how genetic variation, regulatory elements, cellular states, and tissue context shape atherosclerotic cardiovascular disease. The research program connects functional genomics, single-cell and spatial biology, computational modelling, and translational cardiovascular medicine.
  </p>

  <div class="hero-pills">
    <a href="#miracle">MIRACLE</a>
    <a href="#secret">SECRET</a>
    <a href="#singlecell">Single-cell & spatial genomics</a>
    <a href="#finemapping">Functional fine-mapping</a>
    <a href="#multimodal">Multimodal translation</a>
  </div>
</section>

<div class="section-kicker">Research logic</div>
<div class="projects-heading">A connected discovery pipeline</div>

<div class="research-map">
  <div class="map-node">
    <div class="icon">🧬</div>
    <h3>Genetic variation</h3>
    <p>GWAS loci, disease-associated variants, and inherited risk.</p>
  </div>

  <div class="map-node">
    <div class="icon">🎯</div>
    <h3>Causal prioritization</h3>
    <p>Fine-mapping and prioritization of regulatory variants.</p>
  </div>

  <div class="map-node">
    <div class="icon">🔬</div>
    <h3>Functional mechanisms</h3>
    <p>MPRA, CRISPR perturbation, enhancers, and target genes.</p>
  </div>

  <div class="map-node">
    <div class="icon">🧫</div>
    <h3>Cellular context</h3>
    <p>Single-cell, multiome, and spatial disease-state mapping.</p>
  </div>

  <div class="map-node">
    <div class="icon">❤️</div>
    <h3>Translation</h3>
    <p>Mechanism-aware prediction and cardiovascular disease biology.</p>
  </div>
</div>

<div class="section-kicker">Ongoing programs</div>
<div class="projects-heading">Current research projects</div>

<div class="project-stack">

  <section class="project-feature" id="miracle">
    <div class="project-symbol">
      <div class="symbol-orbit"></div>
    </div>
    <div class="project-body">
      <span class="project-tag">Ongoing · 2023–2027</span>
      <h2>MIRACLE</h2>
      <p>
        MIRACLE focuses on understanding how genetic risk contributes to cardiovascular disease mechanisms and disease progression. The project integrates genetic, functional, and multi-omics data to identify causal variants, regulatory mechanisms, and pathways that shape cardiovascular risk.
      </p>
      <div class="focus-list">
        <span>genetic risk</span>
        <span>causal variants</span>
        <span>multi-omics</span>
        <span>pathways</span>
        <span>risk prediction</span>
      </div>
      <div class="project-actions">
        <a href="https://uefconnect.uef.fi/en/minna.kaikkonen-maatta/" target="_blank">Learn more</a>
        <a class="secondary" href="#finemapping">Related: fine-mapping</a>
      </div>
    </div>
  </section>

  <section class="project-feature" id="secret">
    <div class="project-symbol">
      <div class="symbol-orbit"></div>
    </div>
    <div class="project-body">
      <span class="project-tag">ERC-funded project</span>
      <h2>SECRET</h2>
      <p>
        SECRET aims to functionally dissect causal regulatory variants in atherosclerotic cardiovascular disease. The project connects non-coding disease variants to enhancer activity, target genes, cellular phenotypes, and disease-relevant regulatory networks.
      </p>
      <div class="focus-list">
        <span>non-coding variants</span>
        <span>CRISPRi/a</span>
        <span>endothelial cells</span>
        <span>smooth muscle cells</span>
        <span>regulatory networks</span>
      </div>
      <div class="project-actions">
        <a href="https://uefconnect.uef.fi/en/cardiovascular-genomics-kaikkonen-lab/" target="_blank">Lab profile</a>
        <a class="secondary" href="#regulation">Related: gene regulation</a>
      </div>
    </div>
  </section>

  <section class="project-feature" id="singlecell">
    <div class="project-symbol">
      <div class="symbol-orbit"></div>
    </div>
    <div class="project-body">
      <span class="project-tag">Single-cell · Spatial biology</span>
      <h2>Single-cell and spatial genomics</h2>
      <p>
        This research direction maps cardiovascular disease at cell-type and spatial resolution, identifying disease-associated cell states, regulatory programs, and spatial tissue organization in vascular pathology.
      </p>
      <div class="focus-list">
        <span>scRNA-seq</span>
        <span>scATAC-seq</span>
        <span>multiome</span>
        <span>spatial transcriptomics</span>
        <span>cell states</span>
      </div>
      <div class="project-actions">
        <a href="https://uefconnect.uef.fi/en/cardiovascular-genomics-kaikkonen-lab/" target="_blank">Research group</a>
        <a class="secondary" href="#multimodal">Related: multimodal integration</a>
      </div>
    </div>
  </section>

  <section class="project-feature" id="finemapping">
    <div class="project-symbol">
      <div class="symbol-orbit"></div>
    </div>
    <div class="project-body">
      <span class="project-tag">Variant-to-function</span>
      <h2>Functional fine-mapping of GWAS variants</h2>
      <p>
        This project area translates statistical disease associations into experimentally testable biological mechanisms by identifying causal regulatory elements, target genes, and functional effects of non-coding variants.
      </p>
      <div class="focus-list">
        <span>GWAS interpretation</span>
        <span>fine-mapping</span>
        <span>MPRA</span>
        <span>CRISPR validation</span>
        <span>target genes</span>
      </div>
      <div class="project-actions">
        <a href="#secret">Related: SECRET</a>
        <a class="secondary" href="#regulation">Related: enhancer biology</a>
      </div>
    </div>
  </section>

  <section class="project-feature" id="multimodal">
    <div class="project-symbol">
      <div class="symbol-orbit"></div>
    </div>
    <div class="project-body">
      <span class="project-tag">Computational · Translational</span>
      <h2>Multimodal translational cardiovascular genomics</h2>
      <p>
        This emerging direction integrates molecular, cellular, spatial, genetic, and clinical data to connect disease mechanisms with phenotype and support mechanism-aware prediction.
      </p>
      <div class="focus-list">
        <span>genomics</span>
        <span>epigenomics</span>
        <span>spatial data</span>
        <span>clinical integration</span>
        <span>machine learning</span>
      </div>
      <div class="project-actions">
        <a href="https://uefconnect.uef.fi/en/minna.kaikkonen-maatta/" target="_blank">UEF profile</a>
        <a class="secondary" href="#singlecell">Related: single-cell data</a>
      </div>
    </div>
  </section>

  <section class="project-feature" id="regulation">
    <div class="project-symbol">
      <div class="symbol-orbit"></div>
    </div>
    <div class="project-body">
      <span class="project-tag">Core biology</span>
      <h2>Gene regulatory mechanisms in cardiovascular disease</h2>
      <p>
        A central goal of the lab is to understand how regulatory elements, enhancers, enhancer RNAs, chromatin programs, and transcriptional networks control disease-relevant cellular phenotypes.
      </p>
      <div class="focus-list">
        <span>enhancers</span>
        <span>eRNAs</span>
        <span>chromatin regulation</span>
        <span>inflammation</span>
        <span>variant-to-gene mechanisms</span>
      </div>
      <div class="project-actions">
        <a href="#secret">Related: regulatory variants</a>
        <a class="secondary" href="#finemapping">Related: variant-to-function</a>
      </div>
    </div>
  </section>

</div>

<div class="section-kicker">Foundations</div>
<div class="projects-heading">Previous and foundational research</div>

<div class="foundation-grid">
  <div class="foundation-card">
    <h3>Enhancer biology</h3>
    <p>Foundational work on enhancers and enhancer RNAs in transcriptional regulation and inflammatory gene expression.</p>
  </div>

  <div class="foundation-card">
    <h3>Genomic dissection of atherosclerosis</h3>
    <p>Application of next-generation sequencing technologies to identify regulatory mechanisms in cardiovascular disease.</p>
  </div>

  <div class="foundation-card">
    <h3>Polygenic disease architecture</h3>
    <p>Research linking genetic variation, disease-associated cell states, and heritability in cardiovascular disease.</p>
  </div>

  <div class="foundation-card">
    <h3>Variant-to-function mapping</h3>
    <p>Frameworks connecting non-coding variants to regulatory elements, target genes, and disease mechanisms.</p>
  </div>
</div>

<section class="vision-panel">
  <h2>Research vision</h2>
  <div class="vision-route">
    Genetic variation → Regulatory function → Cellular mechanisms → Disease biology → Clinical translation
  </div>
  <p>
    The long-term goal is to bridge the gap between genetic association and disease mechanism by combining experimental genomics, single-cell technologies, computational biology, and translational cardiovascular research.
  </p>
</section>

<div class="bottom-actions">
  <a href="../team/">Meet the team</a>
  <a href="../publications/">Publications</a>
  <a href="../contact/">Contact us</a>
</div>

</div>
