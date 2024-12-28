---
layout: archive
title: "<i>Curriculum vitae<i>"
permalink: /cv/
author_profile: true
---

<div class="pdf-container"> <object data="/_pages/CV.pdf" type="application/pdf" width="100%" height="100%"> <!-- Fallback content if PDF can't be displayed --> <p> Your browser may not support embedded PDFs.<br> <a href="/_pages/CV.pdf" target="_blank" rel="noopener">Click here to download the PDF</a>. </p> </object> </div>
Then add CSS to control the container’s size:

<style> .pdf-container { /* For example, 80% of the viewport height (vh) */ width: 100%; height: 80vh; max-width: 900px; /* Optional max width to prevent overexpansion */ margin: 0 auto; /* Center horizontally */ border: 1px solid #ccc; border-radius: 4px; overflow: hidden; } </style>

