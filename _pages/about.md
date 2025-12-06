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
/* Responsive Grid for Gallery */
.gallery-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); /* Smart responsiveness */
  gap: 25px;
  padding: 20px 0;
  max-width: 1200px;
  margin: 2em auto;
}

.gallery-item {
  display: flex;
  flex-direction: column;
  background-color: #fff;
  border-radius: 12px;
  box-shadow: 0 4px 6px rgba(0,0,0,0.05); /* Softer shadow */
  overflow: hidden;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  border: 1px solid #eee;
}

.gallery-item:hover {
  transform: translateY(-5px);
  box-shadow: 0 12px 24px rgba(0,0,0,0.12);
}

.gallery-item img {
  width: 100%;
  height: 250px; /* Fixed height for uniformity */
  object-fit: cover;
  transition: transform 0.5s ease;
}

.gallery-item:hover img {
  transform: scale(1.03);
}

.gallery-item p {
  margin: 0;
  padding: 15px;
  color: #555;
  font-size: 0.95em;
  font-weight: 500;
  background: #fff;
  border-top: 1px solid #f0f0f0;
}

/* Hero Section Styling */
.hero-intro {
  background-color: #f8f9fa;
  border-left: 5px solid #1a73e8;
  padding: 20px 25px;
  border-radius: 0 8px 8px 0;
  margin-bottom: 30px;
  font-size: 1.05em;
  line-height: 1.6;
}

/* Button Styling */
.btn-container {
  margin-top: 20px;
  text-align: center;
}
.btn-primary {
  background-color: #1a73e8;
  color: white !important;
  padding: 10px 20px;
  text-decoration: none;
  border-radius: 25px;
  font-weight: 600;
  font-size: 0.9em;
  transition: all 0.2s;
  display: inline-block;
  box-shadow: 0 2px 5px rgba(26, 115, 232, 0.3);
}
.btn-primary:hover {
  background-color: #1557b0;
  transform: translateY(-2px);
  box-shadow: 0 4px 8px rgba(26, 115, 232, 0.4);
}
</style>

<div class="hero-intro">
  <strong>I am a scientist focused on the study of viral interactions.</strong> 
  <br><br>
  My research aims to elucidate:
  1. The evolutionary dynamics of viruses.
  2. The interplay among the host, virus, and microbial communities.
  3. The consequences of infections for the host.
  
  <div class="btn-container">
    <a href="/publications/" class="btn-primary">View Publications</a>
    </div>
</div>

I owe my interest in viruses to [Santiago F. Elena](https://sfelenalab.csic.es/sfelena/). I completed my PhD under his mentorship at I2SysBio (Valencia, Spain), where I studied factors influencing the evolution of viruses, using plant-pathogen systems as model organisms.

After my PhD, I obtained an [EMBO](https://www.embo.org/about-embo/mission/) Postdoctoral Fellowship and joined the [Marie-Anne Félix Laboratory](https://www.ibens.ens.fr/?rubrique29&lang=en) (IBENS, France). There I investigated host factors and bacterial environments that modulate the nematode *Caenorhabditis elegans* susceptibility to Orsay virus infection.



Currently, I am Pasteur-Roux-Cantarini Postdoctoral Fellow at the [Carla Saleh Laboratory](http://salehlab.eu) (Institut Pasteur, France). Here, I am studying viral infections in the fly *Drosophila melanogaster*, focusing on aging induced by viruses, microbiome impacts, and RNA virus evolution.



[Image of Drosophila melanogaster]


<div class="gallery-container">
  <div class="gallery-item">
    <img src="/images/VIA_2024.jpg" alt="Viruses and RNAi" loading="lazy" />
    <p>Viruses and RNAi <br><span style="color:#999; font-size:0.9em;">(Carla Saleh Lab, 2024)</span></p>
  </div>
  <div class="gallery-item">
    <img src="/images/New_20211108_Santi.jpeg" alt="C. elegans facilities" loading="lazy" />
    <p>Setting up C. elegans facilities <br><span style="color:#999; font-size:0.9em;">(2021)</span></p>
  </div>
  <div class="gallery-item">
    <img src="/images/Felix_lab_2023.JPEG" alt="Evolution of Caenorhabditis" loading="lazy" />
    <p>Evolution of Caenorhabditis <br><span style="color:#999; font-size:0.9em;">(Marie-Anne Félix Lab, 2023)</span></p>
  </div>
  <div class="gallery-item">
    <img src="/images/EvoSysVir_2021.jpg" alt="Evolutionary Systems Virology" loading="lazy" />
    <p>Evolutionary Systems Virology <br><span style="color:#999; font-size:0.9em;">(Santiago F. Elena Lab, 2021)</span></p>
  </div>
</div>
