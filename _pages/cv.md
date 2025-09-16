---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<link rel="stylesheet" href="{{ base_path }}/assets/css/cv-style.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">

<style>
  .archive {
    width: 80%;
    margin: 0 auto;
    float: none;
    padding-right: 0;
  }
  
  @media (min-width: 80em) {
    .archive {
      width: 70%;
    }
  }
</style>

{% include cv-template.html %}

<div class="cv-download-links">
  <a href="{{ base_path }}/files/CV-PhD.pdf" class="btn btn--primary">Download CV as PDF</a>
  <a href="{{ base_path }}/cv-json/" class="btn btn--inverse">View JSON CV</a>
</div>
