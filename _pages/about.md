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
/* --- GLOBAL VARIABLES & MODERN RESET --- */
:root {
  --primary-color: #0f172a; /* Deep Slate */
  --accent-color: #0284c7; /* Authoritative Blue */
  --text-color: #334155; /* Readable Slate */
  --bg-light: #f8fafc; /* Subtle light background */
}

/* --- VISION HERO SECTION --- */
.vision-hero {
  padding: 40px 35px;
  background: linear-gradient(to right bottom, #ffffff, var(--bg-light));
  border-radius: 8px;
  border-left: 4px solid var(--accent-color);
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.03);
  margin-bottom: 50px;
}

.vision-subtitle {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  text-transform: uppercase;
  letter-spacing: 0.12em;
  font-size: 0.85em;
  color: var(--accent-color);
  font-weight: 700;
  margin-bottom: 15px;
  display: block;
}

.vision-statement {
  font-family: "Georgia", "Times New Roman", serif;
  font-size: 1.6em; 
  line-height: 1.5;
  color: var(--primary-color);
  font-weight: 400;
}

.vision-statement strong {
  font-weight: 600;
  color: var(--accent-color); 
}

/* --- BIO & NARRATIVE --- */
.bio-section {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  font-size: 1.15em; 
  line-height: 1.8;
  color: var(--text-color);
  margin-bottom: 50px;
}

.bio-section p {
  margin-bottom: 1.5em;
}

.bio-section a {
  color: var(--accent-color);
  text-decoration: none;
  border-bottom: 1px solid rgba(2, 132, 199, 0.3);
  transition: border-bottom-color 0.2s ease-in-out, color 0.2s ease-in-out;
}

.bio-section a:hover {
  border-bottom-color: var(--accent-color);
  color: #0369a1; /* Darker blue on hover */
}

/* --- MINIMALIST GALLERY --- */
.gallery-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 30px;
  margin-top: 60px;
}

.gallery-item {
  position: relative;
  overflow: hidden;
  border-radius: 6px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.05);
  background-color: #fff;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.gallery-item:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
}

.gallery-item img {
  width: 100%;
  height: 220px;
  object-fit: cover;
  display: block;
  filter: grayscale(15%);
  transition: filter 0.4s ease;
}

.gallery-item:hover img {
  filter: grayscale(0%);
}

.gallery-caption {
  padding: 15px;
  font-size: 0.95em;
  color: var(--text-color);
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  font-weight: 500;
  text-align: center;
  border-top: 1px solid #eaeaea;
}
</style>

<div class="vision-hero">
  <div class="vision-statement">
    My research investigates the fundamental principles governing <strong>viral infections and virus evolution</strong> across model systems. 
    <br><br>
    By integrating evolutionary biology, molecular virology, and systems approaches, my work uncovers how viruses evolve, impact host biology, and interact with environmental factors to shape infection outcomes.
  </div>
</div>

<div class="bio-section">
  <p>
    I completed my PhD under the supervision of <a href="https://sfelenalab.csic.es/sfelena/">Santiago F. Elena</a> at the Institute for Integrative Systems Biology (I2SysBio, Spain), where I investigated the factors driving the evolution of plant viruses.
  </p>
  <p>
    I subsequently obtained an <a href="https://www.embo.org/about-embo/mission/">EMBO postdoctoral fellowship</a> to join the <a href="https://www.ibens.ens.fr/?rubrique29&lang=en">Marie-Anne Félix laboratory</a> at the Institute of Biology of the École Normale Supérieure (IBENS, France). My research identified host genetic factors and environmental bacterial interactions that modulate the susceptibility of the nematode <em>Caenorhabditis elegans</em> to Orsay virus infection.
  </p>
  <p>
    As a Pasteur-Roux-Cantarini postdoctoral fellow at the <a href="http://salehlab.eu">Carla Saleh laboratory</a> (Institut Pasteur, France), I used <em>Drosophila melanogaster</em> to investigate how viral infections alter host aging trajectories, the impact of the microbiome on viral pathogenesis, and the experimental evolution of RNA viruses.
  </p>
  <p>
    Currently, I am a <a href="https://cinbio.es/en/nano4talent/about/">Nano4Talent </a>research fellow (MSCA-COFUND) at the Center for Research in Nanomaterials and Biomedicine (<a href="httpS://cinbio.es/en">CINBIO</a>) of the University of Vigo, Spain. My ongoing research expands upon the mechanistic basis of host-virus interactions by integrating the use of nanomaterials to modulate and dissect viral infection dynamics.
  </p>
</div>

<div class="gallery-container">
  <div class="gallery-item">
    <img src="/images/VIA_2024.jpg" alt="Viruses and RNAi" loading="lazy" />
    <div class="gallery-caption">Viruses and RNAi (Carla Saleh Lab, 2024)</div>
  </div>
  <div class="gallery-item">
    <img src="/images/New_20211108_Santi.jpeg" alt="C. elegans facilities" loading="lazy" />
    <div class="gallery-caption">Setting up C. elegans facilities (2021)</div>
  </div>
  <div class="gallery-item">
    <img src="/images/Felix_lab_2023.JPEG" alt="Evolution of Caenorhabditis" loading="lazy" />
    <div class="gallery-caption">Evolution of Caenorhabditis (Marie-Anne Félix Lab, 2023)</div>
  </div>
  <div class="gallery-item">
    <img src="/images/EvoSysVir_2021.jpg" alt="Evolutionary Systems Virology" loading="lazy" />
    <div class="gallery-caption">Evolutionary Systems Virology (Santiago F. Elena Lab, 2021)</div>
  </div>
</div>
