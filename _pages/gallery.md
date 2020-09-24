---
layout: archive
title: "Gallery"
permalink: /gallery/
author_profile: true
---

<!-- The grid: four columns -->
<div class="row">
  <div class="column">
    <img src="/images/6k2.png" alt="Self-assembled vesicles created by the potyviral protein 6K2" onclick="myFunction(this);">
  </div>
  <div class="column">
    <img src="/images/populations.jpg" alt="Presenting research" onclick="myFunction(this);">
  </div>

</div>

<!-- The expanding image container -->
<div class="container">
  <!-- Close the image -->
  <span onclick="this.parentElement.style.display='none'" class="closebtn">&times;</span>

  <!-- Expanded image -->
  <img id="expandedImg" style="width:100%">

  <!-- Image text -->
  <div id="imgtext"></div>
</div>
