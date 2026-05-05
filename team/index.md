---
title: Team
nav:
  order: 3
  tooltip: About our team
---

<style>
.team-page {
  --navy: #061b3a;
  --blue: #0b5570;
  --teal: #00a6a6;
  --berry: #7b1e4a;
  --ink: #102033;
  --muted: #5f7185;
  --line: #dce8ef;
  --soft: #f7fbfd;
}

.team-open {
  display: grid;
  grid-template-columns: 1.15fr .85fr;
  gap: 2rem;
  align-items: center;
  padding: 2.3rem 0 3rem;
}

.team-title {
  font-size: clamp(2.5rem, 5vw, 5rem);
  line-height: 1.02;
  color: var(--navy);
  margin: 0 0 1rem;
}

.team-title span {
  color: var(--teal);
}

.team-lead {
  font-size: 1.18rem;
  line-height: 1.75;
  color: var(--ink);
  max-width: 850px;
}

.team-actions {
  display: flex;
  flex-wrap: wrap;
  gap: .8rem;
  margin-top: 1.5rem;
}

.team-actions a {
  text-decoration: none;
  padding: .75rem 1rem;
  border-radius: 999px;
  font-weight: 900;
  background: var(--navy);
  color: white;
  transition: all .25s ease;
}

.team-actions a.secondary {
  background: white;
  color: var(--navy);
  border: 1px solid var(--line);
}

.team-actions a:hover {
  background: var(--teal);
  color: white;
  transform: translateY(-3px);
}

.team-orbit {
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

.team-ring {
  position: absolute;
  inset: 55px;
  border: 2px dashed rgba(11, 85, 112, .28);
  border-radius: 50%;
  animation: rotateRing 28s linear infinite;
}

.team-ring.two {
  inset: 95px;
  animation-duration: 20s;
  animation-direction: reverse;
}

@keyframes rotateRing {
  from { transform: rotate(0deg); }
  to { transform: rotate(360deg); }
}

.team-center {
  position: absolute;
  inset: 125px;
  border-radius: 50%;
  background: linear-gradient(135deg, var(--berry), #b43b6b);
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 3.1rem;
  box-shadow: 0 18px 35px rgba(123, 30, 74, .25);
  animation: pulseTeam 3.5s ease-in-out infinite;
}

@keyframes pulseTeam {
  0%, 100% { transform: scale(1); }
  50% { transform: scale(1.06); }
}

.team-node {
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

.team-node.n1 { top: 35px; left: 45%; animation-delay: 0s; }
.team-node.n2 { top: 135px; right: 28px; animation-delay: .5s; }
.team-node.n3 { bottom: 35px; right: 25%; animation-delay: 1s; }
.team-node.n4 { bottom: 70px; left: 35px; animation-delay: 1.5s; }
.team-node.n5 { top: 105px; left: 40px; animation-delay: 2s; }

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

.team-values {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: .9rem;
  margin: 1.4rem 0 3rem;
}

.value-card {
  background: white;
  border: 1px solid var(--line);
  border-radius: 24px;
  padding: 1.2rem 1rem;
  text-align: center;
  box-shadow: 0 10px 26px rgba(6, 38, 79, 0.07);
  transition: all .25s ease;
}

.value-card:hover {
  transform: translateY(-7px);
  box-shadow: 0 18px 38px rgba(6, 38, 79, 0.13);
}

.value-card .icon {
  font-size: 2rem;
  margin-bottom: .45rem;
}

.value-card strong {
  display: block;
  color: var(--navy);
  margin-bottom: .3rem;
}

.value-card span {
  color: var(--muted);
  font-size: .9rem;
  line-height: 1.45;
}

.member-section {
  padding: 1.7rem;
  margin: 1.2rem 0 2rem;
  border-radius: 30px;
  border: 1px solid var(--line);
  background: linear-gradient(180deg, white, #f8fbfd);
  box-shadow: 0 12px 30px rgba(6, 38, 79, 0.06);
}

.member-section h3 {
  color: var(--navy);
  margin-top: 0;
  font-size: 1.45rem;
}

.member-section.pi {
  background:
    radial-gradient(circle at 90% 15%, rgba(0,166,166,.18), transparent 32%),
    linear-gradient(180deg, #ffffff, #f4fbfb);
}

.join-panel {
  padding: 2.3rem;
  border-radius: 30px;
  color: white;
  background:
    radial-gradient(circle at 85% 20%, rgba(0, 200, 190, .30), transparent 32%),
    linear-gradient(135deg, #68153d, #061b3a 72%);
  margin: 3rem 0;
}

.join-panel h2 {
  color: white;
  margin-top: 0;
  font-size: 2rem;
}

.join-panel p {
  color: rgba(255,255,255,.9);
  line-height: 1.7;
  max-width: 850px;
}

.join-panel a {
  display: inline-block;
  text-decoration: none;
  margin-top: .7rem;
  padding: .75rem 1rem;
  border-radius: 999px;
  background: white;
  color: var(--navy);
  font-weight: 900;
}

.join-panel a:hover {
  background: var(--teal);
  color: white;
}

.funding-card {
  border-radius: 28px;
  border: 1px solid var(--line);
  padding: 1.6rem;
  background: white;
  box-shadow: 0 12px 30px rgba(6, 38, 79, 0.07);
  margin: 1.2rem 0 3rem;
  text-align: center;
}

.funding-card img {
  max-width: 240px;
  height: auto;
  transition: transform .25s ease;
}

.funding-card img:hover {
  transform: scale(1.04);
}

@media (max-width: 950px) {
  .team-open,
  .team-values {
    grid-template-columns: 1fr;
  }

  .team-orbit {
    height: 310px;
  }

  .team-center {
    inset: 105px;
  }
}
</style>

<div class="team-page">

<section class="team-open">
  <div>
    <h1 class="team-title">People behind <span>cardiovascular genomics</span></h1>

    <p class="team-lead">
      We are an interdisciplinary team working across cardiovascular epigenomics, gene regulation, single-cell technologies, functional genomics, and computational biology to understand disease mechanisms and translate genetic discoveries into biological insight.
    </p>

    <div class="team-actions">
      <a href="#current-members">Current members</a>
      <a class="secondary" href="#alumni">Alumni</a>
      <a class="secondary" href="join">Interested in joining?</a>
    </div>
  </div>

  <div class="team-orbit">
    <div class="team-ring"></div>
    <div class="team-ring two"></div>
    <div class="team-center">👥</div>
    <div class="team-node n1">🧬</div>
    <div class="team-node n2">🔬</div>
    <div class="team-node n3">🧫</div>
    <div class="team-node n4">📊</div>
    <div class="team-node n5">❤️</div>
  </div>
</section>

<div class="section-kicker">How we work</div>
<div class="section-title">An interdisciplinary research culture</div>

<div class="team-values">
  <div class="value-card">
    <div class="icon">🧬</div>
    <strong>Genomics</strong>
    <span>From disease-associated variants to functional mechanisms.</span>
  </div>

  <div class="value-card">
    <div class="icon">🔬</div>
    <strong>Experimental biology</strong>
    <span>Cellular models, perturbation assays, and mechanistic validation.</span>
  </div>

  <div class="value-card">
    <div class="icon">🧫</div>
    <strong>Single-cell biology</strong>
    <span>Cell states, tissue context, and disease progression.</span>
  </div>

  <div class="value-card">
    <div class="icon">📊</div>
    <strong>Computation</strong>
    <span>Data integration, interpretation, and disease-focused modelling.</span>
  </div>
</div>

<div id="current-members" class="section-kicker">Current lab members</div>
<div class="section-title">Meet the team</div>

<section class="member-section pi">
  <h3>Principal Investigator</h3>
  {% include list.html data="members" component="portrait" filter="group == 'current' and role == 'principal-investigator'" %}
</section>

<section class="member-section">
  <h3>Senior Researchers</h3>
  {% include list.html data="members" component="portrait" filter="group == 'current' and role == 'senior-researcher'" %}
</section>

<section class="member-section">
  <h3>Postdoctoral Researchers</h3>
  {% include list.html data="members" component="portrait" filter="group == 'current' and role == 'postdoctoral-researcher'" %}
</section>

<section class="member-section">
  <h3>Doctoral Researchers</h3>
  {% include list.html data="members" component="portrait" filter="group == 'current' and role == 'doctoral-researcher'" %}
</section>

<section class="member-section">
  <h3>Technicians</h3>
  {% include list.html data="members" component="portrait" filter="group == 'current' and role == 'technician'" %}
</section>

<section class="member-section">
  <h3>Other Group Members</h3>
  {% include list.html data="members" component="portrait" filter="group == 'current' and role == 'other-group-member'" %}
</section>

<section class="join-panel">
  <h2>Interested in joining us?</h2>
  <p>
    We welcome motivated students and researchers interested in cardiovascular genomics, functional variant interpretation, gene regulation, single-cell technologies, and computational biology.
  </p>
  <a href="join">Learn about opportunities</a>
</section>

<div id="alumni" class="section-kicker">Former members</div>
<div class="section-title">Alumni</div>

<section class="member-section">
  {% include list.html data="members" component="portrait" filter="group == 'alumni'" style="small" %}
</section>

<div class="section-kicker">Support</div>
<div class="section-title">Funding and institutional support</div>

<div class="funding-card">
  <a href="https://www.uef.fi/fi" target="_blank">
    <img src="https://sites.uef.fi/europeanforestry/wp-content/uploads/sites/62/2020/05/UEF_eng_pysty_1_black-1024x892.jpg" alt="University of Eastern Finland">
  </a>
</div>

</div>
