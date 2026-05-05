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

.publications-section {
  margin-top: 60px;
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

    <section id="publications" class="publications-section">

      <p class="section-kicker">Publication database</p>

      <h2 class="section-title">
        Recent publications
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
