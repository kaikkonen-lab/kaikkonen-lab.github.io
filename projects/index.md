---
title: Projects
nav:
  order: 2
  tooltip: Ongoing and past research in the Kaikkonen Lab
---

<style>
.projects-page {
  --navy: #071d35;
  --deep: #061625;
  --blue: #0c4d68;
  --teal: #0fa6a6;
  --berry: #8f2048;
  --ink: #102033;
  --muted: #617487;
  --line: rgba(7, 29, 53, 0.12);
  --soft: #f5f8fb;
  --paper: #ffffff;

  color: var(--ink);
}

.projects-hero {
  width: min(1180px, calc(100% - 44px));
  margin: 64px auto 84px;
}

.projects-kicker,
.section-kicker,
.card-kicker {
  margin: 0 0 16px;
  color: var(--berry);
  font-size: 0.76rem;
  font-weight: 900;
  letter-spacing: 0.15em;
  text-transform: uppercase;
}

.projects-hero h1 {
  max-width: 1040px;
  margin: 0;
  color: var(--navy);
  font-size: clamp(2.8rem, 6vw, 6.3rem);
  line-height: 0.92;
  letter-spacing: -0.075em;
  font-weight: 950;
}

.projects-hero h1 span {
  display: block;
  color: var(--teal);
}

.projects-hero .lead {
  max-width: 850px;
  margin: 30px 0 0;
  color: rgba(16, 32, 51, 0.78);
  font-size: clamp(1.05rem, 1.35vw, 1.24rem);
  line-height: 1.75;
}

.hero-pills {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 34px;
}

.hero-pills a {
  display: inline-flex;
  align-items: center;
  min-height: 42px;
  padding: 0 16px;
  border-radius: 999px;
  color: var(--navy);
  background: #ffffff;
  border: 1px solid var(--line);
  text-decoration: none;
  font-weight: 800;
  transition: all 0.2s ease;
}

.hero-pills a:hover {
  color: #ffffff;
  background: var(--navy);
  transform: translateY(-2px);
}

.logic-section,
.projects-section,
.foundation-section,
.vision-section,
.bottom-actions {
  width: min(1180px, calc(100% - 44px));
  margin-left: auto;
  margin-right: auto;
}

.section-heading {
  max-width: 800px;
  margin-bottom: 34px;
}

.section-heading h2 {
  margin: 0;
  color: var(--navy);
  font-size: clamp(2rem, 3.5vw, 3.8rem);
  line-height: 1.03;
  letter-spacing: -0.055em;
}

.section-heading p.description {
  margin: 18px 0 0;
  color: var(--muted);
  font-size: 1.05rem;
  line-height: 1.7;
}

/* RESEARCH LOGIC */

.logic-section {
  margin-bottom: 92px;
}

.research-map {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  border-top: 1px solid var(--line);
  border-left: 1px solid var(--line);
}

.map-node {
  position: relative;
  min-height: 250px;
  padding: 30px 24px;
  background: #ffffff;
  border-right: 1px solid var(--line);
  border-bottom: 1px solid var(--line);
  transition: background 0.2s ease, transform 0.2s ease;
}

.map-node:hover {
  background: var(--soft);
}

.map-node span {
  display: inline-flex;
  margin-bottom: 52px;
  color: rgba(143, 32, 72, 0.35);
  font-size: 0.82rem;
  font-weight: 950;
  letter-spacing: 0.14em;
}

.map-node h3 {
  margin: 0 0 12px;
  color: var(--navy);
  font-size: 1.08rem;
  line-height: 1.25;
  letter-spacing: -0.025em;
}

.map-node p {
  margin: 0;
  color: var(--muted);
  font-size: 0.96rem;
  line-height: 1.62;
}

.map-node::after {
  content: "";
  position: absolute;
  top: 50px;
  left: 24px;
  right: 24px;
  height: 1px;
  background: linear-gradient(90deg, rgba(15, 166, 166, 0.55), transparent);
}

/* PROJECTS */

.projects-section {
  margin-bottom: 96px;
}

.project-stack {
  display: grid;
  gap: 26px;
}

.project-feature {
  display: grid;
  grid-template-columns: 0.58fr 1.42fr;
  min-height: 360px;
  overflow: hidden;
  border-radius: 34px;
  background: #ffffff;
  border: 1px solid var(--line);
  box-shadow: 0 24px 70px rgba(7, 29, 53, 0.08);
}

.project-visual {
  position: relative;
  padding: 30px;
  background:
    radial-gradient(circle at 25% 20%, rgba(15, 166, 166, 0.20), transparent 32%),
    radial-gradient(circle at 80% 76%, rgba(143, 32, 72, 0.14), transparent 30%),
    linear-gradient(145deg, #f7fbfd, #eef6f7);
  border-right: 1px solid var(--line);
}

.project-visual::before {
  content: "";
  position: absolute;
  inset: 30px;
  border-radius: 28px;
  border: 1px solid rgba(7, 29, 53, 0.10);
}

.project-index {
  position: relative;
  z-index: 1;
  color: rgba(7, 29, 53, 0.22);
  font-size: 4.8rem;
  font-weight: 950;
  line-height: 1;
  letter-spacing: -0.08em;
}

.project-linework {
  position: absolute;
  left: 30px;
  right: 30px;
  bottom: 34px;
  height: 120px;
  border-radius: 24px;
  overflow: hidden;
  background:
    linear-gradient(90deg, transparent 0 8%, rgba(7, 29, 53, 0.18) 8% 9%, transparent 9% 28%, rgba(15, 166, 166, 0.50) 28% 29%, transparent 29% 48%, rgba(7, 29, 53, 0.16) 48% 49%, transparent 49% 68%, rgba(143, 32, 72, 0.42) 68% 69%, transparent 69%),
    linear-gradient(180deg, transparent 58px, rgba(7, 29, 53, 0.16) 59px, transparent 60px);
}

.project-linework::before {
  content: "";
  position: absolute;
  inset: 30px 18px;
  border-top: 2px solid rgba(15, 166, 166, 0.45);
  border-radius: 50% 50% 0 0;
}

.project-linework::after {
  content: "";
  position: absolute;
  width: 9px;
  height: 9px;
  left: 31%;
  top: 55px;
  border-radius: 999px;
  background: var(--teal);
  box-shadow:
    68px -20px 0 rgba(143, 32, 72, 0.75),
    126px 18px 0 rgba(7, 29, 53, 0.35);
}

.project-body {
  padding: 38px 42px;
}

.project-tag {
  display: inline-flex;
  margin-bottom: 16px;
  padding: 7px 12px;
  border-radius: 999px;
  color: #006d70;
  background: rgba(15, 166, 166, 0.11);
  font-size: 0.78rem;
  font-weight: 900;
  letter-spacing: 0.07em;
  text-transform: uppercase;
}

.project-body h2 {
  margin: 0 0 16px;
  color: var(--navy);
  font-size: clamp(1.55rem, 2.3vw, 2.25rem);
  line-height: 1.08;
  letter-spacing: -0.045em;
}

.project-body p {
  margin: 0;
  color: rgba(16, 32, 51, 0.78);
  font-size: 1.02rem;
  line-height: 1.72;
}

.focus-list {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin: 22px 0 0;
}

.focus-list span {
  display: inline-flex;
  align-items: center;
  min-height: 32px;
  padding: 0 11px;
  border-radius: 999px;
  color: var(--navy);
  background: var(--soft);
  border: 1px solid var(--line);
  font-size: 0.86rem;
  font-weight: 800;
}

.project-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 24px;
}

.project-actions a {
  display: inline-flex;
  align-items: center;
  min-height: 40px;
  padding: 0 15px;
  border-radius: 999px;
  color: #ffffff;
  background: var(--navy);
  text-decoration: none;
  font-size: 0.88rem;
  font-weight: 850;
  transition: all 0.2s ease;
}

.project-actions a.secondary {
  color: var(--navy);
  background: #ffffff;
  border: 1px solid var(--line);
}

.project-actions a:hover {
  color: #ffffff;
  background: var(--teal);
  transform: translateY(-2px);
}

/* FOUNDATIONS */

.foundation-section {
  margin-bottom: 96px;
}

.foundation-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  border-top: 1px solid var(--line);
  border-left: 1px solid var(--line);
}

.foundation-card {
  min-height: 230px;
  padding: 28px 24px;
  background: #ffffff;
  border-right: 1px solid var(--line);
  border-bottom: 1px solid var(--line);
}

.foundation-card h3 {
  margin: 0 0 14px;
  color: var(--navy);
  font-size: 1.18rem;
  line-height: 1.25;
}

.foundation-card p {
  margin: 0;
  color: var(--muted);
  line-height: 1.65;
}

/* VISION */

.vision-section {
  margin-bottom: 56px;
}

.vision-panel {
  position: relative;
  overflow: hidden;
  padding: 58px;
  border-radius: 36px;
  color: #ffffff;
  background:
    radial-gradient(circle at 84% 18%, rgba(15, 166, 166, 0.30), transparent 34%),
    linear-gradient(135deg, #68153d 0%, #071d35 68%, #064f5d 100%);
}

.vision-panel::after {
  content: "";
  position: absolute;
  inset: 0;
  background-image:
    linear-gradient(rgba(255, 255, 255, 0.045) 1px, transparent 1px),
    linear-gradient(90deg, rgba(255, 255, 255, 0.045) 1px, transparent 1px);
  background-size: 52px 52px;
  mask-image: linear-gradient(90deg, transparent, black 20%, black 80%, transparent);
}

.vision-panel > * {
  position: relative;
  z-index: 1;
}

.vision-panel h2 {
  max-width: 820px;
  margin: 0;
  color: #ffffff;
  font-size: clamp(2rem, 3.6vw, 4rem);
  line-height: 1.02;
  letter-spacing: -0.055em;
}

.vision-route {
  max-width: 1000px;
  margin: 26px 0;
  color: rgba(255, 255, 255, 0.92);
  font-size: clamp(1.05rem, 1.55vw, 1.38rem);
  font-weight: 850;
  line-height: 1.7;
}

.vision-panel p {
  max-width: 820px;
  margin: 0;
  color: rgba(255, 255, 255, 0.76);
  font-size: 1.05rem;
  line-height: 1.72;
}

/* BOTTOM ACTIONS */

.bottom-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-bottom: 80px;
}

.bottom-actions a {
  display: inline-flex;
  align-items: center;
  min-height: 42px;
  padding: 0 16px;
  border-radius: 999px;
  color: #ffffff;
  background: var(--navy);
  text-decoration: none;
  font-weight: 850;
}

.bottom-actions a:hover {
  background: var(--teal);
}

/* RESPONSIVE */

@media (max-width: 1020px) {
  .research-map,
  .foundation-grid {
    grid-template-columns: 1fr 1fr;
  }

  .project-feature {
    grid-template-columns: 1fr;
  }

  .project-visual {
    min-height: 230px;
    border-right: 0;
    border-bottom: 1px solid var(--line);
  }
}

@media (max-width: 680px) {
  .projects-hero,
  .logic-section,
  .projects-section,
  .foundation-section,
  .vision-section,
  .bottom-actions {
    width: min(100% - 30px, 1180px);
  }

  .projects-hero {
    margin-top: 48px;
  }

  .research-map,
  .foundation-grid {
    grid-template-columns: 1fr;
  }

  .project-body {
    padding: 30px 24px;
  }

  .vision-panel {
    padding: 38px 26px;
  }

  .bottom-actions a,
  .hero-pills a {
    width: 100%;
    justify-content: center;
  }
}
</style>

<div class="projects-page">

  <section class="projects-hero">
    <p class="projects-kicker">Projects · Kaikkonen Lab</p>

    <h1>
      From genetic discovery to
      <span>cardiovascular mechanisms</span>
    </h1>

    <p class="lead">
      The Kaikkonen Lab investigates how genetic variation, regulatory elements,
      cellular states, and tissue context shape atherosclerotic cardiovascular
      disease. Our research connects functional genomics, single-cell and spatial
      biology, computational modelling, and translational cardiovascular medicine.
    </p>

    <div class="hero-pills">
      <a href="#miracle">MIRACLE</a>
      <a href="#secret">SECRET</a>
      <a href="#singlecell">Single-cell & spatial genomics</a>
      <a href="#finemapping">Functional fine-mapping</a>
      <a href="#multimodal">Multimodal translation</a>
    </div>
  </section>

  <section class="logic-section">
    <div class="section-heading">
      <p class="section-kicker">Research logic</p>
      <h2>A connected discovery pipeline</h2>
      <p class="description">
        Our projects are organized around a variant-to-function framework:
        identifying genetic signals, resolving their regulatory consequences,
        placing them in cellular context, and interpreting their disease relevance.
      </p>
    </div>

    <div class="research-map">
      <article class="map-node">
        <span>01</span>
        <h3>Genetic variation</h3>
        <p>GWAS loci, disease-associated variants, and inherited cardiovascular risk.</p>
      </article>

      <article class="map-node">
        <span>02</span>
        <h3>Causal prioritization</h3>
        <p>Fine-mapping and functional prioritization of regulatory variants.</p>
      </article>

      <article class="map-node">
        <span>03</span>
        <h3>Functional mechanisms</h3>
        <p>Enhancers, target genes, perturbation assays, and regulatory networks.</p>
      </article>

      <article class="map-node">
        <span>04</span>
        <h3>Cellular context</h3>
        <p>Single-cell, multiome, and spatial mapping of disease-state programs.</p>
      </article>

      <article class="map-node">
        <span>05</span>
        <h3>Translation</h3>
        <p>Mechanism-aware interpretation of cardiovascular disease biology.</p>
      </article>
    </div>
  </section>

  <section class="projects-section">
    <div class="section-heading">
      <p class="section-kicker">Ongoing programs</p>
      <h2>Current research projects</h2>
    </div>

    <div class="project-stack">

      <section class="project-feature" id="miracle">
        <div class="project-visual">
          <div class="project-index">01</div>
          <div class="project-linework"></div>
        </div>

        <div class="project-body">
          <span class="project-tag">Ongoing · 2023–2027</span>
          <h2>MIRACLE</h2>
          <p>
            MIRACLE focuses on understanding how genetic risk contributes to
            cardiovascular disease mechanisms and disease progression. The project
            integrates genetic, functional, and multi-omics data to identify causal
            variants, regulatory mechanisms, and pathways that shape cardiovascular risk.
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
        <div class="project-visual">
          <div class="project-index">02</div>
          <div class="project-linework"></div>
        </div>

        <div class="project-body">
          <span class="project-tag">ERC-funded project</span>
          <h2>SECRET</h2>
          <p>
            SECRET aims to functionally dissect causal regulatory variants in
            atherosclerotic cardiovascular disease. The project connects non-coding
            disease variants to enhancer activity, target genes, cellular phenotypes,
            and disease-relevant regulatory networks.
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
        <div class="project-visual">
          <div class="project-index">03</div>
          <div class="project-linework"></div>
        </div>

        <div class="project-body">
          <span class="project-tag">Single-cell · Spatial biology</span>
          <h2>Single-cell and spatial genomics</h2>
          <p>
            This research direction maps cardiovascular disease at cell-type and
            spatial resolution, identifying disease-associated cell states,
            regulatory programs, and spatial tissue organization in vascular pathology.
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
        <div class="project-visual">
          <div class="project-index">04</div>
          <div class="project-linework"></div>
        </div>

        <div class="project-body">
          <span class="project-tag">Variant-to-function</span>
          <h2>Functional fine-mapping of GWAS variants</h2>
          <p>
            This project area translates statistical disease associations into
            experimentally testable biological mechanisms by identifying causal
            regulatory elements, target genes, and functional effects of non-coding
            variants.
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
        <div class="project-visual">
          <div class="project-index">05</div>
          <div class="project-linework"></div>
        </div>

        <div class="project-body">
          <span class="project-tag">Computational · Translational</span>
          <h2>Multimodal translational cardiovascular genomics</h2>
          <p>
            This emerging direction integrates molecular, cellular, spatial,
            genetic, and clinical data to connect disease mechanisms with phenotype
            and support mechanism-aware prediction.
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
        <div class="project-visual">
          <div class="project-index">06</div>
          <div class="project-linework"></div>
        </div>

        <div class="project-body">
          <span class="project-tag">Core biology</span>
          <h2>Gene regulatory mechanisms in cardiovascular disease</h2>
          <p>
            A central goal of the lab is to understand how regulatory elements,
            enhancers, enhancer RNAs, chromatin programs, and transcriptional
            networks control disease-relevant cellular phenotypes.
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
  </section>

  <section class="foundation-section">
    <div class="section-heading">
      <p class="section-kicker">Foundations</p>
      <h2>Previous and foundational research</h2>
    </div>

    <div class="foundation-grid">
      <article class="foundation-card">
        <h3>Enhancer biology</h3>
        <p>Foundational work on enhancers and enhancer RNAs in transcriptional regulation and inflammatory gene expression.</p>
      </article>

      <article class="foundation-card">
        <h3>Genomic dissection of atherosclerosis</h3>
        <p>Application of next-generation sequencing technologies to identify regulatory mechanisms in cardiovascular disease.</p>
      </article>

      <article class="foundation-card">
        <h3>Polygenic disease architecture</h3>
        <p>Research linking genetic variation, disease-associated cell states, and heritability in cardiovascular disease.</p>
      </article>

      <article class="foundation-card">
        <h3>Variant-to-function mapping</h3>
        <p>Frameworks connecting non-coding variants to regulatory elements, target genes, and disease mechanisms.</p>
      </article>
    </div>
  </section>

  <section class="vision-section">
    <div class="vision-panel">
      <p class="projects-kicker">Research vision</p>
      <h2>Bridging genetic association and disease mechanism</h2>

      <div class="vision-route">
        Genetic variation → Regulatory function → Cellular mechanisms → Disease biology → Clinical translation
      </div>

      <p>
        The long-term goal is to bridge the gap between genetic association and
        disease mechanism by combining experimental genomics, single-cell technologies,
        computational biology, and translational cardiovascular research.
      </p>
    </div>
  </section>

  <div class="bottom-actions">
    <a href="../team/">Meet the team</a>
    <a href="../publications/">Publications</a>
    <a href="../contact/">Contact us</a>
  </div>

</div>
