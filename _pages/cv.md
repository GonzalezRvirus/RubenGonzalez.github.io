---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
---

<style>
/* --- GLOBAL VARIABLES --- */
:root {
  --primary-color: #0f172a; 
  --accent-color: #0284c7; 
  --text-color: #334155; 
  --bg-light: #f8fafc; 
}

/* --- INTRO SECTION --- */
.cv-intro {
  text-align: center;
  margin-bottom: 2em;
  color: var(--text-color);
  font-size: 1.1em;
  line-height: 1.6;
}

/* --- BUTTON STYLING --- */
.btn-container {
  text-align: center;
  margin-bottom: 40px;
}

.btn-download {
  display: inline-flex;
  align-items: center;
  gap: 10px;
  background-color: var(--accent-color);
  color: #ffffff !important;
  padding: 14px 28px;
  text-decoration: none;
  border-radius: 6px;
  font-weight: 600;
  font-size: 1.1em;
  box-shadow: 0 4px 10px rgba(2, 132, 199, 0.2);
  transition: background-color 0.2s ease, transform 0.2s ease, box-shadow 0.2s ease;
}

.btn-download:hover {
  background-color: #0369a1;
  transform: translateY(-2px);
  box-shadow: 0 6px 15px rgba(2, 132, 199, 0.3);
  text-decoration: none;
}

/* Inline SVG Icon */
.btn-download svg {
  width: 20px;
  height: 20px;
  fill: currentColor;
}

/* --- IFRAME PDF VIEWER --- */
.pdf-viewer-container {
  width: 100%;
  height: 850px; 
  border: 1px solid #e2e8f0;
  border-radius: 8px;
  background-color: var(--bg-light);
  box-shadow: 0 4px 15px rgba(0,0,0,0.03);
  overflow: hidden; 
}

.pdf-viewer-container iframe {
  width: 100%;
  height: 100%;
  border: none;
}

@media (max-width: 768px) {
  .pdf-viewer-container {
    height: 600px; 
  }
}
</style>

<div class="cv-intro">
  <p>A comprehensive overview of my academic trajectory, research funding, and scientific output.</p>
</div>

<div class="btn-container">
  <a href="{{ site.baseurl }}/files/cv.pdf" class="btn-download" target="_blank" rel="noopener noreferrer">
    <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
      <path d="M19 9h-4V3H9v6H5l7 7 7-7zM5 18v2h14v-2H5z"/>
    </svg>
    Download Full CV (PDF)
  </a>
</div>

<div class="pdf-viewer-container">
  <iframe src="https://docs.google.com/gview?url={{ site.url }}{{ site.baseurl }}/files/cv.pdf&embedded=true" frameborder="0">
    <div style="text-align: center; padding: 50px;">
      <p>Your browser cannot display the CV viewer.</p>
      <a href="{{ site.baseurl }}/files/CV.pdf" style="color: #0284c7; font-weight: bold;">Click here to download the PDF</a>
    </div>
  </iframe>
</div>
