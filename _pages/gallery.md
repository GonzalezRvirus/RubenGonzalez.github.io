---
layout: archive
title: "Gallery"
permalink: /gallery/
author_profile: true
---

<!-- Container for the image gallery -->
<div class="container">

  <!-- Full-width images with number text -->
  <div class="mySlides">
    <div class="numbertext">1 / 6</div>
      <img src="/images/6k2.png" style="width:100%">
  </div>

  <div class="mySlides">
    <div class="numbertext">2 / 6</div>
      <img src="/images/populations.jpg" style="width:100%">
  </div>

  <!-- Next and previous buttons -->
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>

  <!-- Image text -->
  <div class="caption-container">
    <p id="caption"></p>
  </div>

  <!-- Thumbnail images -->
  <div class="row">
    <div class="column">
      <img class="demo cursor" src="/images/6k2.png" style="width:100%" onclick="currentSlide(1)" alt="Self-assembled vesicles created by the potyviral protein 6K2">
    </div>
    <div class="column"> 
      <img class="demo cursor" src="/images/populations.jpg" style="width:100%" onclick="currentSlide(2)" alt="Presenting the research.">
    </div>
    
