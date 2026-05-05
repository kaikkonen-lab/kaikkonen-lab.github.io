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

.home-open {
  display: grid;
  grid-template-columns: 1.15fr .85fr;
  gap: 2rem;
  align-items: center;
  padding: 2.2rem 0 2.5rem;
}

.home-title {
  font-size: clamp(2.4rem, 5vw, 5rem);
  line-height: 1.02;
  color: var(--navy);
  margin: 0 0 1rem;
}

.home-title span {
  color: var(--teal);
}

.home-lead {
  font-size: 1.18rem;
  line-height: 1.75;
  color: var(--ink);
  max-width: 850px;
}

.home-actions {
  display: flex;
  flex-wrap: wrap;
  gap: .8rem;
  margin-top: 1.5rem;
}

.home-actions a {
  text-decoration: none;
  padding: .75rem 1rem;
  border-radius: 999px;
  font-weight: 900;
  background: var(--navy);
  color: white;
  transition: all .25s ease;
}

.home-actions a.secondary {
  background: white;
  color: var(--navy);
  border: 1px solid var(--line);
}

.home-actions a:hover {
  background: var(--teal);
  color: white;
  transform: translateY(-3px);
}

.research-orbit {
  position: relative;
  height: 360px;
  border-radius: 34px;
  background:
    radial-gradient(circle at center, rgba(0,166,166,.14), transparent 35%),
    linear-gradient(135deg, #f8fcfd, #eef7fa);
  border: 1px solid var(--line);
  overflow: hidden;
  box-shadow: 0 16px 38px rgba(6, 38, 79, 0.08);
}

.orbit-ring {
  position: absolute;
  inset: 55px;
  border: 2px dashed rgba(11, 85, 112, .28);
  border-radius: 50%;
  animation: rotateRing 28s linear infinite;
}

.orbit-ring.two {
  inset: 95px;
  animation-duration: 20s;
  animation-direction: reverse;
}

@keyframes rotateRing {
  from { transform: rotate(0deg); }
  to { transform: rotate(360deg); }
}

.orbit-heart {
  position: absolute;
  inset: 125px;
  border-radius: 50%;
  background: linear-gradient(135deg, var(--berry), #b43b6b);
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 3.3rem;
  box-shadow: 0 18px 35px rgba(123, 30, 74, .25);
  animation: pulseHeart 3.5s ease-in-out infinite;
}

@keyframes pulseHeart {
  0%, 100% { transform: scale(1); }
  50% { transform: scale(1.06); }
}

.orbit-node {
  position: absolute;
  width: 86px;
  height: 86px;
  border-radius: 24px;
  background: white;
  border: 1px solid var(--line);
  box-shadow: 0 12px 26px rgba(6, 38, 79, .10);
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 2rem;
  animation: floatNode 4s ease-in-out infinite;
}

.orbit-node.n1 { top: 35px; left: 45%; animation-delay: 0s; }
.orbit-node.n2 { top: 135px; right: 28px; animation-delay: .5s; }
.orbit-node.n3 { bottom: 35px; right: 25%; animation-delay: 1s; }
.orbit-node.n4 { bottom: 70px; left: 35px; animation-delay: 1.5s; }
.orbit-node.n5 { top: 105px; left: 40px; animation-delay: 2s; }

@keyframes floatNode {
  0%, 100% { transform: translateY(0); }
  50% { transform: translateY(-9px); }
}

.section-kicker {
  color: var(--teal);
  font-weight: 900;
  letter-spacing: .08em;
  text-transform: uppercase;
  font-size: .82rem;
  margin-top: 2.5rem;
}

.section-title {
  color: var(--navy);
  font-size: 2.15rem;
  margin: .3rem 0 1rem;
}

.discovery-strip {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  gap: .9rem;
  margin: 1.4rem 0 3rem;
}

.discovery-step {
  background: white;
  border: 1px solid var(--line);
  border-radius: 24px;
  padding: 1.2rem 1rem;
  text-align: center;
  box-shadow: 0 10px 26px rgba(6, 38, 79, 0.07);
  transition: all .25s ease;
}

.discovery-step:hover {
  transform: translateY(-7px);
  box-shadow: 0 18px 38px rgba(6, 38, 79, 0.13);
}

.discovery-step .icon {
  font-size: 2rem;
  margin-bottom: .45rem;
}

.discovery-step strong {
  display: block;
  color: var(--navy);
  margin-bottom: .3rem;
}

.discovery-step span {
  color: var(--muted);
  font-size: .9rem;
  line-height: 1.45;
}

.gateway-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1.2rem;
  margin: 1.5rem 0 3rem;
}

.gateway-card {
  overflow: hidden;
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
  height: 155px;
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
  .home-open,
  .discovery-strip,
  .gateway-grid {
    grid-template-columns: 1fr;
  }

  .research-orbit {
    height: 310px;
  }

  .orbit-heart {
    inset: 105px;
  }
}
</style>

<div class="home-page">

<section class="home-open">
  <div>
    <h1 class="home-title">Regulatory genomics of <span>cardiovascular disease</span></h1>

    <p class="home-lead">
      The Kaikkonen Lab investigates how genetic and epigenomic regulatory mechanisms shape atherosclerotic cardiovascular disease and cardiometabolic risk. We connect disease-associated genetic variation to regulatory mechanisms, cellular states, and biological function using functional genomics, single-cell technologies, multi-omics, and computational biology.
    </p>

    <div class="home-actions">
      <a href="research/">Explore research</a>
      <a class="secondary" href="projects/">View projects</a>
      <a class="secondary" href="team/">Meet the team</a>
    </div>
  </div>

  <div class="research-orbit">
    <div class="orbit-ring"></div>
    <div class="orbit-ring two"></div>
    <div class="orbit-heart">♥</div>
    <div class="orbit-node n1">🧬</div>
    <div class="orbit-node n2">🔬</div>
    <div class="orbit-node n3">🧫</div>
    <div class="orbit-node n4">📊</div>
    <div class="orbit-node n5">🎯</div>
  </div>
</section>

<div class="section-kicker">Discovery pipeline</div>
<div class="section-title">A connected path from genetics to cardiovascular translation</div>

<div class="discovery-strip">
  <div class="discovery-step">
    <div class="icon">🧬</div>
    <strong>Genetic risk</strong>
    <span>GWAS loci and disease-associated variants</span>
  </div>

  <div class="discovery-step">
    <div class="icon">🎯</div>
    <strong>Prioritization</strong>
    <span>Causal regulatory variant discovery</span>
  </div>

  <div class="discovery-step">
    <div class="icon">🔬</div>
    <strong>Validation</strong>
    <span>MPRA, CRISPR, and cellular models</span>
  </div>

  <div class="discovery-step">
    <div class="icon">🧫</div>
    <strong>Cell states</strong>
    <span>Single-cell and spatial disease biology</span>
  </div>

  <div class="discovery-step">
    <div class="icon">🫀</div>
    <strong>Translation</strong>
    <span>Mechanisms, prediction, and therapeutic insight</span>
  </div>
</div>

<div class="section-kicker">Explore</div>
<div class="section-title">Learn more about our work</div>

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
  <p>“Science and everyday life cannot and should not be separated.”</p>
  <cite>— Rosalind Franklin</cite>
</section>

</div>
