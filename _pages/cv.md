---
layout: page
title: "Curriculum Vitae"
navbar_title: "CV"  
permalink: /cv/
description: 
nav: true
nav_order: 8
---

- [Download CV]({{ site.baseurl }}/assets/pdf/Kai_CV.pdf)

<br>


<!-- Responsive PDF embed -->
<style>
  /* Contain and scale the PDF nicely across devices */
  .pdf-embed { margin: 0 auto; max-width: 100%; }
  .pdf-embed object {
    width: 100%;
    height: 80vh;           /* Tall on desktop/laptop */
    border: 0;
  }
  @media (max-width: 768px) {
    .pdf-embed object { height: 70vh; }  /* Tablets */
  }
  @media (max-width: 480px) {
    .pdf-embed object { height: 65vh; }  /* Phones */
  }
</style>

<div class="pdf-embed">
  <object data="{{ site.baseurl }}/assets/pdf/Kai_CV.pdf"
          type="application/pdf">
    <p>Your browser can’t display PDFs inline.
       <a href="{{ site.baseurl }}/assets/pdf/Kai_CV.pdf">Tap to download the PDF</a>.
    </p>
  </object>
</div>
