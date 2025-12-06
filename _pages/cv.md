---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
---

<style>
/* Button Styling */
.btn-download {
  display: inline-block;
  background-color: #1c7ed6;
  color: #fff !important;
  padding: 12px 25px;
  text-decoration: none;
  border-radius: 6px;
  font-weight: 600;
  font-size: 1.1em;
  margin-bottom: 30px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  transition: background-color 0.2s;
}

.btn-download:hover {
  background-color: #145fa8;
  text-decoration: none;
}

.btn-container {
  text-align: center;
}

/* PDF Embed Styling */
.pdf-viewer {
  width: 100%;
  height: 800px; /* Provides a large area for viewing */
  border: 1px solid #ddd;
  border-radius: 8px;
}

@media (max-width: 768px) {
  .pdf-viewer {
    height: 500px; /* Reduced height on mobile */
  }
}
</style>

<div class="btn-container">
  <a href="{{ site.baseurl }}/files/cv.pdf" class="btn-download" target="_blank">
    <i class="fas fa-file-download"></i> Download Full CV (PDF)
  </a>
</div>

<object data="{{ site.baseurl }}/files/cv.pdf" type="application/pdf" class="pdf-viewer">
  <div style="text-align: center; padding: 50px; background: #f9f9f9; border-radius: 8px;">
    <p>Your browser does not support inline PDF viewing.</p>
    <a href="{{ site.baseurl }}/files/cv.pdf" style="color: #1c7ed6; font-weight: bold;">Click here to download the PDF</a>
  </div>
</object>
