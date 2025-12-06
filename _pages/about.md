---
permalink: /
title: "Research Vision"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
/* --- VISION HERO SECTION --- */
.vision-hero {
  padding: 20px 0 50px 0;
  border-bottom: 1px solid #eaeaea;
  margin-bottom: 40px;
}

.vision-statement {
  font-family: "Georgia", "Times New Roman", serif;
  font-size: 1.6em; /* Increased size */
  line-height: 1.5;
  color: #202124;
  font-weight: 300;
}

.vision-statement strong {
  font-weight: 600;
  color: #1a73e8;
}

/* --- BIO & NARRATIVE --- */
.bio-section {
  font-size: 1.15em; /* Increased for readability */
  line-height: 1.8;
  color: #333;
  margin-bottom: 50px;
}

.bio-section a {
  color: #1a73e8;
  text-decoration: none;
  border-bottom: 1px solid transparent;
  transition: border-color 0.2s;
}

.bio-section a:hover {
  border-bottom: 1px solid #1a73e8;
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
  border-radius: 4px;
}

.gallery-item img {
  width: 100%;
  height: 220px;
  object-fit: cover;
  display: block;
  filter: grayscale(10%);
  transition: filter 0.3s, transform 0.5s;
}

.gallery-item:hover img {
  filter: grayscale(0%);
  transform: scale(1.02);
}

.gallery-caption {
  margin-top: 12px;
  font-size: 1.0em; /* Fixed: Was too small */
  color: #555;
  font-family: sans-serif;
  letter-spacing: 0.02em;
}
</style>

<div class="vision-hero">
  <div class="vision-statement">
    My research investigates the fundamental principles governing <strong>host-pathogen interactions</strong> across model systems. 
    <br><br>
    By integrating evolutionary biology, molecular virology, and systems approaches, we uncover how viruses evolve, impact host biology, and interact with environmental factors to shape infection outcomes.
  </div>
</div>

<div class="bio-section">
  <p>
    I owe my interest in viruses to <a href="https://sfelenalab.csic.es/sfelena/">Santiago F. Elena</a>. I completed my PhD under his mentorship at I2SysBio (Valencia, Spain), where I studied factors influencing the evolution of viruses, using plant-pathogen systems as model organisms.
  </p>
  <p>
    After my PhD, I obtained an <a href="https://www.embo.org/about-embo/mission/">EMBO Postdoctoral Fellowship</a> and joined the <a href="https://www.ibens.ens.fr/?rubrique29&lang=en">Marie-Anne Félix Laboratory</a> (IBENS, France). There I investigated host factors and bacterial environments that modulate the nematode <em>Caenorhabditis elegans</em> susceptibility to Orsay virus infection.
  </p>
  
  <p>
    Currently, I am a Pasteur-Roux-Cantarini Postdoctoral Fellow at the <a href="http://salehlab.eu">Carla Saleh Laboratory</a> (Institut Pasteur, France). Here I am a happy researcher studying viral infections in the fly <em>Drosophila melanogaster</em>. My research here focuses in the aging induced by viruses, the impact of the microbiome on infections, and the evolution of RNA viruses.
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
