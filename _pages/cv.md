---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
---

<style>
/* Button Style */
.download-btn-container {
  text-align: center;
  margin-bottom: 30px;
}

.btn-download {
  display: inline-block;
  background-color: #1a73e8; /* Your blue theme color */
  color: white !important;
  padding: 12px 24px;
  text-decoration: none;
  border-radius: 6px;
  font-weight: 600;
  font-size: 1.1em; /* Large legible text */
  box-shadow: 0 2px 5px rgba(0,0,0,0.2);
  transition: background-color 0.2s, transform 0.2s;
}

.btn-download:hover {
  background-color: #1557b0;
  transform: translateY(-2px);
  text-decoration: none;
}

/* PDF Container Style */
.pdf-container {
  width: 100%;
  height: 800px; /* Fixed nice height */
  border: 1px solid #e0e0e0;
  border-radius: 8px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.05);
}

/* Mobile Adjustment */
@media (max-width: 768px) {
  .pdf-container {
    height: 500px; /* Smaller on phones */
  }
}
</style>

<div class="download-btn-container">
  <a href="/files/cv.pdf" class="btn-download" target="_blank">
    <i class="fas fa-file-download"></i> Download full CV (PDF)
  </a>
</div>

<div class="pdf-container">
  <object data="/files/cv.pdf" type="application/pdf" width="100%" height="100%">
    <div style="text-align: center; padding: 40px; color: #666;">
      <p>Your browser does not support inline PDF viewing.</p>
      <p>Please click the button above to view the CV.</p>
    </div>
  </object>
</div>
