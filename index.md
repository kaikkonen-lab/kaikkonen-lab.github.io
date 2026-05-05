---
title: Home
---

<style>
/* ================================
   GLOBAL THEME
================================ */
.home-page {
  --navy: #061b3a;
  --blue: #0b5570;
  --teal: #00a6a6;
  --berry: #7b1e4a;
  --ink: #102033;
  --muted: #5f7185;
  --line: #dce8ef;
}

/* ================================
   ULTRA-WIDE HEADER (FIXED)
================================ */
header,
.header,
.banner,
.hero {
  height: 260px !important;
  overflow: hidden;
}

header img,
.header img,
.banner img,
.hero img,
header picture img,
.header picture img,
.banner picture img,
.hero picture img {
  width: 100%;
  height: 100%;
  object-fit: cover;

  /* crop top + bottom */
  object-position: center 45%;

  /* subtle polish */
  filter: brightness(0.92) contrast(1.05);
}

/* ================================
   INTRO SECTION
================================ */
.home-open {
  display: grid;
  grid-template-columns: 1.15fr .85fr;
  gap: 2rem;
  align-items: center;
  padding: 2rem 0 2.5rem;
}

.home-title {
  font-size: clamp(2.3rem, 5vw, 4.8rem);
  line-height: 1.05;
  color: var(--navy);
  margin-bottom: 1rem;
}

.home-title span {
  color: var(--teal);
}

.home-lead {
  font-size: 1.15rem;
  line-height: 1.75;
  color: var(--ink);
  max-width: 820px;
}

.home-actions {
  display: flex;
  flex-wrap: wrap;
  gap: .7rem;
  margin-top: 1.4rem;
}

.home-actions a {
  padding: .7rem 1rem;
  border-radius: 999px;
  font-weight: 800;
  background: var(--navy);
  color: white;
  text-decoration: none;
  transition: .25s ease;
}

.home-actions a.secondary {
  background: white;
  color: var(--navy);
  border: 1px solid var(--line);
}

.home-actions a:hover {
  background: var(--teal);
  transform: translateY(-3px);
}

/* ================================
   ORBIT VISUAL
================================ */
.research-orbit {
  position: relative;
  height: 320px;
  border-radius: 30px;
  background: linear-gradient(135deg, #f7fbfd, #eef6f9);
  border: 1px solid var(--line);
}

.orbit-ring {
  position: absolute;
  inset: 50px;
  border: 2px dashed rgba(11,85,112,.25);
  border-radius: 50%;
  animation: spin 30s linear infinite;
}

.orbit-heart {
  position: absolute;
  inset: 110px;
  border-radius: 50%;
  background: linear-gradient(135deg, var(--berry), #b43b6b);
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 3rem;
}

.orbit-node {
  position: absolute;
  width: 75px;
  height: 75px;
  border-radius: 20px;
  background: white;
  border: 1px solid var(--line);
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 1.8rem;
}

.orbit-node.n1 { top: 20px; left: 45%; }
.orbit-node.n2 { top: 110px; right: 20px; }
.orbit-node.n3 { bottom: 20px; right: 25%; }
.orbit-node.n4 { bottom: 60px; left: 25px; }
.orbit-node.n5 { top: 90px; left: 20px; }

@keyframes spin {
  from { transform: rotate(0deg); }
  to { transform: rotate(360deg); }
}

/* ================================
   FULL-WIDTH DISCOVERY BLOCK
================================ */
.discovery-full {
  position: relative;
  left: 50%;
  width: 100vw;
  margin-left: -50vw;
  margin-top: 2rem;
  margin-bottom: 3rem;
  padding: 3.2rem 1.5rem;

  background:
    linear-gradient(135deg, #061b3a 0%, #083e67 50%, #0a6265 100%);
  color: white;
}

.discovery-inner {
  max-width: 1200px;
  margin: auto;
}

.discovery-title {
  font-size: 2rem;
  margin-bottom: 1rem;
}

.discovery-strip {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  gap: .8rem;
}

.discovery-step {
  background: rgba(255,255,255,.12);
  border: 1px solid rgba(255,255,255,.25);
  padding: 1rem;
  border-radius: 20px;
  text-align: center;
  transition: .25s ease;
}

.discovery-step:hover {
  transform: translateY(-6px);
  background: rgba(255,255,255,.2);
}

.discovery-step .icon {
  font-size: 1.8rem;
  margin-bottom: .4rem;
}

/* ================================
   GATEWAY CARDS
================================ */
.gateway-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1rem;
}

.gateway-card {
  border-radius: 24px;
  overflow: hidden;
  border: 1px solid var(--line);
  background: white;
  transition: .25s ease;
}

.gateway-card:hover {
  transform: translateY(-6px);
}

.gateway-card img {
  width: 100%;
  height: 140px;
  object-fit: cover;
}

.gateway-content {
  padding: 1rem;
}

.gateway-content h3 {
  color: var(--navy);
}

.gateway-content a {
  font-weight: 800;
  text-decoration: none;
  color: var(--navy);
}

/* ================================
   MOBILE
================================ */
@media (max-width: 900px) {
  .home-open,
  .discovery-strip,
  .gateway-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="home-page">

<section class="home-open">
  <div>
    <h1 class="home-title">Regulatory genomics of <span>cardiovascular disease</span></h1>

    <p class="home-lead">
      The Kaikkonen Lab investigates how genetic and epigenomic regulatory mechanisms shape atherosclerotic cardiovascular disease and cardiometabolic risk.
    </p>

    <div class="home-actions">
      <a href="research/">Explore research</a>
      <a class="secondary" href="projects/">Projects</a>
      <a class="secondary" href="team/">Team</a>
    </div>
  </div>

  <div class="research-orbit">
    <div class="orbit-ring"></div>
    <div class="orbit-heart">♥</div>
    <div class="orbit-node n1">🧬</div>
    <div class="orbit-node n2">🔬</div>
    <div class="orbit-node n3">🧫</div>
    <div class="orbit-node n4">📊</div>
    <div class="orbit-node n5">🎯</div>
  </div>
</section>

<section class="discovery-full">
  <div class="discovery-inner">
    <div class="discovery-title">A connected path from genetics to disease</div>

    <div class="discovery-strip">
      <div class="discovery-step"><div class="icon">🧬</div>Genetic risk</div>
      <div class="discovery-step"><div class="icon">🎯</div>Prioritization</div>
      <div class="discovery-step"><div class="icon">🔬</div>Validation</div>
      <div class="discovery-step"><div class="icon">🧫</div>Cell states</div>
      <div class="discovery-step"><div class="icon">❤️</div>Translation</div>
    </div>
  </div>
</section>

<div class="gateway-grid">
  <div class="gateway-card">
    <img src="images/research_logo.png">
    <div class="gateway-content">
      <h3>Research</h3>
      <a href="research/">Explore →</a>
    </div>
  </div>

  <div class="gateway-card">
    <img src="images/projects.png">
    <div class="gateway-content">
      <h3>Projects</h3>
      <a href="projects/">Explore →</a>
    </div>
  </div>

  <div class="gateway-card">
    <img src="images/team.jpg">
    <div class="gateway-content">
      <h3>Team</h3>
      <a href="team/">Explore →</a>
    </div>
  </div>
</div>

</div>
