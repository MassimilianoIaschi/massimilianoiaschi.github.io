---
layout: page
title: Curriculum Vitae
permalink: /cv-pdf/
nav: true
nav_order: 5
description: The most recent version of my Curriculum Vitae
---

<style>
  /* --- CV Page Styling --- */
  .cv-container {
    max-width: 900px;
    margin: 0 auto;
    text-align: center;
  }

  .cv-frame {
    width: 100%;
    height: 85vh;
    border: 1px solid #ddd;
    border-radius: 6px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05);
  }

  .cv-download {
    display: inline-block;
    margin-top: 20px;
    padding: 12px 24px;
    background-color: #0056b3;
    color: #fff !important;
    font-weight: 500;
    border-radius: 6px;
    text-decoration: none;
    transition: background-color 0.3s ease, transform 0.2s ease;
  }

  .cv-download:hover {
    background-color: #003f88;
    transform: translateY(-2px);
  }

  .cv-download:active {
    background-color: #002b5e;
    transform: translateY(0);
  }

  .cv-note {
    margin-top: 15px;
    font-size: 0.95em;
    color: #666;
  }

  @media (max-width: 768px) {
    .cv-frame {
      height: 70vh;
    }
  }
</style>

<div class="cv-container">

   <a 
    href="{{ '/assets/files/cv_oct_23_25.pdf' | relative_url }}" 
    download="My_CV.pdf" 
    class="cv-download">
    ⬇️ Download CV (PDF)
  </a>

  <p class="cv-note"> </p>

  <iframe 
    class="cv-frame"
    src="{{ '/assets/files/cv_oct_23_25.pdf' | relative_url }}">
    This browser does not support embedded PDFs. Please use the download link below.
  </iframe>
</div>
