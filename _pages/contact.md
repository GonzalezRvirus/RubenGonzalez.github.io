---
layout: single
title: "Contact"
permalink: /contact/
author_profile: true
redirect_from:
  - /resume
---

<style>
/* --- GLOBAL VARIABLES --- */
:root {
  --primary-color: #0f172a; 
  --accent-color: #0284c7; 
  --text-color: #334155; 
  --bg-light: #f8fafc; 
}

/* Connect section */
.connect-header {
  text-align: center;
  margin-bottom: 2em;
  padding: 2.5em 1.5em;
  background: linear-gradient(to right bottom, #ffffff, var(--bg-light));
  border-radius: 8px;
  border-top: 4px solid var(--accent-color);
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.03);
}

.connect-header h1 {
  color: var(--primary-color);
  margin-bottom: 0.4em;
  font-size: 1.8em;
  font-weight: 600;
}

.connect-header p {
  font-size: 1.1em;
  color: var(--text-color);
  line-height: 1.6;
  margin: 0;
}

/* Contact info box */
.contact-info {
  background: #ffffff;
  border: 1px solid #e8eaed;
  border-radius: 8px;
  padding: 1.5em;
  margin-bottom: 1.5em;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.02);
}

.contact-info h2 {
  color: var(--accent-color);
  font-size: 1.2em;
  margin-bottom: 0.8em;
}

.contact-item {
  margin-bottom: 0.8em;
  font-size: 1.05em;
}

/* Email highlight */
.email-display {
  background: var(--bg-light);
  padding: 0.8em 1.2em;
  border-radius: 6px;
  display: inline-block;
  font-family: 'Courier New', Courier, monospace;
  font-size: 1.1em;
  color: var(--primary-color);
  font-weight: 600;
  margin-top: 0.3em;
  border: 1px solid #e2e8f0;
}

/* Location section */
.location-section {
  background: var(--bg-light);
  border-radius: 8px;
  padding: 2em;
  margin-top: 1.5em;
  border: 1px solid #e8eaed;
}

.location-section h2 {
  color: var(--accent-color);
  margin-bottom: 0.6em;
  text-align: center;
  font-size: 1.3em;
}

.location-intro {
  text-align: center; 
  margin-bottom: 2em; 
  font-size: 1.05em;
  color: var(--text-color);
}

.location-intro a {
  color: var(--accent-color);
  text-decoration: none;
  border-bottom: 1px solid rgba(2, 132, 199, 0.3);
  transition: border-bottom-color 0.2s ease-in-out;
}

.location-intro a:hover {
  border-bottom-color: var(--accent-color);
}

.address-box {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 2.5em;
  align-items: center;
  margin-top: 1em;
}

.address-text {
  font-size: 1.05em;
  line-height: 1.7;
  color: var(--text-color);
}

.address-text strong {
  color: var(--primary-color);
  font-size: 1.15em;
}

.location-image {
  text-align: center;
}

.location-image img {
  max-width: 100%;
  height: 220px;
  object-fit: cover;
  border-radius: 6px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.08);
  filter: grayscale(10%);
  transition: filter 0.3s ease, transform 0.3s ease;
}

.location-image img:hover {
  filter: grayscale(0%);
  transform: translateY(-2px);
}

/* Responsive design */
@media (max-width: 768px) {
  .address-box {
    grid-template-columns: 1fr;
  }
  
  .location-image {
    order: -1;
  }
}
</style>

<div class="connect-header">
  <h1>Let's connect</h1>
  <p>
    I am always interested in discussing new ideas and potential collaborations.<br>
    Feel free to reach out if you share interests in viral evolution, host-pathogen interactions, or the systems biology of viral infections.
  </p>
</div>

<div class="contact-info">
  <h2>Email</h2>
  <div class="contact-item">
    <div class="email-display">ru.gonzalez@uvigo.gal</div>
  </div>
</div>

<div class="location-section">
  <h2>Location</h2>
  
  <p class="location-intro">
    I am based at the <a href="https://cinbio.es/en/" target="_blank">Center for Research in Nanomaterials and Biomedicine (CINBIO)</a>.
  </p>
  
  <div class="address-box">
    <div class="address-text">
      <strong>CINBIO – Universidade de Vigo</strong><br>
      Campus Universitario de Vigo<br>
      Lagoas, Marcosende<br>
      36310 Vigo, Spain<br>
    </div>
    
    <div class="location-image">
      <img src="/images/cinbio_campus.jpg" alt="CINBIO campus at University of Vigo">
    </div>
  </div>
</div>
