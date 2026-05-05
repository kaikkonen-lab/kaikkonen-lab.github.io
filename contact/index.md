---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

<style>
.contact-page {
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

.contact-hero,
.contact-main,
.contact-info-section,
.contact-focus-section {
  width: min(1180px, calc(100% - 44px));
  margin-left: auto;
  margin-right: auto;
}

.contact-hero {
  margin-top: 64px;
  margin-bottom: 76px;
}

.contact-kicker,
.section-kicker {
  margin: 0 0 16px;
  color: var(--berry);
  font-size: 0.76rem;
  font-weight: 900;
  letter-spacing: 0.15em;
  text-transform: uppercase;
}

.contact-hero h1 {
  max-width: 1040px;
  margin: 0;
  color: var(--navy);
  font-size: clamp(2.8rem, 6vw, 6.3rem);
  line-height: 0.92;
  letter-spacing: -0.075em;
  font-weight: 950;
}

.contact-hero h1 span {
  display: block;
  color: var(--teal);
}

.contact-hero .lead {
  max-width: 860px;
  margin: 30px 0 0;
  color: rgba(16, 32, 51, 0.78);
  font-size: clamp(1.05rem, 1.35vw, 1.24rem);
  line-height: 1.75;
}

/* MAIN CONTACT CARD */

.contact-main {
  margin-bottom: 96px;
}

.contact-card {
  display: grid;
  grid-template-columns: 0.9fr 1.1fr;
  overflow: hidden;
  border-radius: 36px;
  border: 1px solid var(--line);
  background: #ffffff;
  box-shadow: 0 24px 70px rgba(7, 29, 53, 0.08);
}

.contact-panel {
  position: relative;
  min-height: 440px;
  padding: 42px;
  color: #ffffff;
  background:
    radial-gradient(circle at 22% 18%, rgba(15, 166, 166, 0.32), transparent 34%),
    radial-gradient(circle at 86% 78%, rgba(143, 32, 72, 0.32), transparent 34%),
    linear-gradient(135deg, #061625 0%, #071d35 60%, #064f5d 100%);
  overflow: hidden;
}

.contact-panel::after {
  content: "";
  position: absolute;
  inset: 0;
  background-image:
    linear-gradient(rgba(255, 255, 255, 0.045) 1px, transparent 1px),
    linear-gradient(90deg, rgba(255, 255, 255, 0.045) 1px, transparent 1px);
  background-size: 52px 52px;
  mask-image: linear-gradient(90deg, transparent, black 20%, black 80%, transparent);
}

.contact-panel > * {
  position: relative;
  z-index: 1;
}

.contact-panel h2 {
  max-width: 520px;
  margin: 0;
  color: #ffffff;
  font-size: clamp(2rem, 3.5vw, 3.8rem);
  line-height: 1.03;
  letter-spacing: -0.055em;
}

.contact-panel p {
  max-width: 520px;
  margin: 22px 0 0;
  color: rgba(255, 255, 255, 0.76);
  font-size: 1.04rem;
  line-height: 1.72;
}

.contact-details {
  padding: 42px;
  display: grid;
  gap: 18px;
  align-content: center;
}

.contact-item {
  display: grid;
  grid-template-columns: 120px 1fr;
  gap: 22px;
  padding: 22px 0;
  border-bottom: 1px solid var(--line);
}

.contact-item:last-child {
  border-bottom: 0;
}

.contact-label {
  color: var(--berry);
  font-size: 0.76rem;
  font-weight: 900;
  letter-spacing: 0.13em;
  text-transform: uppercase;
}

.contact-value {
  color: var(--navy);
  font-size: 1.06rem;
  line-height: 1.55;
}

.contact-value strong {
  display: block;
  margin-bottom: 4px;
  color: var(--navy);
  font-size: 1.15rem;
}

.contact-value a {
  color: var(--navy);
  text-decoration: none;
  font-weight: 850;
  border-bottom: 1px solid rgba(15, 166, 166, 0.38);
}

.contact-value a:hover {
  color: var(--teal);
}

/* INFO SECTIONS */

.contact-info-section {
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

.info-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  border-top: 1px solid var(--line);
  border-left: 1px solid var(--line);
}

.info-card {
  min-height: 260px;
  padding: 34px 30px;
  background: #ffffff;
  border-right: 1px solid var(--line);
  border-bottom: 1px solid var(--line);
}

.info-card h3 {
  margin: 0 0 16px;
  color: var(--navy);
  font-size: 1.35rem;
  line-height: 1.18;
  letter-spacing: -0.035em;
}

.info-card p {
  margin: 0;
  color: var(--muted);
  line-height: 1.72;
}

.info-card address {
  margin: 0;
  color: var(--muted);
  font-style: normal;
  line-height: 1.72;
}

.info-card strong {
  color: var(--navy);
}

/* FOCUS / ENQUIRIES */

.contact-focus-section {
  margin-bottom: 80px;
}

.focus-panel {
  position: relative;
  overflow: hidden;
  padding: 58px;
  border-radius: 36px;
  color: #ffffff;
  background:
    radial-gradient(circle at 84% 18%, rgba(15, 166, 166, 0.30), transparent 34%),
    linear-gradient(135deg, #68153d 0%, #071d35 68%, #064f5d 100%);
}

.focus-panel::after {
  content: "";
  position: absolute;
  inset: 0;
  background-image:
    linear-gradient(rgba(255, 255, 255, 0.045) 1px, transparent 1px),
    linear-gradient(90deg, rgba(255, 255, 255, 0.045) 1px, transparent 1px);
  background-size: 52px 52px;
  mask-image: linear-gradient(90deg, transparent, black 20%, black 80%, transparent);
}

.focus-panel > * {
  position: relative;
  z-index: 1;
}

.focus-panel h2 {
  max-width: 860px;
  margin: 0;
  color: #ffffff;
  font-size: clamp(2rem, 3.5vw, 3.8rem);
  line-height: 1.03;
  letter-spacing: -0.055em;
}

.focus-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 22px;
  margin-top: 34px;
}

.focus-card {
  padding: 26px 24px;
  border-radius: 26px;
  background: rgba(255, 255, 255, 0.10);
  border: 1px solid rgba(255, 255, 255, 0.18);
  backdrop-filter: blur(14px);
}

.focus-card h3 {
  margin: 0 0 12px;
  color: #ffffff;
  font-size: 1.15rem;
  line-height: 1.22;
}

.focus-card p {
  margin: 0;
  color: rgba(255, 255, 255, 0.74);
  line-height: 1.65;
}

/* RESPONSIVE */

@media (max-width: 900px) {
  .contact-card,
  .info-grid,
  .focus-grid {
    grid-template-columns: 1fr;
  }

  .contact-panel {
    min-height: auto;
  }
}

@media (max-width: 640px) {
  .contact-hero,
  .contact-main,
  .contact-info-section,
  .contact-focus-section {
    width: min(100% - 30px, 1180px);
  }

  .contact-hero {
    margin-top: 48px;
  }

  .contact-panel,
  .contact-details,
  .focus-panel {
    padding: 34px 24px;
  }

  .contact-item {
    grid-template-columns: 1fr;
    gap: 8px;
  }
}
</style>

<div class="contact-page">

  <section class="contact-hero">
    <p class="contact-kicker">Contact · Kaikkonen Lab</p>

    <h1>
      Get in touch with
      <span>Cardiovascular Genomics</span>
    </h1>

    <p class="lead">
      The Cardiovascular Genomics — Kaikkonen Lab is based at the
      A. I. Virtanen Institute for Molecular Sciences, University of Eastern
      Finland, Kuopio campus.
    </p>
  </section>

  <section class="contact-main">
    <div class="contact-card">

      <div class="contact-panel">
        <p class="contact-kicker">Principal contact</p>

        <h2>
          Research collaborations, student enquiries, and joining the group.
        </h2>

        <p>
          For research collaborations, student enquiries, and questions about
          joining the group, please contact Professor Minna Kaikkonen-Määttä.
        </p>
      </div>

      <div class="contact-details">

        <div class="contact-item">
          <div class="contact-label">Email</div>
          <div class="contact-value">
            <a href="mailto:minna.kaikkonen@uef.fi">minna.kaikkonen@uef.fi</a>
          </div>
        </div>

        <div class="contact-item">
          <div class="contact-label">Phone</div>
          <div class="contact-value">
            <a href="tel:+358403552413">+358 40 355 2413</a>
          </div>
        </div>

        <div class="contact-item">
          <div class="contact-label">Location</div>
          <div class="contact-value">
            <a href="https://www.google.com/maps/search/?api=1&query=University%20of%20Eastern%20Finland%20A.%20I.%20Virtanen%20Institute%20Kuopio" target="_blank">
              Kuopio campus, University of Eastern Finland
            </a>
          </div>
        </div>

      </div>

    </div>
  </section>

  <section class="contact-info-section">
    <div class="section-heading">
      <p class="section-kicker">Visit us</p>
      <h2>Address and affiliation</h2>
    </div>

    <div class="info-grid">

      <article class="info-card">
        <h3>Address</h3>

        <address>
          <strong>Cardiovascular Genomics — Kaikkonen Lab</strong><br>
          A. I. Virtanen Institute for Molecular Sciences<br>
          University of Eastern Finland<br>
          P. O. Box 1627<br>
          FI-70211 Kuopio<br>
          Finland
        </address>
      </article>

      <article class="info-card">
        <h3>Principal Investigator</h3>

        <p>
          <strong>Professor Minna Kaikkonen-Määttä</strong><br>
          Professor of Cardiovascular Genomics<br>
          Deputy Head of Department<br>
          Director, Single Cell Genomics Core<br>
          A. I. Virtanen Institute for Molecular Sciences<br>
          University of Eastern Finland
        </p>
      </article>

    </div>
  </section>

  <section class="contact-focus-section">
    <div class="focus-panel">
      <p class="contact-kicker">Enquiries</p>

      <h2>
        Areas for collaboration and prospective lab members
      </h2>

      <div class="focus-grid">

        <article class="focus-card">
          <h3>Research focus</h3>
          <p>
            We investigate atherosclerotic cardiovascular disease and
            cardiometabolic disease using genetic model systems, single-cell
            transcriptomics, epigenetics, high-throughput functional genomics,
            and bioinformatics.
          </p>
        </article>

        <article class="focus-card">
          <h3>Collaborations</h3>
          <p>
            We welcome enquiries related to cardiovascular genomics, functional
            fine-mapping, disease-associated variants, single-cell multiomics,
            spatial transcriptomics, and gene-regulatory mechanisms.
          </p>
        </article>

        <article class="focus-card">
          <h3>Joining the lab</h3>
          <p>
            Prospective students and researchers are encouraged to email Minna
            with a short description of their research interests, background,
            and potential fit with the group.
          </p>
        </article>

      </div>
    </div>
  </section>

</div>
