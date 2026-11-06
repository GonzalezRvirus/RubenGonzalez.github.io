---
layout: single
title: "Research funding & fellowships"
permalink: /funding/
author_profile: true
---

<style>
/* --- 1. EDITORIAL VARIABLES & TYPOGRAPHY --- */
:root {
  --ink-primary: #111827;       /* Casi negro, máxima legibilidad */
  --ink-secondary: #374151;     /* Gris carbón para subtítulos y proyectos */
  --ink-muted: #6b7280;         /* Gris medio para metadatos */
  --accent-editorial: #1e3a8a;  /* Azul marino académico */
  --accent-active: #065f46;     /* Verde bosque sobrio para proyectos activos */
  --rule-heavy: #111827;        /* Líneas divisorias principales */
  --rule-light: #e5e7eb;        /* Divisorias finas entre proyectos */
  --bg-subtle: #f9fafb;         /* Fondo sutil para hover */
  
  --font-serif: "Georgia", "Times New Roman", serif;
  --font-sans: -apple-system, BlinkMacSystemFont, "Inter", "Segoe UI", Roboto, sans-serif;
}

/* --- 2. LAYOUT FIX: REDUCE GAP WITH LEFT SIDEBAR --- */
.page, .archive {
  font-family: var(--font-sans);
  color: var(--ink-primary);
}

@media screen and (min-width: 1024px) {
  #main {
    max-width: 1240px;
  }
  .sidebar {
    width: 210px !important;
    margin-right: 28px !important;
  }
  .page, .archive {
    width: calc(100% - 245px) !important;
    padding-left: 0 !important;
    margin-left: 0 !important;
    float: left !important;
    max-width: 920px;
  }
}

/* --- 3. SECTION HEADERS --- */
.funding-section {
  margin-bottom: 42px;
}

.funding-section-header {
  border-bottom: 2px solid var(--rule-heavy);
  padding-bottom: 10px;
  margin-bottom: 20px;
  display: flex;
  justify-content: space-between;
  align-items: baseline;
}

.funding-section-header h2 {
  margin: 0;
  font-family: var(--font-serif);
  font-size: 1.42rem;
  font-weight: 400;
  color: var(--ink-primary);
  letter-spacing: -0.015em;
}

.funding-section-header span {
  font-size: 0.82rem;
  color: var(--ink-muted);
  text-transform: uppercase;
  letter-spacing: 0.05em;
}

/* --- 4. FUNDING ENTRIES (EDITORIAL TIMELINE) --- */
.funding-entry {
  padding: 18px 0 18px 18px;
  margin-left: 2px;
  border-left: 2px solid var(--rule-light);
  transition: border-color 0.2s ease, background-color 0.2s ease;
}

.funding-entry + .funding-entry {
  border-top: 1px solid #f3f4f6;
}

.funding-entry:hover {
  border-left-color: var(--accent-editorial);
  background-color: var(--bg-subtle);
}

.funding-entry.is-active {
  border-left-color: var(--accent-editorial);
}

.funding-header {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  gap: 16px;
  flex-wrap: wrap;
  margin-bottom: 4px;
}

.funding-title {
  font-size: 1.06rem;
  font-weight: 600;
  color: var(--ink-primary);
  margin: 0;
  line-height: 1.4;
}

.funding-meta-right {
  display: inline-flex;
  align-items: center;
  gap: 10px;
  font-variant-numeric: tabular-nums;
  flex-shrink: 0;
}

.funding-amount {
  font-size: 0.88rem;
  font-weight: 600;
  color: var(--ink-primary);
}

.funding-year {
  font-size: 0.88rem;
  color: var(--ink-muted);
}

.status-tag {
  font-size: 0.72rem;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 0.06em;
  color: var(--accent-active);
  background-color: #ecfdf5;
  border: 1px solid #a7f3d0;
  padding: 1px 7px;
  border-radius: 3px;
}

.funding-project {
  font-family: var(--font-serif);
  font-size: 0.98rem;
  color: var(--ink-secondary);
  font-style: italic;
  margin-bottom: 8px;
  line-height: 1.45;
}

.funding-project em {
  font-style: normal; /* Evita doble cursiva en nombres de especies dentro de títulos en cursiva */
  text-decoration: none;
}

.funding-details {
  font-size: 0.88rem;
  color: var(--ink-muted);
  line-height: 1.5;
  display: flex;
  flex-wrap: wrap;
  gap: 6px 18px;
}

.funding-details span strong {
  color: var(--ink-secondary);
  font-weight: 600;
}

/* --- 5. COMPACT LIST FOR HONORS & SHORT GRANTS --- */
.compact-awards-list {
  display: flex;
  flex-direction: column;
}

.compact-award {
  display: grid;
  grid-template-columns: 60px 1fr auto;
  gap: 16px;
  padding: 11px 0;
  border-bottom: 1px solid #f3f4f6;
  align-items: baseline;
  font-size: 0.92rem;
}

.compact-award:last-child {
  border-bottom: none;
}

.compact-year {
  font-variant-numeric: tabular-nums;
  color: var(--ink-muted);
  font-size: 0.88rem;
}

.compact-title {
  color: var(--ink-primary);
  font-weight: 500;
}

.compact-title span {
  color: var(--ink-muted);
  font-weight: 400;
  font-size: 0.88rem;
}

.compact-amount {
  font-variant-numeric: tabular-nums;
  color: var(--ink-secondary);
  font-size: 0.88rem;
  font-weight: 500;
  text-align: right;
}

/* --- 6. BOTTOM LOGOS & FOOTER --- */
.funding-image-container {
  text-align: center;
  margin: 48px 0 24px 0;
  padding-top: 32px;
  border-top: 1px solid var(--rule-light);
}

.funding-image-container img {
  max-width: 100%;
  width: 580px;
  filter: grayscale(100%);
  opacity: 0.75;
  transition: filter 0.3s ease, opacity 0.3s ease;
}

.funding-image-container img:hover {
  filter: grayscale(0%);
  opacity: 1;
}

.pub-footer {
  margin: 32px 0 24px;
  font-size: 0.8rem;
  color: var(--ink-muted);
  text-transform: uppercase;
  letter-spacing: 0.06em;
}
</style>

<!-- SECTION 1: MAJOR RESEARCH GRANTS & FELLOWSHIPS -->
<div class="funding-section">
  <div class="funding-section-header">
    <h2>Research grants & postdoctoral fellowships</h2>
    <span>Competitive funding</span>
  </div>

  <!-- ACTIVE: NANO4TALENT -->
  <div class="funding-entry is-active">
    <div class="funding-header">
      <h3 class="funding-title">MSCA-COFUND Nano4Talent Postdoctoral Fellowship</h3>
      <div class="funding-meta-right">
        <span class="status-tag">Active</span>
        <span class="funding-amount">168,000 €</span>
        <span class="funding-year">2026 – 2028</span>
      </div>
    </div>
    <div class="funding-project">Nanomaterials to modulate viral infections</div>
    <div class="funding-details">
      <span><strong>Agency:</strong> Marie Skłodowska-Curie Actions (MSCA-COFUND) / Xunta de Galicia</span>
      <span><strong>Host:</strong> CINBIO, Universidade de Vigo (Spain)</span>
    </div>
  </div>

  <!-- PASTEUR SEED GRANT -->
  <div class="funding-entry">
    <div class="funding-header">
      <h3 class="funding-title">Pasteur Seed Grant</h3>
      <div class="funding-meta-right">
        <span class="funding-amount">10,000 €</span>
        <span class="funding-year">2026</span>
      </div>
    </div>
    <div class="funding-project">Enteric viral infections and systemic aging in <em>Drosophila melanogaster</em></div>
    <div class="funding-details">
      <span><strong>Agency:</strong> Institut Pasteur</span>
      <span><strong>Host:</strong> Institut Pasteur (France)</span>
    </div>
  </div>

  <!-- PASTEUR-ROUX-CANTARINI -->
  <div class="funding-entry">
    <div class="funding-header">
      <h3 class="funding-title">Pasteur-Roux-Cantarini Postdoctoral Fellowship</h3>
      <div class="funding-meta-right">
        <span class="funding-amount">2-year salary</span>
        <span class="funding-year">2024 – 2026</span>
      </div>
    </div>
    <div class="funding-project">How host bacteriomes drive viral evolution and virulence</div>
    <div class="funding-details">
      <span><strong>Agency:</strong> Institut Pasteur</span>
      <span><strong>Host:</strong> Institut Pasteur (France)</span>
    </div>
  </div>

  <!-- EMBO POSTDOCTORAL FELLOWSHIP -->
  <div class="funding-entry">
    <div class="funding-header">
      <h3 class="funding-title">EMBO Postdoctoral Fellowship</h3>
      <div class="funding-meta-right">
        <span class="funding-amount">143,000 €</span>
        <span class="funding-year">2021 – 2023</span>
      </div>
    </div>
    <div class="funding-project">Microbiome impact on <em>Caenorhabditis elegans</em> viral infection and evolution of Orsay virus</div>
    <div class="funding-details">
      <span><strong>Agency:</strong> European Molecular Biology Organization (Ref. ALTF 311-2021)</span>
      <span><strong>Host:</strong> IBENS, CNRS / ENS (France)</span>
    </div>
  </div>

  <!-- ESA OSIP -->
  <div class="funding-entry">
    <div class="funding-header">
      <h3 class="funding-title">European Space Agency (ESA) Research Grant</h3>
      <div class="funding-meta-right">
        <span class="funding-amount">180,682 €</span>
        <span class="funding-year">2021 – 2022</span>
      </div>
    </div>
    <div class="funding-project">Dynamics of viral infection in simulated microgravity conditions</div>
    <div class="funding-details">
      <span><strong>Agency:</strong> European Space Agency (Open Space Innovation Platform)</span>
      <span><strong>Role:</strong> Co-lead author (with Santiago F. Elena)</span>
    </div>
  </div>

  <!-- FPI PREDOCTORAL -->
  <div class="funding-entry">
    <div class="funding-header">
      <h3 class="funding-title">MINECO-FEDER FPI Predoctoral Fellowship</h3>
      <div class="funding-meta-right">
        <span class="funding-amount">92,750 €</span>
        <span class="funding-year">2017 – 2021</span>
      </div>
    </div>
    <div class="funding-project">Virus adaptation at different biological and environmental levels</div>
    <div class="funding-details">
      <span><strong>Agency:</strong> Spanish Ministry of Science and Innovation (Ref. BES-2016-077078)</span>
      <span><strong>Host:</strong> I2SysBio, CSIC – Universitat de València (Spain)</span>
    </div>
  </div>
</div>

<!-- SECTION 2: MOBILITY, DISTINCTIONS & SHORT-TERM GRANTS -->
<div class="funding-section">
  <div class="funding-section-header">
    <h2>Mobility grants, distinctions & awards</h2>
    <span>Honors & short stays</span>
  </div>

  <div class="compact-awards-list">
    <div class="compact-award">
      <div class="compact-year">2023</div>
      <div class="compact-title">MSCA Seal of Excellence <span>— Marie Skłodowska-Curie Actions Postdoctoral Fellowship</span></div>
      <div class="compact-amount">Distinction</div>
    </div>

    <div class="compact-award">
      <div class="compact-year">2020</div>
      <div class="compact-title">EMBO Short-Term Fellowship <span>— Implementation of C. elegans as a model host at IBENS (Paris)</span></div>
      <div class="compact-amount">4,450 €</div>
    </div>

    <div class="compact-award">
      <div class="compact-year">2020</div>
      <div class="compact-title">FISABIO – Universitat de València Chair <span>— European research stay grant</span></div>
      <div class="compact-amount">4,000 €</div>
    </div>

    <div class="compact-award">
      <div class="compact-year">2020</div>
      <div class="compact-title">GBE Best Student Paper Award (Honorable Mention) <span>— Genome Biology and Evolution (published in 2019)</span></div>
      <div class="compact-amount">500 €</div>
    </div>

    <div class="compact-award">
      <div class="compact-year">2020</div>
      <div class="compact-title">AAAS / Science Program for Excellence in Science <span>— Sponsored membership</span></div>
      <div class="compact-amount">Award</div>
    </div>

    <div class="compact-award">
      <div class="compact-year">2020</div>
      <div class="compact-title">Wellcome Genome Campus Conference Bursary <span>— Travel grant</span></div>
      <div class="compact-amount">170 €</div>
    </div>

    <div class="compact-award">
      <div class="compact-year">2015</div>
      <div class="compact-title">MINECO-FEDER Department Collaboration Grant <span>— University of Vigo (Ref. BOE-A-2015-700)</span></div>
      <div class="compact-amount">2,000 €</div>
    </div>

    <div class="compact-award">
      <div class="compact-year">2014</div>
      <div class="compact-title">European Commission & Xunta de Galicia ERASMUS+ Fellowships <span>— University of Coimbra (Portugal)</span></div>
      <div class="compact-amount">2,800 €</div>
    </div>
  </div>
</div>

<div class="funding-image-container">
  <img src="/images/funding.jpg" alt="Logos of funding agencies: MSCA, EMBO, ESA, Institut Pasteur, and Spanish Ministry of Science" loading="lazy">
</div>

<div class="pub-footer">Updated October 2026</div>
