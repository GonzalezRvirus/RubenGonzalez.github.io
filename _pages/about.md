---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
/* Gallery styles */
.gallery-container {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 20px;
  padding: 20px 0;
  max-width: 1200px;
  margin: 2em auto;
}

.gallery-item {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  background-color: #fff;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  overflow: hidden;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.gallery-item:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 20px rgba(0,0,0,0.1);
}

.gallery-item img {
  width: 100%;
  height: auto;
  object-fit: cover;
  transition: transform 0.2s ease-out;
}

.gallery-item:hover img {
  transform: scale(1.05);
}

.gallery-item p {
  margin: 10px 0;
  color: #666;
  font-size: 14px;
  padding: 0 10px 10px;
}

/* Button styling */
.btn--primary {
  background-color: #1a73e8;
  color: white;
  padding: 12px 24px;
  text-decoration: none;
  border-radius: 4px;
  display: inline-block;
  font-weight: 500;
  transition: background-color 0.2s;
}

.btn--primary:hover {
  background-color: #1557b0;
  color: white;
}

.btn--large {
  font-size: 1.1em;
  padding: 14px 28px;
}

/* CV section */
.cv-section {
  background: #f8f9fa;
  padding: 2em;
  border-radius: 8px;
  margin: 3em 0;
  text-align: center;
}

.cv-section h2 {
  color: #1a73e8;
  margin-bottom: 0.5em;
}
</style>

I am a scientist focused on the study of viral interactions. My research aims to elucidate (i) the evolutionary dynamics of viruses, (ii) the interplay among the host, virus, and microbial communities, and (iii) the consequences of infections for the host.

I owe my interest in viruses to Professor [Santiago F. Elena](https://sfelenalab.csic.es/sfelena/). I completed my PhD under his mentorship at I2SysBio (Valencia, Spain), where I studied factors influencing the evolution of viruses, using plant-pathogen systems as model organisms.

After my PhD, I obtained an [EMBO](https://www.embo.org/about-embo/mission/) Postdoctoral Fellowship and joined the [Marie-Anne Félix Laboratory](https://www.ibens.ens.fr/?rubrique29&lang=en) (IBENS, France). There I investigated host factors and bacterial environments that modulate the nematode *Caenorhabditis elegans* susceptibility to Orsay virus infection.

Currently, I am Pasteur-Roux-Cantarini Postdoctoral Fellow at [Carla Saleh Laboratory](http://salehlab.eu) (Institut Pasteur, France). In here I am a happy researcher studying viral infections in the fly *Drosophila melanogaster*. My research here focuses in the aging induced by viruses, the impact of the microbiome on infections, and the evolution of RNA viruses.

<div class="gallery-container">
  <div class="gallery-item">
    <img src="/images/VIA_2024.jpg" alt="Viruses and RNAi" />
    <p>Viruses and RNAi<br>(Carla Saleh Lab, 2024)</p>
  </div>
  <div class="gallery-item">
    <img src="/images/New_20211108_Santi.jpeg" alt="C. elegans facilities" />
    <p>Setting up C. elegans facilities<br>(2021)</p>
  </div>
  <div class="gallery-item">
    <img src="/images/Felix_lab_2023.JPEG" alt="Evolution of Caenorhabditis" />
    <p>Evolution of Caenorhabditis<br>(Marie-Anne Félix Lab, 2023)</p>
  </div>
  <div class="gallery-item">
    <img src="/images/EvoSysVir_2021.jpg" alt="Evolutionary Systems Virology" />
    <p>Evolutionary Systems Virology<br>(Santiago F. Elena Lab, 2021)</p>
  </div>
</div>

<div class="cv-section">
  <h2>Curriculum Vitae</h2>
  <p>For a complete overview of my academic background, publications, and achievements:</p>
  <a href="https://github.com/GonzalezRvirus/RubenGonzalez.github.io/raw/master/_pages/CV.pdf" target="_blank" class="btn--primary">Download CV (PDF)</a>
</div>

<div style="text-align: center; margin: 3em 0;">
  <h2 style="color: #202124; margin-bottom: 1em;">Connect & Collaborate</h2>
  <p style="font-size: 1.1em; color: #5f6368; margin-bottom: 2em;">
    I'm always interested in discussing new ideas and potential collaborations.<br>
    Feel free to reach out if you share interests in viral evolution, host-pathogen interactions, or model system biology.
  </p>
  <a href="mailto:ruben.gonzalez@pasteur.fr" class="btn--primary btn--large">Get in Touch</a>
</div>
