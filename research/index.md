---
title: Research
nav:
  order: 1
  tooltip: Research themes and publications
---

<style>
.research-page {
  --navy: #071d35;
  --deep: #061625;
  --blue: #0c4d68;
  --teal: #0fa6a6;
  --berry: #8f2048;
  --ink: #102033;
  --muted: #617487;
  --line: rgba(7, 29, 53, 0.12);
  --soft: #f5f8fb;

  color: var(--ink);
}

/* HERO */

.research-hero,
.research-themes,
.publication-links,
.publications-section,
.research-vision {
  width: min(1180px, calc(100% - 44px));
  margin-left: auto;
  margin-right: auto;
}

.research-hero {
  margin-top: 64px;
  margin-bottom: 84px;
}

.research-kicker,
.section-kicker {
  margin: 0 0 16px;
  color: var(--berry);
  font-size: 0.76rem;
  font-weight: 900;
  letter-spacing: 0.15em;
  text-transform: uppercase;
}

.research-hero h1 {
  max-width: 1060px;
  margin: 0;
  color: var(--navy);
  font-size: clamp(2.8rem, 6vw, 6.3rem);
  line-height: 0.92;
  letter-spacing: -0.075em;
  font-weight: 950;
}

.research-hero h1 span {
  display: block;
  color: var(--teal);
}

.research-hero .lead {
  max-width: 880px;
  margin: 30px 0 0;
  color: rgba(16, 32, 51, 0.78);
  font-size: clamp(1.05rem, 1.35vw, 1.24rem);
  line-height: 1.75;
}

.research-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 34px;
}

.research-actions a {
  display: inline-flex;
  align-items: center;
  min-height: 42px;
  padding: 0 16px;
  border-radius: 999px;
  color: #ffffff;
  background: var(--navy);
  text-decoration: none;
  font-weight: 850;
  transition: all 0.2s ease;
}

.research-actions a.secondary {
  color: var(--navy);
  background: #ffffff;
  border: 1px solid var(--line);
}

.research-actions a:hover {
  color: #ffffff;
  background: var(--teal);
  transform: translateY(-2px);
}

/* THEMES */

.research-themes {
  margin-bottom: 96px;
}

.section-heading {
  max-width: 820px;
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

.theme-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  border-top: 1px solid var(--line);
  border-left: 1px solid var(--line);
}

.theme-card {
  min-height: 320px;
  padding: 32px 28px;
  background: #ffffff;
  border-right: 1px solid var(--line);
  border-bottom: 1px solid var(--line);
  transition: background 0.2s ease;
}

.theme-card:hover {
  background: var(--soft);
}

.theme-card span {
  display: block;
  margin-bottom: 54px;
  color: rgba(143, 32, 72, 0.35);
  font-size: 0.82rem;
  font-weight: 950;
  letter-spacing: 0.14em;
}

.theme-card h3 {
  margin: 0 0 14px;
  color: var(--navy);
  font-size: 1.32rem;
  line-height: 1.18;
  letter-spacing: -0.035em;
}

.theme-card p {
  margin: 0;
  color: var(--muted);
  line-height: 1.68;
}

/* PUBLICATION LINKS */

.publication-links {
  margin-bottom: 96px;
}

.profile-panel {
  position: relative;
  overflow: hidden;
  padding: 54px;
  border-radius: 36px;
  color: #ffffff;
  background:
    radial-gradient(circle at 84% 18%, rgba(15, 166, 166, 0.30), transparent 34%),
    linear-gradient(135deg, #68153d 0%, #071d35 68%, #064f5d 100%);
}

.profile-panel::after {
  content: "";
  position: absolute;
  inset: 0;
  background-image:
    linear-gradient(rgba(255, 255, 255, 0.045) 1px, transparent 1px),
    linear-gradient(90deg, rgba(255, 255, 255, 0.045) 1px, transparent 1px);
  background-size: 52px 52px;
  mask-image: linear-gradient(90deg, transparent, black 20%, black 80%, transparent);
}

.profile-panel > * {
  position: relative;
  z-index: 1;
}

.profile-panel h2 {
  max-width: 860px;
  margin: 0;
  color: #ffffff;
  font-size: clamp(2rem, 3.5vw, 3.8rem);
  line-height: 1.03;
  letter-spacing: -0.055em;
}

.profile-panel p {
  max-width: 860px;
  margin: 22px 0 0;
  color: rgba(255, 255, 255, 0.78);
  font-size: 1.05rem;
  line-height: 1.72;
}

.profile-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 30px;
}

.profile-actions a {
  display: inline-flex;
  align-items: center;
  min-height: 42px;
  padding: 0 16px;
  border-radius: 999px;
  color: var(--navy);
  background: #ffffff;
  text-decoration: none;
  font-weight: 900;
  transition: all 0.2s ease;
}

.profile-actions a:hover {
  color: #ffffff;
  background: var(--teal);
  transform: translateY(-2px);
}

/* PUBLICATIONS */

.publications-section {
  margin-bottom: 96px;
}

.publication-toolbar {
  margin: 34px 0 28px;
  padding: 26px;
  border-radius: 28px;
  background: #ffffff;
  border: 1px solid var(--line);
  box-shadow: 0 18px 50px rgba(7, 29, 53, 0.06);
}

.publication-note {
  margin: 0 0 18px;
  color: var(--muted);
  line-height: 1.65;
}

/* VISION */

.research-vision {
  margin-bottom: 80px;
}

.vision-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  border-top: 1px solid var(--line);
  border-left: 1px solid var(--line);
}

.vision-card {
  min-height: 230px;
  padding: 30px 26px;
  background: #ffffff;
  border-right: 1px solid var(--line);
  border-bottom: 1px solid var(--line);
}

.vision-card h3 {
  margin: 0 0 14px;
  color: var(--navy);
  font-size: 1.2rem;
  line-height: 1.22;
}

.vision-card p {
  margin: 0;
  color: var(--muted);
  line-height: 1.68;
}

/* RESPONSIVE */

@media (max-width: 900px) {
  .theme-grid,
  .vision-grid {
    grid-template-columns: 1fr;
  }

  .profile-panel {
    padding: 42px 30px;
  }
}

@media (max-width: 640px) {
  .research-hero,
  .research-themes,
  .publication-links,
  .publications-section,
  .research-vision {
    width: min(100% - 30px, 1180px);
  }

  .research-hero {
    margin-top: 48px;
  }

  .research-actions a,
  .profile-actions a {
    width: 100%;
    justify-content: center;
  }

  .publication-toolbar {
    padding: 22px;
  }
}
</style>

<div class="research-page">

  <section class="research-hero">
    <p class="research-kicker">Research · Kaikkonen Lab</p>

    <h1>
      Regulatory genomics of
      <span>cardiovascular disease</span>
    </h1>

    <p class="lead">
      The Kaikkonen Lab studies how genetic variation, chromatin regulation,
      enhancer activity, cellular state transitions, and inflammatory programs
      contribute to atherosclerotic cardiovascular disease and cardiometabolic
      disease.
    </p>

    <div class="research-actions">
      <a href="#publications">Recent publications</a>
      <a class="secondary" href="https://scholar.google.com/citations?hl=en&user=WHdgFhUAAAAJ" target="_blank">Google Scholar</a>
      <a class="secondary" href="https://pubmed.ncbi.nlm.nih.gov/?term=Minna+Kaikkonen" target="_blank">PubMed</a>
    </div>
  </section>

  <section class="research-themes">
    <div class="section-heading">
      <p class="section-kicker">Research themes</p>
      <h2>Mechanisms linking genetic variation to disease biology</h2>
      <p class="description">
        Our research connects statistical genetic discoveries with functional
        regulatory mechanisms, disease-associated cell states, and experimentally
        testable cardiovascular biology.
      </p>
    </div>

    <div class="theme-grid">
      <article class="theme-card">
        <span>01</span>
        <h3>Regulatory variant function</h3>
        <p>
          We investigate how non-coding disease-associated variants influence
          enhancers, transcription factor binding, chromatin accessibility, and
          target gene regulation.
        </p>
      </article>

      <article class="theme-card">
        <span>02</span>
        <h3>Single-cell and spatial disease biology</h3>
        <p>
          We use single-cell, multiome, and spatial approaches to identify
          disease-relevant cell states and regulatory programs in cardiovascular
          tissues.
        </p>
      </article>

      <article class="theme-card">
        <span>03</span>
        <h3>Functional genomics and perturbation</h3>
        <p>
          We combine high-throughput functional genomics, cellular models, and
          computational analysis to prioritize mechanisms and interpret disease risk.
        </p>
      </article>
    </div>
  </section>

  <section class="publication-links">
    <div class="profile-panel">
      <p class="research-kicker">Publication profiles</p>

      <h2>
        Follow the latest publications from Minna Kaikkonen-Määttä and the group
      </h2>

      <p>
        For the most up-to-date publication list, use the external profile links
        below. The local list on this page displays publications available in the
        website citation database.
      </p>

      <div class="profile-actions">
        <a href="https://scholar.google.com/citations?hl=en&user=WHdgFhUAAAAJ" target="_blank">Google Scholar profile</a>
        <a href="https://pubmed.ncbi.nlm.nih.gov/?term=Minna+Kaikkonen" target="_blank">PubMed search</a>
        <a href="https://uefconnect.uef.fi/en/minna.kaikkonen-maatta/" target="_blank">UEF profile</a>
        <a href="https://uefconnect.uef.fi/en/cardiovascular-genomics-kaikkonen-lab/" target="_blank">UEF group profile</a>
      </div>
    </div>
  </section>

  <section id="publications" class="publications-section">
    <div class="section-heading">
      <p class="section-kicker">Publications</p>
      <h2>Recent and selected publications</h2>
      <p class="description">
        Publications shown below are rendered from the website citation database.
        Use the search box to filter by author, title, year, or keyword.
      </p>
    </div>

    <div class="publication-toolbar">
      <p class="publication-note">
        Search the local publication database or open the external profiles above
        for the full and most current publication record.
      </p>

      {% include search-box.html %}
      {% include search-info.html %}
    </div>

    {% include list.html data="citations" component="citation" style="rich" %}
  </section>

  <section class="research-vision">
    <div class="section-heading">
      <p class="section-kicker">Research direction</p>
      <h2>From association to mechanism</h2>
    </div>

    <div class="vision-grid">
      <article class="vision-card">
        <h3>Genetic discovery</h3>
        <p>
          Identify disease-associated loci and prioritize variants most likely to
          influence cardiovascular disease biology.
        </p>
      </article>

      <article class="vision-card">
        <h3>Regulatory mechanism</h3>
        <p>
          Connect variants to enhancers, chromatin programs, target genes, and
          disease-relevant cellular responses.
        </p>
      </article>

      <article class="vision-card">
        <h3>Biological interpretation</h3>
        <p>
          Translate genomic discoveries into mechanistic insight and experimentally
          testable hypotheses for cardiovascular disease.
        </p>
      </article>
    </div>
  </section>

</div>
