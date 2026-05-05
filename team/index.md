---
title: Team
nav:
  order: 3
  tooltip: About our team
---

<style>
.team-page {
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

/* HERO */

.team-hero {
  width: min(1180px, calc(100% - 44px));
  margin: 64px auto 84px;
}

.team-kicker,
.section-kicker {
  margin: 0 0 16px;
  color: var(--berry);
  font-size: 0.76rem;
  font-weight: 900;
  letter-spacing: 0.15em;
  text-transform: uppercase;
}

.team-title {
  max-width: 1060px;
  margin: 0;
  color: var(--navy);
  font-size: clamp(2.8rem, 6vw, 6.2rem);
  line-height: 0.92;
  letter-spacing: -0.075em;
  font-weight: 950;
}

.team-title span {
  display: block;
  color: var(--teal);
}

.team-lead {
  max-width: 880px;
  margin: 30px 0 0;
  color: rgba(16, 32, 51, 0.78);
  font-size: clamp(1.05rem, 1.35vw, 1.24rem);
  line-height: 1.75;
}

.team-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 34px;
}

.team-actions a {
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

.team-actions a.secondary {
  color: var(--navy);
  background: #ffffff;
  border: 1px solid var(--line);
}

.team-actions a:hover {
  color: #ffffff;
  background: var(--teal);
  transform: translateY(-2px);
}

/* INTRO STATEMENT */

.team-statement {
  width: min(1180px, calc(100% - 44px));
  margin: 0 auto 90px;
  padding: 46px 0;
  display: grid;
  grid-template-columns: 150px 1fr;
  gap: 42px;
  border-top: 1px solid var(--line);
  border-bottom: 1px solid var(--line);
}

.statement-number {
  color: rgba(143, 32, 72, 0.20);
  font-size: 5rem;
  font-weight: 950;
  line-height: 1;
  letter-spacing: -0.08em;
}

.team-statement h2 {
  max-width: 920px;
  margin: 0;
  color: var(--navy);
  font-size: clamp(2rem, 3.5vw, 3.8rem);
  line-height: 1.03;
  letter-spacing: -0.055em;
}

.team-statement p {
  max-width: 860px;
  margin: 22px 0 0;
  color: var(--muted);
  font-size: 1.06rem;
  line-height: 1.72;
}

/* SECTION HEADINGS */

.members-block,
.join-section,
.alumni-block,
.support-block {
  width: min(1180px, calc(100% - 44px));
  margin-left: auto;
  margin-right: auto;
}

.section-title {
  max-width: 820px;
  margin: 0;
  color: var(--navy);
  font-size: clamp(2rem, 3.5vw, 3.8rem);
  line-height: 1.03;
  letter-spacing: -0.055em;
}

.section-heading {
  margin-bottom: 34px;
}

/* MEMBER GROUPS */

.members-block {
  margin-bottom: 96px;
}

.member-stack {
  display: grid;
  gap: 22px;
}

.member-section {
  position: relative;
  overflow: hidden;
  padding: 32px;
  border-radius: 34px;
  border: 1px solid var(--line);
  background:
    linear-gradient(180deg, rgba(255, 255, 255, 0.98), rgba(248, 251, 253, 0.94));
  box-shadow: 0 24px 70px rgba(7, 29, 53, 0.07);
}

.member-section::before {
  content: "";
  position: absolute;
  width: 170px;
  height: 170px;
  right: -70px;
  top: -70px;
  border-radius: 999px;
  background: rgba(15, 166, 166, 0.11);
}

.member-section.pi {
  background:
    radial-gradient(circle at 90% 10%, rgba(15, 166, 166, 0.18), transparent 34%),
    linear-gradient(145deg, #ffffff, #f2faf9);
}

.member-section h3 {
  position: relative;
  z-index: 1;
  margin: 0 0 24px;
  color: var(--navy);
  font-size: clamp(1.35rem, 2vw, 2rem);
  line-height: 1.15;
  letter-spacing: -0.04em;
}

.member-section > * {
  position: relative;
  z-index: 1;
}

/* JOIN PANEL */

.join-section {
  margin-bottom: 92px;
}

.join-panel {
  position: relative;
  overflow: hidden;
  padding: 58px;
  border-radius: 36px;
  color: #ffffff;
  background:
    radial-gradient(circle at 84% 18%, rgba(15, 166, 166, 0.30), transparent 34%),
    linear-gradient(135deg, #68153d 0%, #071d35 68%, #064f5d 100%);
}

.join-panel::after {
  content: "";
  position: absolute;
  inset: 0;
  background-image:
    linear-gradient(rgba(255, 255, 255, 0.045) 1px, transparent 1px),
    linear-gradient(90deg, rgba(255, 255, 255, 0.045) 1px, transparent 1px);
  background-size: 52px 52px;
  mask-image: linear-gradient(90deg, transparent, black 20%, black 80%, transparent);
}

.join-panel > * {
  position: relative;
  z-index: 1;
}

.join-panel h2 {
  max-width: 860px;
  margin: 0;
  color: #ffffff;
  font-size: clamp(2rem, 3.5vw, 3.8rem);
  line-height: 1.03;
  letter-spacing: -0.055em;
}

.join-panel p {
  max-width: 860px;
  margin: 22px 0 0;
  color: rgba(255, 255, 255, 0.78);
  font-size: 1.05rem;
  line-height: 1.72;
}

.join-panel a {
  display: inline-flex;
  align-items: center;
  min-height: 42px;
  margin-top: 28px;
  padding: 0 16px;
  border-radius: 999px;
  color: var(--navy);
  background: #ffffff;
  text-decoration: none;
  font-weight: 900;
  transition: all 0.2s ease;
}

.join-panel a:hover {
  color: #ffffff;
  background: var(--teal);
  transform: translateY(-2px);
}

/* ALUMNI */

.alumni-block {
  margin-bottom: 96px;
}

/* SUPPORT */

.support-block {
  margin-bottom: 80px;
}

.funding-card {
  margin-top: 28px;
  padding: 34px;
  border-radius: 34px;
  border: 1px solid var(--line);
  background: #ffffff;
  box-shadow: 0 24px 70px rgba(7, 29, 53, 0.07);
  display: flex;
  align-items: center;
  justify-content: center;
}

.funding-card img {
  max-width: 250px;
  width: 100%;
  height: auto;
  display: block;
  filter: grayscale(100%);
  opacity: 0.9;
  transition: all 0.25s ease;
}

.funding-card img:hover {
  filter: grayscale(0%);
  opacity: 1;
  transform: translateY(-3px);
}

/* RESPONSIVE */

@media (max-width: 900px) {
  .team-statement {
    grid-template-columns: 1fr;
  }

  .statement-number {
    font-size: 4rem;
  }

  .join-panel {
    padding: 42px 30px;
  }
}

@media (max-width: 640px) {
  .team-hero,
  .team-statement,
  .members-block,
  .join-section,
  .alumni-block,
  .support-block {
    width: min(100% - 30px, 1180px);
  }

  .team-hero {
    margin-top: 48px;
  }

  .team-actions a,
  .join-panel a {
    width: 100%;
    justify-content: center;
  }

  .member-section {
    padding: 26px 22px;
    border-radius: 28px;
  }

  .funding-card {
    padding: 28px 20px;
  }
}
</style>

<div class="team-page">

  <section class="team-hero">
    <p class="team-kicker">Team · Kaikkonen Lab</p>

    <h1 class="team-title">
      People behind
      <span>cardiovascular genomics</span>
    </h1>

    <p class="team-lead">
      We are an interdisciplinary team working across cardiovascular epigenomics,
      gene regulation, single-cell technologies, functional genomics, and
      computational biology to understand disease mechanisms and translate
      genetic discoveries into biological insight.
    </p>

    <div class="team-actions">
      <a href="#current-members">Current members</a>
      <a class="secondary" href="#alumni">Alumni</a>
      <a class="secondary" href="join">Interested in joining?</a>
    </div>
  </section>

  <section class="team-statement">
    <div class="statement-number">01</div>

    <div>
      <p class="team-kicker">Working culture</p>

      <h2>
        Experimental biology, computational analysis, and collaborative science.
      </h2>

      <p>
        Our lab brings together researchers with complementary expertise in
        molecular biology, genomics, vascular biology, data analysis, and disease
        interpretation. We value careful experimental design, transparent analysis,
        interdisciplinary collaboration, and mechanistic thinking.
      </p>
    </div>
  </section>

  <section id="current-members" class="members-block">
    <div class="section-heading">
      <p class="section-kicker">Current lab members</p>
      <h2 class="section-title">Meet the team</h2>
    </div>

    <div class="member-stack">

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

    </div>
  </section>

  <section class="join-section">
    <div class="join-panel">
      <p class="team-kicker">Opportunities</p>

      <h2>Interested in joining us?</h2>

      <p>
        We welcome motivated students and researchers interested in cardiovascular
        genomics, functional variant interpretation, gene regulation, single-cell
        technologies, and computational biology.
      </p>

      <a href="join">Learn about opportunities</a>
    </div>
  </section>

  <section id="alumni" class="alumni-block">
    <div class="section-heading">
      <p class="section-kicker">Former members</p>
      <h2 class="section-title">Alumni</h2>
    </div>

    <section class="member-section">
      {% include list.html data="members" component="portrait" filter="group == 'alumni'" style="small" %}
    </section>
  </section>

  <section class="support-block">
    <div class="section-heading">
      <p class="section-kicker">Support</p>
      <h2 class="section-title">Funding and institutional support</h2>
    </div>

    <div class="funding-card">
      <a href="https://www.uef.fi/fi" target="_blank">
        <img src="https://sites.uef.fi/europeanforestry/wp-content/uploads/sites/62/2020/05/UEF_eng_pysty_1_black-1024x892.jpg" alt="University of Eastern Finland">
      </a>
    </div>
  </section>

</div>
