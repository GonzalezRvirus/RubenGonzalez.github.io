---
layout: archive
title: "Gallery"
permalink: /gallery/
author_profile: true
---
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
      <img class="demo cursor" src="/images/fitotron.png" style="width:100%" onclick="currentSlide(1)" alt="Evaluating infections">
    </div>
    <div class="column"> 
      <img class="demo cursor" src="/images/santi.png" style="width:100%" onclick="currentSlide(2)" alt="Discussing data">
    </div>
    <div class="column">
      <img class="demo cursor" src="/images/6k2.png" style="width:100%" onclick="currentSlide(3)" alt="Viral vesicles">
    </div>
    <div class="column">
      <img class="demo cursor" src="/images/populations.png" style="width:100%" onclick="currentSlide(4)" alt="Presenting work"> 
</div>

  
var slideIndex = 1;
showSlides(slideIndex);

// Next/previous controls
function plusSlides(n) {
  showSlides(slideIndex += n);
}

// Thumbnail image controls
function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("demo");
  var captionText = document.getElementById("caption");
  if (n > slides.length) {slideIndex = 1}
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";
  }
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";
  dots[slideIndex-1].className += " active";
  captionText.innerHTML = dots[slideIndex-1].alt;
}

