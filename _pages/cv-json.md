---
layout: archive
title: "CV"
permalink: /cv-json/
author_profile: false
redirect_from:
  - /resume-json
---

{% include base_path %}

<!-- Include Custom Styles -->
<link rel="stylesheet" href="{{ base_path }}/assets/css/cv-style.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">

<!-- Custom Inline Style for Layout -->
<style>
  .archive {
    width: 90%;
    margin: 0 auto;
    float: none;
    padding-right: 0;
  }

  @media (min-width: 80em) {
    .archive {
      width: 70%;
    }
  }

  .cv-download-links {
    text-align: center;
    margin-top: 2rem;
  }

  .cv-download-links .btn {
    margin: 0.5rem;
  }
</style>

<!-- Include JSON-based CV Template -->
{% include cv-template.html %}

<!-- CV Download Links -->
<div class="cv-download-links">
  <a href="{{ base_path }}/files/cv.pdf" class="btn btn--primary">
    <i class="fas fa-file-pdf"></i> Download CV as PDF
  </a>
  <a href="{{ base_path }}/cv/" class="btn btn--inverse">
    <i class="fas fa-file-alt"></i> View CV in Markdown
  </a>
</div>
