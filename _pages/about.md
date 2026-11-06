---
permalink: /
title: "Research vision"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
/* --- 1. EDITORIAL VARIABLES & TYPOGRAPHY --- */
:root {
  --ink-primary: #111827;       /* Casi negro, máxima legibilidad */
  --ink-secondary: #374151;     /* Gris carbón para texto principal */
  --ink-muted: #6b7280;         /* Gris medio para metadatos y pies */
  --accent-editorial: #1e3a8a;  /* Azul marino académico sobrio */
  --rule-heavy: #111827;        /* Línea divisoria principal */
  --rule-light: #e5e7eb;        /* Divisorias finas */
  --bg-subtle: #f9fafb;         /* Fondo sutil */
  
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

/* --- 3. VISION HERO (EDITORIAL LEAD) --- */
.vision-hero {
  border-bottom: 2px solid var(--rule-heavy);
  padding-bottom: 24px;
  margin-bottom: 32px;
}

.vision-statement {
  font-family: var(--font-serif);
  font-size: 1.35rem;
  line-height: 1.6;
  color: var(--ink-primary);
  font-weight: 400;
  letter-spacing: -0.01em;
}

.vision-statement strong {
  font-weight: 600;
  color: var(--ink-primary);
  text-decoration: underline;
  text-decoration-color: #9ca3af;
  text-underline-offset: 4px;
  text-decoration-thickness: 1px;
}

/* --- 4. BIO & NARRATIVE (ACADEMIC TIMELINE STYLE) --- */
.bio-section {
  font-size: 1.02rem;
  line-height: 1.75;
  color: var(--ink-secondary);
  margin-bottom: 48px;
}

.bio-paragraph {
  padding: 14px 0 14px 18px;
  margin-left: 2px;
  border-left: 2px solid var(--rule-light);
  margin-bottom: 12px;
  transition: border-color 0.2s ease, background-color 0.2s ease;
}

.bio-paragraph:hover {
  border-left-color: var(--accent-editorial);
  background-color: var(--bg-subtle);
}

.bio-paragraph p {
  margin: 0;
}

.bio-section a {
  color: var(--ink-primary);
  text-decoration: underline;
  text-decoration-color: #9ca3af;
  text-underline-offset: 3px;
  transition: color 0.15s ease, text-decoration-color 0.15s ease;
}

.bio-section a:hover {
  color: var(--accent-editorial);
  text-decoration-color: var(--accent-editorial);
}

/* --- 5. EDITORIAL GALLERY GRID --- */
.gallery-section-title {
  font-size: 0.78rem;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 0.06em;
  color: var(--ink-muted);
  margin-bottom: 16px;
  border-bottom: 1px solid var(--rule-light);
  padding-bottom: 8px;
}

.gallery-container {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 24px;
  margin-top: 24px;
}

.gallery-item {
  background-color: #ffffff;
  border: 1px solid var(--rule-light);
  border-radius: 2px;
  overflow: hidden;
  transition: border-color 0.2s ease;
}

.gallery-item:hover {
  border-color: var(--accent-editorial);
}

.gallery-item img {
  width: 100%;
  height: 200px;
  object-fit: cover;
  display: block;
  filter: grayscale(15%);
  transition: filter 0.3s ease;
}

.gallery-item:hover img {
  filter: grayscale(0%);
}

.gallery-caption {
  padding: 12px 14px;
  font-size: 0.85rem;
  color: var(--ink-muted);
  font-weight: 500;
  border-top: 1px solid var(--rule-light);
  background-color: #fafafa;
}

/* --- RESPONSIVE --- */
@media (max-width: 768px) {
  .gallery-container {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="vision-hero">
  <div class="vision-statement">
    My research investigates the fundamental principles governing <strong>viral infections and virus evolution</strong> across model systems. By integrating evolutionary biology, molecular virology, and systems approaches, my work uncovers how viruses evolve, impact host biology, and interact with environmental factors to shape infection outcomes.
  </div>
</div>

<div class="bio-section">
  <div class="bio-paragraph">
    <p>
      I completed my Ph.D. in Biotechnology under the supervision of <a href="https://sfelenalab.csic.es/sfelena/" target="_blank" rel="noopener">Santiago F. Elena</a> at the Institute for Integrative Systems Biology (I2SysBio, CSIC–UV), investigating the evolutionary dynamics and environmental drivers of plant viruses.
    </p>
  </div>

  <div class="bio-paragraph">
    <p>
      Subsequently, as an <a href="https://www.embo.org/" target="_blank" rel="noopener">EMBO postdoctoral fellow</a> in the <a href="https://www.ibens.ens.fr/" target="_blank" rel="noopener">Marie-Anne Félix laboratory</a> at the École Normale Supérieure (IBENS, Paris), my research identified host genetic factors and natural bacterial environments that modulate susceptibility to viral infection in the nematode <em>Caenorhabditis elegans</em>.
    </p>
  </div>

  <div class="bio-paragraph">
    <p>
      As a Pasteur-Roux-Cantarini postdoctoral researcher at the <a href="http://salehlab.eu" target="_blank" rel="noopener">Carla Saleh laboratory</a> (Institut Pasteur, Paris), I examined how enteric viral infections accelerate systemic aging in <em>Drosophila melanogaster</em>, explored microbiome-mediated viral pathogenesis, and studied the experimental evolution of diverse RNA viruses.
    </p>
  </div>

  <div class="bio-paragraph">
    <p>
      Currently, I serve am a <a href="https://cinbio.es/en/nano4talent/about/" target="_blank" rel="noopener">Nano4Talent Research Fellow</a> (MSCA-COFUND) at the Center for Research in Nanomaterials and Biomedicine (<a href="https://cinbio.es/en" target="_blank" rel="noopener">CINBIO</a>) of the University of Vigo, expanding my research line on host-pathogen interactions and antiviral resilience through advanced systems biology and nanotechnological approaches.
    </p>
  </div>
</div>






<div class="clean-gallery">
  <div class="clean-card">
    <div class="img-wrapper">
      <img src="/images/VIA_2024.jpg" alt="Viruses and RNAi Unit at Institut Pasteur" loading="lazy" />
    </div>
    <div class="clean-caption">Viruses and RNAi Unit (Carla Saleh Lab, Institut Pasteur, 2024)</div>
  </div>

  <div class="clean-card">
    <div class="img-wrapper">
      <img src="/images/New_20211108_Santi.jpeg" alt="C. elegans experimental facilities setup" loading="lazy" />
    </div>
    <div class="clean-caption">Establishing C. elegans research facilities (2021)</div>
  </div>

  <div class="clean-card">
    <div class="img-wrapper">
      <img src="/images/Felix_lab_2023.JPEG" alt="Evolution of Caenorhabditis at IBENS" loading="lazy" />
    </div>
    <div class="clean-caption">Nematode host evolution (Marie-Anne Félix Lab, IBENS, 2023)</div>
  </div>

  <div class="clean-card">
    <div class="img-wrapper">
      <img src="/images/EvoSysVir_2021.jpg" alt="Evolutionary Systems Virology lab at I2SysBio" loading="lazy" />
    </div>
    <div class="clean-caption">Evolutionary Systems Virology (Santiago F. Elena Lab, I2SysBio, 2021)</div>
  </div>
</div>

<style>
.gallery-section-title {
  font-size: 0.78rem;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 0.06em;
  color: #6b7280;
  margin-top: 48px;
  margin-bottom: 16px;
  border-bottom: 1px solid #e5e7eb;
  padding-bottom: 8px;
}

.clean-gallery {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 24px;
  margin-top: 16px;
}

.clean-card {
  background-color: #ffffff;
  border: 1px solid #e5e7eb;
  border-radius: 4px;
  overflow: hidden;
  display: flex;
  flex-direction: column;
}

.img-wrapper {
  width: 100%;
  background-color: #000; /* Fondo negro por si la imagen carga o tiene transparencia */
  overflow: hidden;
}

.clean-card img {
  width: 100% !important;
  height: auto !important; /* Mantiene la proporción real y evita el estiramiento borroso */
  max-height: 280px;
  object-fit: contain !important; /* Muestra la imagen completa sin recortar ni pixelar */
  display: block !important;
  margin: 0 auto !important;
  padding: 0 !important;
  border: none !important;
  filter: grayscale(15%);
  transition: filter 0.3s ease;
}

.clean-card img:hover {
  filter: grayscale(0%);
}

.clean-caption {
  padding: 12px 14px;
  font-size: 0.85rem;
  color: #4b5563;
  font-weight: 500;
  border-top: 1px solid #e5e7eb;
  background-color: #fafafa;
  line-height: 1.4;
}

@media (max-width: 768px) {
  .clean-gallery {
    grid-template-columns: 1fr;
  }
}
</style>
