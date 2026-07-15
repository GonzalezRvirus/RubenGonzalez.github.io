---
layout: single
title: "Research funding & fellowships"
permalink: /funding/
author_profile: true
---

<style>
/* --- GLOBAL VARIABLES & TYPOGRAPHY --- */
:root {
  --primary-color: #0f172a; 
  --accent-color: #0284c7; 
  --text-color: #334155; 
  --bg-light: #f8fafc; 
  --border-color: #e2e8f0;
}

/* --- FUNDING CARDS LAYOUT --- */
.funding-list {
  display: flex;
  flex-direction: column;
  gap: 25px;
  margin-top: 30px;
  margin-bottom: 50px;
}

.funding-card {
  background: #ffffff;
  border: 1px solid var(--border-color);
  border-radius: 8px;
  padding: 25px 30px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.02);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  position: relative;
  overflow: hidden;
}

.funding-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.06);
  border-color: #cbd5e1;
}

/* Status border accents */
.status-active-border {
  border-left: 6px solid #059669; /* Emerald green for active */
}

.status-completed-border {
  border-left: 6px solid #94a3b8; /* Slate gray for completed */
}

/* --- CARD INTERNAL ELEMENTS --- */
.funding-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  margin-bottom: 12px;
  flex-wrap: wrap;
  gap: 10px;
}

.funding-title {
  font-size: 1.3em;
  font-weight: 700;
  color: var(--primary-color);
  margin: 0;
  line-height: 1.3;
}

.funding-badges {
  display: flex;
  gap: 10px;
  align-items: center;
}

.badge-year {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", monospace;
  font-size: 1.05em;
  font-weight: 600;
  color: var(--accent-color);
  background: var(--bg-light);
  padding: 4px 10px;
  border-radius: 4px;
  border: 1px solid var(--border-color);
}

.badge-status {
  font-size: 0.85em;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.05em;
  padding: 4px 10px;
  border-radius: 20px;
}

.badge-status.active {
  background-color: #d1fae5;
  color: #065f46;
  border: 1px solid #34d399;
}

.badge-status.completed {
  background-color: #f1f5f9;
  color: #64748b;
  border: 1px solid #cbd5e1;
}

.funding-project {
  font-size: 1.1em;
  color: var(--text-color);
  font-style: italic;
  margin-bottom: 15px;
  line-height: 1.5;
}

.funding-details {
  font-size: 0.95em;
  color: #475569;
  line-height: 1.6;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
  border-top: 1px solid var(--border-color);
  padding-top: 12px;
}

.funding-details strong {
  color: var(--primary-color);
  font-weight: 600;
}

/* --- BOTTOM IMAGE --- */
.funding-image-container {
  text-align: center;
  margin: 4em 0 2em 0;
  padding-top: 3em;
  border-top: 1px solid var(--border-color);
}

.funding-image-container img {
  max-width: 100%;
  width: 600px;
  border-radius: 8px;
  box-shadow: 0 4px 15px rgba(0,0,0,0.05);
  filter: grayscale(10%);
  transition: filter 0.3s ease;
}

.funding-image-container img:hover {
  filter: grayscale(0%);
}
</style>

<div class="funding-list">

  <!-- ACTIVE FUNDING -->
  <div class="funding-card status-active-border">
    <div class="funding-header">
      <h3 class="funding-title">Nano4Talent Postdoctoral Fellowship</h3>
      <div class="funding-badges">
        <span class="badge-status active">Active</span>
        <span class="badge-year">2026 - 2028</span>
      </div>
    </div>
    <div class="funding-project">Nanomaterials to modulate viral infections</div>
    <div class="funding-details">
      <strong>Funding Agency:</strong> Marie Skłodowska-Curie Actions (MSCA-COFUND) / Xunta de Galicia<br>
      <strong>Host Institution:</strong> CINBIO, Universidade de Vigo (Spain)
    </div>
  </div>

  <!-- COMPLETED FUNDING -->
  <div class="funding-card status-completed-border">
    <div class="funding-header">
      <h3 class="funding-title">Pasteur-Roux-Cantarini Postdoctoral Fellowship</h3>
      <div class="funding-badges">
        <span class="badge-status completed">Completed</span>
        <span class="badge-year">2025 - 2026</span>
      </div>
    </div>
    <div class="funding-project">How host bacteriomes drive viral evolution and virulence</div>
    <div class="funding-details">
      <strong>Funding Agency:</strong> Institut Pasteur<br>
      <strong>Host Institution:</strong> Institut Pasteur (France)
    </div>
  </div>

  <div class="funding-card status-completed-border">
    <div class="funding-header">
      <h3 class="funding-title">EMBO Postdoctoral Fellowship</h3>
      <div class="funding-badges">
        <span class="badge-status completed">Completed</span>
        <span class="badge-year">2021 - 2023</span>
      </div>
    </div>
    <div class="funding-project">Microbiome impact on Caenorhabditis elegans viral infection and evolution of Orsay virus</div>
    <div class="funding-details">
      <strong>Funding Agency:</strong> European Molecular Biology Organization (EMBO)<br>
      <strong>Host Institution:</strong> IBENS (France)
    </div>
  </div>

  <div class="funding-card status-completed-border">
    <div class="funding-header">
      <h3 class="funding-title">Open Space Innovation Project</h3>
      <div class="funding-badges">
        <span class="badge-status completed">Completed</span>
        <span class="badge-year">2021 - 2022</span>
      </div>
    </div>
    <div class="funding-project">Dynamics of viral infection in simulated microgravity conditions</div>
    <div class="funding-details">
      <strong>Funding Agency:</strong> European Space Agency (ESA)<br>
      <strong>Details:</strong> Collaborative research project
    </div>
  </div>

  <div class="funding-card status-completed-border">
    <div class="funding-header">
      <h3 class="funding-title">EMBO Short-Term Fellowship</h3>
      <div class="funding-badges">
        <span class="badge-status completed">Completed</span>
        <span class="badge-year">2020</span>
      </div>
    </div>
    <div class="funding-project">Implementation of Caenorhabditis elegans as a model host system in virology research</div>
    <div class="funding-details">
      <strong>Funding Agency:</strong> European Molecular Biology Organization (EMBO)
    </div>
  </div>

  <div class="funding-card status-completed-border">
    <div class="funding-header">
      <h3 class="funding-title">FISABIO-Valencia University Chair</h3>
      <div class="funding-badges">
        <span class="badge-status completed">Completed</span>
        <span class="badge-year">2020</span>
      </div>
    </div>
    <div class="funding-project">Implementation of C. elegans as a model host system in virology research</div>
    <div class="funding-details">
      <strong>Funding Agency:</strong> FISABIO / Universitat de València<br>
      <strong>Details:</strong> Financing for European research stays
    </div>
  </div>

  <div class="funding-card status-completed-border">
    <div class="funding-header">
      <h3 class="funding-title">FPI Spanish Research Fellowship</h3>
      <div class="funding-badges">
        <span class="badge-status completed">Completed</span>
        <span class="badge-year">2017 - 2021</span>
      </div>
    </div>
    <div class="funding-project">Virus adaptation at different levels</div>
    <div class="funding-details">
      <strong>Funding Agency:</strong> Spanish Ministry of Science and Innovation<br>
      <strong>Details:</strong> Pre-doctoral (PhD) funding
    </div>
  </div>

</div>

<div class="funding-image-container">
  <img src="/images/funding.jpg" alt="Logos of funding agencies: MSCA, EMBO, ESA, Institut Pasteur, and Spanish Ministry of Science" loading="lazy">
</div>
