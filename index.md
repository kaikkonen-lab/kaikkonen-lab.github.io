---
title: Home
---

<style>
.home-page {
  --navy: #061b3a;
  --blue: #0b5570;
  --teal: #00a6a6;
  --berry: #7b1e4a;
  --ink: #102033;
  --muted: #5f7185;
  --line: #dce8ef;
  --soft: #f7fbfd;
}

.home-hero {
  position: relative;
  overflow: hidden;
  border-radius: 34px;
  padding: 4.8rem 2.4rem;
  color: white;
  background:
    radial-gradient(circle at 15% 20%, rgba(0, 210, 190, 0.33), transparent 28%),
    radial-gradient(circle at 85% 10%, rgba(180, 60, 120, 0.28), transparent 30%),
    linear-gradient(135deg, #061b3a 0%, #083e67 52%, #0a6265 100%);
  margin: 1rem 0 3rem;
}

.home-hero::after {
  content: "";
  position: absolute;
  right: -130px;
  bottom: -150px;
  width: 440px;
  height: 440px;
  border-radius: 50%;
  border: 36px solid rgba(255,255,255,0.08);
}

.home-hero h1 {
  position: relative;
  z-index: 1;
  color: white;
  max-width: 980px;
  font-size: clamp(2.5rem, 5vw, 5.2rem);
  line-height: 1.02;
  margin: 0 0 1.2rem;
}

.home-hero p {
  position: relative;
  z-index: 1;
  max-width: 900px;
  font-size: 1.22rem;
  line-height: 1.75;
  color: rgba(255,255,255,0.92);
}

.home-actions {
  position: relative;
  z-index: 1;
  display: flex;
  flex-wrap: wrap;
  gap: .8rem;
  margin-top: 1.8rem;
}

.home-actions a {
  color: white;
  text-decoration: none;
  border: 1px solid rgba(255,255,255,0.38);
  background: rgba(255,255,255,0.13);
  padding: .7rem 1rem;
  border-radius: 999px;
  font-weight: 800;
}

.home-actions a:hover {
  background: white;
  color: var(--navy);
}

.home-kicker {
  color: var(--teal);
  font-weight: 900;
  letter-spacing: .08em;
  text-transform: uppercase;
  font-size: .82rem;
  margin-top: 2.5rem;
}

.home-heading {
  color: var(--navy);
  font-size: 2.25rem;
  margin: .35rem 0 1rem;
}

.focus-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1.1rem;
  margin: 1.5rem 0 3rem;
}

.focus-card {
  background: white;
  border: 1px solid var(--line);
  border-radius: 26px;
  padding: 1.5rem;
  box-shadow: 0 12px 30px rgba(6, 38, 79, 0.08);
  transition: transform .25s ease, box-shadow .25s ease;
}

.focus-card:hover {
  transform: translateY(-6px);
  box-shadow: 0 20px 42px rgba(6, 38, 79, 0.14);
}

.focus-icon {
  display: inline-flex;
  width: 54px;
  height: 54px;
  border-radius: 18px;
  align-items: center;
  justify-content: center;
  background: #e9f7f6;
  font-size: 1.8rem;
  margin-bottom: .8rem;
}

.focus-card h3 {
  color: var(--navy);
  margin: .2rem 0 .5rem;
}

.focus-card p {
  color: var(--muted);
  line-height: 1.65;
}

.home-pathway {
  padding: 2rem;
  border-radius: 30px;
  background: linear-gradient(180deg, #ffffff, #f7fbfd);
  border: 1px solid var(--line);
  box-shadow: 0 14px 34px rgba(6, 38, 79, 0.07);
  margin: 2rem 0 3rem;
}

.pathway-grid {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  gap: .9rem;
  margin-top: 1rem;
}

.pathway-step {
  text-align: center;
  padding: 1rem;
  border-radius: 20px;
  background: white;
  border: 1px solid var(--line);
}

.pathway-step .icon {
  font-size: 2rem;
  margin-bottom: .5rem;
}

.pathway-step strong {
  display: block;
  color: var(--navy);
  margin-bottom: .3rem;
}

.pathway-step span {
  display: block;
  color: var(--muted);
  font-size: .9rem;
  line-height: 1.4;
}

.quote-panel {
  padding: 2.2rem;
  border-radius: 30px;
  color: white;
  background:
    radial-gradient(circle at 85% 20%, rgba(0, 200, 190, .30), transparent 32%),
    linear-gradient(135deg, #68153d, #061b3a 72%);
  margin: 3rem 0;
}

.quote-panel blockquote {
  margin: 0;
  border-left: 0;
  padding: 0;
}

.quote-panel p {
  color: rgba(255,255,255,.93);
  font-size: 1.25rem;
  line-height: 1.7;
  margin: 0;
}

.quote-panel cite {
  display: block;
  margin-top: 1rem;
  color: rgba(255,255,255,.75);
  font-style: normal;
  font-weight: 700;
}

.gateway-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1.2rem;
  margin: 1.5rem 0 3rem;
}

.gateway-card {
  position: relative;
  overflow: hidden;
  min-height: 280px;
  border-radius: 30px;
  border: 1px solid var(--line);
  background: white;
  box-shadow: 0 14px 34px rgba(6, 38, 79, 0.08);
}

.gateway-card img {
  width: 100%;
  height: 150px;
  object-fit: cover;
  display: block;
}

.gateway-content {
  padding: 1.3rem;
}

.gateway-content h3 {
  color: var(--navy);
  margin: 0 0 .5rem;
}

.gateway-content p {
  color: var(--muted);
  line-height: 1.6;
}

.gateway-content a {
  display: inline-block;
  margin-top: .5rem;
  color: var(--navy);
  font-weight: 900;
  text-decoration: none;
}

.gateway-content a:hover {
  color: var(--teal);
}

@media (max-width: 950px) {
  .focus-grid,
  .pathway-grid,
  .gateway-grid {
    grid-template-columns: 1fr;
  }

  .home-hero {
    padding: 3.3rem 1.5rem;
  }
}
</style>

<div class="home-page">

<section class="home-hero">
  <h1>Decoding cardiovascular disease through regulatory genomics</h1>

  <p>
    The Kaikkonen Lab investigates how genetic and epigenomic regulatory mechanisms shape atherosclerotic cardiovascular disease and cardiometabolic risk. We combine cellular and genetic model systems, single-cell transcriptomics, epigenomics, high-throughput functional genomics, and computational biology to uncover disease-relevant regulatory mechanisms.
  </p>

  <div class="home-actions">
    <a href="research/">Explore research</a>
    <a href="projects/">View projects</a>
    <a href="team/">Meet the team</a>
  </div>
</section>

<div class="home-kicker">Research focus</div>
<div class="home-heading">From variants to mechanisms</div>

<div class="focus-grid">
  <div class="focus-card">
    <span class="focus-icon">🧬</span>
    <h3>Functional genomics</h3>
    <p>Mapping regulatory variants, enhancers, and non-coding mechanisms linked to cardiovascular disease.</p>
  </div>

  <div class="focus-card">
    <span class="focus-icon">❤️</span>
    <h3>Cardiovascular biology</h3>
    <p>Studying vascular, immune, and disease-relevant cellular programs that contribute to atherosclerosis.</p>
  </div>

  <div class="focus-card">
    <span class="focus-icon">📊</span>
    <h3>Computational multi-omics</h3>
    <p>Integrating genetic, epigenomic, single-cell, spatial, and functional data to interpret disease risk.</p>
  </div>
</div>

<section class="home-pathway">
  <div class="home-kicker">Discovery pipeline</div>
  <div class="home-heading">A connected path from genetics to translation</div>

  <div class="pathway-grid">
    <div class="pathway-step">
      <div class="icon">🧬</div>
      <strong>Genetic risk</strong>
      <span>GWAS loci and disease-associated variants</span>
    </div>

    <div class="pathway-step">
      <div class="icon">🎯</div>
      <strong>Prioritization</strong>
      <span>Causal regulatory variant discovery</span>
    </div>

    <div class="pathway-step">
      <div class="icon">🔬</div>
      <strong>Validation</strong>
      <span>MPRA, CRISPR, and cellular models</span>
    </div>

    <div class="pathway-step">
      <div class="icon">🧫</div>
      <strong>Cell states</strong>
      <span>Single-cell and spatial disease biology</span>
    </div>

    <div class="pathway-step">
      <div class="icon">🫀</div>
      <strong>Translation</strong>
      <span>Mechanisms, prediction, and therapeutic insight</span>
    </div>
  </div>
</section>

<section class="quote-panel">
  <blockquote>
    <p>“Science and everyday life cannot and should not be separated.”</p>
    <cite>— Rosalind Franklin</cite>
  </blockquote>
</section>

<div class="home-kicker">Explore</div>
<div class="home-heading">Learn more about our work</div>

<div class="gateway-grid">
  <div class="gateway-card">
    <img src="images/research_logo.png" alt="Research graphic">
    <div class="gateway-content">
      <h3>Research</h3>
      <p>Explore the lab’s scientific themes in cardiovascular genomics, gene regulation, epigenomics, and variant interpretation.</p>
      <a href="research/">Explore research →</a>
    </div>
  </div>

  <div class="gateway-card">
    <img src="images/projects.png" alt="Projects graphic">
    <div class="gateway-content">
      <h3>Projects</h3>
      <p>Browse ongoing and foundational projects linking genetic discovery, regulatory function, cellular context, and translation.</p>
      <a href="projects/">Browse projects →</a>
    </div>
  </div>

  <div class="gateway-card">
    <img src="images/team.jpg" alt="Team photo">
    <div class="gateway-content">
      <h3>Team</h3>
      <p>Meet the interdisciplinary researchers working across cardiovascular biology, functional genomics, and computational analysis.</p>
      <a href="team/">Meet the team →</a>
    </div>
  </div>
</div>

</div>
