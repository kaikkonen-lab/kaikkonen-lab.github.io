---
title: Research
nav:
  order: 1
  tooltip: Publications
---

<style>
.research-page {
  --navy: #071d35;
  --teal: #0fa6a6;
  --berry: #8f2048;
  --ink: #102033;
  --muted: #617487;
  --line: rgba(7, 29, 53, 0.12);
  --soft: #f5f8fb;

  color: var(--ink);
}

.research-container {
  width: min(1100px, calc(100% - 40px));
  margin: 60px auto 80px;
}

.section-kicker {
  margin: 0 0 12px;
  color: var(--berry);
  font-size: 0.75rem;
  font-weight: 900;
  letter-spacing: 0.14em;
  text-transform: uppercase;
}

.section-title {
  margin: 0;
  color: var(--navy);
  font-size: clamp(2rem, 3.5vw, 3.2rem);
  line-height: 1.05;
  letter-spacing: -0.04em;
}

.profile-panel {
  margin-top: 30px;
  padding: 34px;
  border-radius: 24px;
  background: #ffffff;
  border: 1px solid var(--line);
  box-shadow: 0 18px 50px rgba(7, 29, 53, 0.06);
}

.profile-panel p {
  margin: 0;
  color: var(--muted);
  line-height: 1.65;
}

.profile-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 22px;
}

.profile-actions a {
  display: inline-flex;
  align-items: center;
  min-height: 40px;
  padding: 0 15px;
  border-radius: 999px;
  text-decoration: none;
  font-weight: 850;
  font-size: 0.9rem;
  background: var(--navy);
  color: white;
  transition: all 0.2s ease;
}

.profile-actions a.secondary {
  background: #ffffff;
  color: var(--navy);
  border: 1px solid var(--line);
}

.profile-actions a:hover {
  background: var(--teal);
  color: #ffffff;
  transform: translateY(-2px);
}

/* SELECTED PUBLICATIONS */

.selected-publications {
  margin-top: 58px;
}

.selected-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 18px;
  margin-top: 24px;
}

.selected-card {
  overflow: hidden;
  border-radius: 24px;
  background: #ffffff;
  border: 1px solid var(--line);
  box-shadow: 0 18px 50px rgba(7, 29, 53, 0.06);
  text-decoration: none;
  color: var(--ink);
  transition: transform 0.22s ease, box-shadow 0.22s ease;
}

.selected-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 26px 70px rgba(7, 29, 53, 0.12);
}

.selected-image {
  height: 190px;
  background:
    radial-gradient(circle at 30% 20%, rgba(15, 166, 166, 0.18), transparent 34%),
    linear-gradient(145deg, #f7fbfd, #eef6f7);
  border-bottom: 1px solid var(--line);
  overflow: hidden;
}

.selected-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}

.selected-body {
  padding: 22px;
}

.selected-meta {
  margin: 0 0 10px;
  color: var(--berry);
  font-size: 0.72rem;
  font-weight: 900;
  letter-spacing: 0.12em;
  text-transform: uppercase;
}

.selected-card h3 {
  margin: 0;
  color: var(--navy);
  font-size: 1.08rem;
  line-height: 1.32;
  letter-spacing: -0.025em;
}

.selected-card p {
  margin: 12px 0 0;
  color: var(--muted);
  font-size: 0.92rem;
  line-height: 1.58;
}

/* PUBLICATIONS */

.publications-section {
  margin-top: 64px;
}

.publication-toolbar {
  margin: 22px 0 32px;
  padding: 22px;
  border-radius: 22px;
  background: #ffffff;
  border: 1px solid var(--line);
  box-shadow: 0 14px 40px rgba(7, 29, 53, 0.05);
}

.publication-note {
  margin: 0 0 16px;
  color: var(--muted);
  font-size: 0.96rem;
  line-height: 1.6;
}

@media (max-width: 900px) {
  .selected-grid {
    grid-template-columns: 1fr;
  }

  .selected-image {
    height: 230px;
  }
}

@media (max-width: 640px) {
  .research-container {
    width: calc(100% - 30px);
    margin-top: 42px;
  }

  .profile-panel,
  .publication-toolbar {
    padding: 24px;
  }

  .profile-actions a {
    width: 100%;
    justify-content: center;
  }

  .selected-image {
    height: 190px;
  }
}
</style>

<div class="research-page">

  <div class="research-container">

    <p class="section-kicker">Publications</p>

    <h1 class="section-title">
      Kaikkonen Lab publications
    </h1>

    <div class="profile-panel">
      <p>
        Publications on this page are generated from Minna Kaikkonen-Määttä’s ORCID record
        and the website citation database. For the complete and continuously updated
        publication record, use the external profile links below.
      </p>

      <div class="profile-actions">
        <a href="https://scholar.google.com/citations?hl=en&user=WHdgFhUAAAAJ" target="_blank">Google Scholar</a>
        <a href="https://pubmed.ncbi.nlm.nih.gov/?term=Minna+Kaikkonen" target="_blank">PubMed</a>
        <a class="secondary" href="https://uefconnect.uef.fi/en/minna.kaikkonen-maatta/" target="_blank">UEF profile</a>
      </div>
    </div>

    <section class="selected-publications">

      <p class="section-kicker">Selected publications</p>

      <h2 class="section-title">
        Recent work from the group
      </h2>

      <div class="selected-grid">

        <a class="selected-card" href="https://doi.org/10.1093/cvr/cvaf210" target="_blank">
          <div class="selected-image">
            <img src="https://oup.silverchair-cdn.com/oup/backfile/Content_public/Journal/cardiovascres/121/16/10.1093_cvr_cvaf210/2/cvaf210f1.jpeg?Expires=1781067907&Signature=n74i7vR1asfiqr8ZjUQsx33YwnJP-h8nSYHSCGAh~1IHCHuHIxOTGbxFiq-0dWQ4ArMSYIC5fZ2jmRBvAOQU1uBLlW9-jEpaOLRBA~7fWANKa-Ab02AW5LJKSOg-o6I0lqhMy0uhI9Xuw24kjVO3zIgK3LdenUY-mZs3zxkrHOZ4fexJIHksvB1M65qlfHg6y7-o1uGsTRKB0IJHjcfptY1AZNMZkigRT0Jre8z-4t1GTpxbcMZfRees1Si2fpsy6~BRIJpu8t~c2Hjz6-xllMFf0ikMp5IbMyFjTpYyeiSSNl1idnXHIRILlPdSfzfmWW~yYBebb5qPGSHNmu1jiA__&Key-Pair-Id=APKAIE5G5CRDK6RD3PGA" alt="Single-cell macrophage biomarkers for atherosclerosis publication figure">
          </div>
          <div class="selected-body">
            <p class="selected-meta">Cardiovascular Research · 2025</p>
            <h3>Single-cell to pre-clinical evaluation of Trem2, Folr2, and Slc7a7 as macrophage-associated biomarkers for atherosclerosis</h3>
            <p>Single-cell and pre-clinical evaluation of macrophage-associated biomarkers in atherosclerosis.</p>
          </div>
        </a>

        <a class="selected-card" href="https://doi.org/10.1016/j.ajhg.2023.03.010" target="_blank">
          <div class="selected-image">
            <img src="https://ars.els-cdn.com/content/image/1-s2.0-S0002929723000976-gr1.jpg" alt="Dissecting the polygenic basis of atherosclerosis publication figure">
          </div>
          <div class="selected-body">
            <p class="selected-meta">American Journal of Human Genetics · 2023</p>
            <h3>Dissecting the polygenic basis of atherosclerosis via disease-associated cell states</h3>
            <p>Single-cell and bulk transcriptomic analysis connecting atherosclerosis cell states with CAD genetic risk.</p>
          </div>
        </a>

        <a class="selected-card" href="https://doi.org/10.1093/cvr/cvaa219" target="_blank">
          <div class="selected-image">
            <img src="https://oup.silverchair-cdn.com/oup/backfile/Content_public/Journal/cardiovascres/117/5/10.1093_cvr_cvaa219/1/cvaa219f8.jpeg?Expires=1781067946&Signature=VOa1afAjp6jabVfNdFVlaRm-dqlIjpu~-1BF-v3uY4-4Uearel77jpbZHwJVv537kA2s4xqLNZQiyyhy6wZoLuZgsS~hbcJ-1Sk~8aJZSweUjcDUNjX2MacWybLFZewKUgCExAEOm7MgDSgvsk-BW5~cawEZyBU04C4OO7nNeszP3vsJoMdcVEJUDoeZHflp097eVjmLKlXwfrbJsW6LmDOtY4JAOIfaq-Gw9w5DjWaiR8bNeRkugD7x-rTHdt37qVTLIuu~aaTaGps2Yjrxs6Q0blSaPVaCLukF-A8E2llDo4BZOiQ8R~ZL5bKuHHFkpLk68HQyEuOHfg4-5rR4Vw__&Key-Pair-Id=APKAIE5G5CRDK6RD3PGA" alt="NRF2 endothelial microRNA publication figure">
          </div>
          <div class="selected-body">
            <p class="selected-meta">Cardiovascular Research · 2021</p>
            <h3>NRF2 is a key regulator of endothelial microRNA expression under proatherogenic stimuli</h3>
            <p>Integrative regulatory analysis of NRF2, endothelial microRNAs, and proatherogenic stimulation.</p>
          </div>
        </a>

      </div>

    </section>

    <section id="publications" class="publications-section">

      <p class="section-kicker">Publication database</p>

      <h2 class="section-title">
        All publications
      </h2>

      <div class="publication-toolbar">
        <p class="publication-note">
          Search publications by title, author, journal, year, or keyword.
        </p>

        {% include search-box.html %}
        {% include search-info.html %}
      </div>

      {% include list.html data="citations" component="citation" style="rich" %}

    </section>

  </div>

</div>
