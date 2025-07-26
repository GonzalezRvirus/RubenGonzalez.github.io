---
layout: single
title: "Contact"
permalink: /contact/
author_profile: true
redirect_from:
  - /resume
---

<style>
/* Connect section */
.connect-header {
  text-align: center;
  margin-bottom: 3em;
  padding: 2em;
  background: #f8f9fa;
  border-radius: 9px;
}

.connect-header h1 {
  color: #202124;
  margin-bottom: 2em;
  font-size: 2.2em;
  font-weight: 500;
}

.connect-header p {
  font-size: 1.1em;
  color: #5f6368;
  line-height: 1;
  margin: 0;
}

/* Contact info box */
.contact-info {
  background: #ffffff;
  border: 1px solid #e8eaed;
  border-radius: 8px;
  padding: 2em;
  margin-bottom: 2em;
  box-shadow: 0 1px 3px rgba(0,0,0,0.05);
}

.contact-info h2 {
  color: #1a73e8;
  font-size: 1.4em;
  margin-bottom: 1em;
}

.contact-item {
  margin-bottom: 1.5em;
  font-size: 1.05em;
}

.contact-label {
  color: #1a73e8;
  font-weight: 600;
  display: inline-block;
  margin-bottom: 0.3em;
}

.contact-value {
  color: #3c4043;
  font-size: 1.1em;
}

.contact-value a {
  color: #1a73e8;
  text-decoration: none;
}

.contact-value a:hover {
  text-decoration: underline;
}

/* Email highlight */
.email-display {
  background: #f0f7ff;
  padding: 1em 1.5em;
  border-radius: 6px;
  display: inline-block;
  font-family: 'Courier New', monospace;
  font-size: 1.1em;
  color: #202124;
  margin-top: 0.5em;
}

/* Location section */
.location-section {
  background: #f0f7ff;
  border-radius: 8px;
  padding: 2em;
  margin-top: 2em;
}

.location-section h2 {
  color: #1a73e8;
  margin-bottom: 1em;
  text-align: center;
}

.address-box {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 2em;
  align-items: center;
  margin-top: 1.5em;
}

.address-text {
  font-size: 1.05em;
  line-height: 1.8;
  color: #3c4043;
}

.address-text strong {
  color: #202124;
}

.location-image {
  text-align: center;
}

.location-image img {
  max-width: 100%;
  height: auto;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
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
    I'm always interested in discussing new ideas and potential collaborations.<br>
    Feel free to reach out if you share interests in viral evolution, host-pathogen interactions, or model system biology.
  </p>
</div>

<div class="contact-info">
  <h2>Email</h2>
  <div class="contact-item">
    <div class="email-display">ruben.gonzalez-miguelez@pasteur.fr</div>
  </div>
</div>

<div class="location-section">
  <h2>Location</h2>
  
  <p style="text-align: center; margin-bottom: 2em;">
    We are located at the <a href="http://salehlab.eu" target="_blank">Viruses and RNAi Unit</a>, Institut Pasteur
  </p>
  
  <div class="address-box">
    <div class="address-text">
      <strong>Institut Pasteur</strong><br>
      Viruses and RNAi Unit<br>
      28 Rue du Docteur Roux<br>
      75015 Paris, France<br><br>
    </div>
    
    <div class="location-image">
      <img src="/images/center_pasteur.jpg" alt="Institut Pasteur campus">
    </div>
  </div>
</div>
