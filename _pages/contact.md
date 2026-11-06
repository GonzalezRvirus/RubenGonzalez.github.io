---
layout: single
title: "Contact"
permalink: /contact/
author_profile: true
redirect_from:
  - /resume
---

<style>
/* --- 1. EDITORIAL VARIABLES & TYPOGRAPHY --- */
:root {
  --ink-primary: #111827;       /* Casi negro, máxima legibilidad */
  --ink-secondary: #374151;     /* Gris carbón para texto principal */
  --ink-muted: #6b7280;         /* Gris medio para etiquetas y metadatos */
  --accent-editorial: #1e3a8a;  /* Azul marino académico sobrio */
  --rule-heavy: #111827;        /* Línea divisoria principal */
  --rule-light: #e5e7eb;        /* Divisorias finas */
  --bg-subtle: #f9fafb;         /* Fondo sutil para botones */
  
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

/* --- 3. INTRODUCTORY LEAD --- */
.contact-lead {
  font-family: var(--font-serif);
  font-size: 1.18rem;
  line-height: 1.65;
  color: var(--ink-secondary);
  border-bottom: 2px solid var(--rule-heavy);
  padding-bottom: 24px;
  margin-bottom: 32px;
}

.contact-lead p {
  margin: 0;
}

/* --- 4. EDITORIAL DIRECTORY GRID --- */
.contact-directory {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 36px;
  padding-bottom: 32px;
  border-bottom: 1px solid var(--rule-light);
  margin-bottom: 36px;
}

.directory-block {
  border-left: 2px solid var(--rule-light);
  padding-left: 18px;
  transition: border-color 0.2s ease;
}

.directory-block:hover {
  border-left-color: var(--accent-editorial);
}

.directory-label {
  font-size: 0.78rem;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 0.06em;
  color: var(--ink-muted);
  margin-bottom: 10px;
}

/* Email link & Copy button */
.email-row {
  display: flex;
  align-items: center;
  gap: 12px;
  flex-wrap: wrap;
  margin-bottom: 8px;
}

.email-link {
  font-size: 1.08rem;
  font-weight: 600;
  color: var(--ink-primary) !important;
  text-decoration: underline !important;
  text-decoration-color: #9ca3af !important;
  text-underline-offset: 4px;
  text-decoration-thickness: 1px;
  transition: color 0.15s ease, text-decoration-color 0.15s ease;
}

.email-link:hover {
  color: var(--accent-editorial) !important;
  text-decoration-color: var(--accent-editorial) !important;
}

.copy-email-btn {
  background: var(--bg-subtle);
  border: 1px solid var(--rule-light);
  border-radius: 3px;
  padding: 2px 8px;
  font-family: var(--font-sans);
  font-size: 0.72rem;
  font-weight: 500;
  color: var(--ink-muted);
  cursor: pointer;
  text-transform: uppercase;
  letter-spacing: 0.05em;
  transition: all 0.15s ease;
}

.copy-email-btn:hover {
  border-color: var(--ink-muted);
  color: var(--ink-primary);
}

.directory-note {
  font-size: 0.88rem;
  color: var(--ink-muted);
  line-height: 1.5;
  margin: 0;
}

/* Postal address */
.address-details {
  font-size: 0.95rem;
  line-height: 1.6;
  color: var(--ink-secondary);
}

.address-details strong {
  color: var(--ink-primary);
  font-weight: 600;
}

.address-details a {
  color: var(--ink-primary);
  text-decoration: underline;
  text-decoration-color: #9ca3af;
  text-underline-offset: 3px;
  transition: color 0.15s ease, text-decoration-color 0.15s ease;
}

.address-details a:hover {
  color: var(--accent-editorial);
  text-decoration-color: var(--accent-editorial);
}

/* --- 5. INSTITUTIONAL PHOTOGRAPH --- */
.campus-figure {
  margin: 0 0 24px 0;
}

.campus-figure img {
  width: 100%;
  max-height: 340px;
  object-fit: cover;
  border-radius: 2px;
  border: 1px solid var(--rule-light);
  filter: grayscale(15%);
  transition: filter 0.3s ease;
}

.campus-figure img:hover {
  filter: grayscale(0%);
}

.campus-caption {
  margin-top: 8px;
  font-size: 0.82rem;
  color: var(--ink-muted);
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 8px;
}

/* --- 6. RESPONSIVE --- */
@media (max-width: 768px) {
  .contact-directory {
    grid-template-columns: 1fr;
    gap: 24px;
  }
}
</style>

<script>
function copyEmail(btn) {
  navigator.clipboard.writeText('ru.gonzalez@uvigo.gal');
  const original = btn.textContent;
  btn.textContent = 'Copied';
  setTimeout(() => { btn.textContent = original; }, 1800);
}
</script>

<div class="contact-lead">
  <p>
    I am always open to discussing new research questions, collaborative projects, and prospective opportunities across viral evolution, host–pathogen interactions, and the systems biology of infection.
  </p>
</div>

<div class="contact-directory">
  <!-- DIRECT CORRESPONDENCE -->
  <div class="directory-block">
    <div class="directory-label">Electronic mail</div>
    <div class="email-row">
      <a href="mailto:ru.gonzalez@uvigo.gal" class="email-link">ru.gonzalez@uvigo.gal</a>
      <button type="button" class="copy-email-btn" onclick="copyEmail(this)">Copy</button>
    </div>
    <p class="directory-note">
      For scientific inquiries, peer-review requests, or prospective student and postdoctoral opportunities.
    </p>
  </div>

  <!-- INSTITUTIONAL ADDRESS -->
  <div class="directory-block">
    <div class="directory-label">Affiliation &amp; postal address</div>
    <div class="address-details">
      <strong><a href="https://cinbio.es/en/" target="_blank" rel="noopener">Center for Research in Nanomaterials and Biomedicine (CINBIO)</a></strong><br>
      Universidade de Vigo<br>
      Campus Universitario Lagoas-Marcosende<br>
      36310 Vigo, Spain
    </div>
  </div>
</div>

<figure class="campus-figure">
  <img src="/images/CINBIO.jpeg" alt="Center for Research in Nanomaterials and Biomedicine (CINBIO) at the University of Vigo" loading="lazy">
  <figcaption class="campus-caption">
    <span>Center for Research in Nanomaterials and Biomedicine (CINBIO), Universidade de Vigo</span>
    <span>42°09′58″N 8°41′06″W</span>
  </figcaption>
</figure>
