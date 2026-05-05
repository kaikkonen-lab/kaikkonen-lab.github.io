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

.home-pathway {
  position: relative;
  overflow: hidden;
  padding: 3.2rem 2rem;
  border-radius: 34px;
  background:
    radial-gradient(circle at 14% 18%, rgba(0, 210, 190, 0.30), transparent 28%),
    radial-gradient(circle at 86% 12%, rgba(180, 60, 120, 0.25), transparent 30%),
    linear-gradient(135deg, #061b3a 0%, #083e67 52%, #0a6265 100%);
  color: white;
  margin: 1rem 0 3rem;
}

.home-pathway::before {
  content: "";
  position: absolute;
  inset: -80px;
  background:
    linear-gradient(120deg, transparent 0%, rgba(255,255,255,0.10) 45%, transparent 70%);
  transform: translateX(-70%);
  animation: shimmer 7s infinite;
}

.home-pathway::after {
  content: "";
  position: absolute;
  right: -120px;
  bottom: -140px;
  width: 420px;
  height: 420px;
  border-radius: 50%;
  border: 36px solid rgba(255,255,255,0.08);
}

@keyframes shimmer {
  0% { transform: translateX(-70%); }
  45% { transform: translateX(70%); }
  100% { transform: translateX(70%); }
}

.home-kicker {
  position: relative;
  z-index: 1;
  color: #70fff2;
  font-weight: 900;
  letter-spacing: .1em;
  text-transform: uppercase;
  font-size: .82rem;
}

.home-heading {
  position: relative;
  z-index: 1;
  color: white;
  font-size: clamp(2.3rem, 5vw, 4.7rem);
  line-height: 1.04;
  max-width: 980px;
  margin: .4rem 0 1rem;
}

.home-lead {
  position: relative;
  z-index: 1;
  max-width: 930px;
  font-size: 1.18rem;
  line-height: 1.75;
  color: rgba(255,255,255,0.92);
  margin-bottom: 1.5rem;
}

.home-actions {
  position: relative;
  z-index: 1;
  display: flex;
  flex-wrap: wrap;
  gap: .8rem;
  margin: 1.4rem 0 2rem;
}

.home-actions a {
  color: white;
  text-decoration: none;
  border: 1px solid rgba(255,255,255,0.38);
  background: rgba(255,255,255,0.13);
  padding: .7rem 1rem;
  border-radius: 999px;
  font-weight: 800;
  transition: all .25s ease;
}

.home-actions a:hover {
  background: white;
  color: var(--navy);
  transform: translateY(-3px);
}

.pathway-grid {
  position: relative;
  z-index: 1;
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  gap: .9rem;
  margin-top: 1.4rem;
}

.pathway-step {
  position: relative;
  text-align: center;
  padding: 1.15rem .9rem;
  border-radius: 22px;
  background: rgba(255,255,255,0.12);
  border: 1px solid rgba(255,255,255,0.24);
  backdrop-filter: blur(8px);
  transition: transform .25s ease, background .25s ease, box-shadow .25s ease;
}

.pathway-step:hover {
  transform: translateY(-8px) scale(1.02);
  background: rgba(255,255,255,0.20);
  box-shadow: 0 18px 40px rgba(0,0,0,0.18);
}

.pathway-step .icon {
  font-size: 2rem;
  margin-bottom: .5rem;
  animation: floatIcon 4s ease-in-out infinite;
}

.pathway-step:nth-child(2) .icon { animation-delay: .4s; }
.pathway-step:nth-child(3) .icon { animation-delay: .8s; }
.pathway-step:nth-child(4) .icon { animation-delay: 1.2s; }
.pathway-step:nth-child(5) .icon { animation-delay: 1.6s; }

@keyframes floatIcon {
  0%, 100% { transform: translateY(0); }
  50% { transform: translateY(-6px); }
}

.pathway-step strong {
  display: block;
  color: white;
  margin-bottom: .35rem;
}

.pathway-step span {
  display: block;
  color: rgba(255,255,255,0.80);
  font-size: .9rem;
  line-height: 1.4;
}

.page-heading {
  color: var(--navy);
  font-size: 2.15rem;
  margin: .35rem 0 1rem;
}

.page-kicker {
  color: var(--teal);
  font-weight: 900;
  letter-spacing: .08em;
  text-transform: uppercase;
  font-size: .82rem;
  margin-top: 2.5rem;
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
  transition: transform .25s ease, box-shadow .25s ease;
}

.gateway-card:hover {
  transform: translateY(-7px);
  box-shadow: 0 22px 46px rgba(6, 38, 79, 0.15);
}

.gateway-card img {
  width: 100%;
  height: 150px;
  object-fit: cover;
  display: block;
  transition: transform .45s ease;
}

.gateway-card:hover img {
  transform: scale(1.06);
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
  font-size: 1.22rem;
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

@media (max-width: 950px) {
  .pathway-grid,
  .gateway-grid {
    grid-template-columns: 1fr;
  }

  .home-pathway {
    padding: 2.6rem 1.4rem;
  }
}
</style>

<div class="home-page">

<section class="home-pathway">
  <div class="home-kicker">Discovery pipeline</div>

  <div class="home-heading">A connected path from genetics to cardiovascular translation</div>

  <p class="home-lead">
    The Kaikkonen Lab investigates how genetic and epigenomic regulatory mechanisms shape atherosclerotic cardiovascular disease and cardiometabolic risk. We connect disease-associated genetic variation to regulatory mechanisms, cellular states, and biological function using functional genomics, single-cell technologies, multi-omics, and computational biology.
  </p>

  <div class="home-actions">
    <a href="research/">Explore research</a>
    <a href="projects/">View projects</a>
    <a href="team/">Meet the team</a>
  </div>

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

<div class="page-kicker">Explore</div>
<div class="page-heading">Learn more about our work</div>

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

<section class="quote-panel">
  <blockquote>
    <p>“Science and everyday life cannot and should not be separated.”</p>
    <cite>— Rosalind Franklin</cite>
  </blockquote>
</section>

</div>
