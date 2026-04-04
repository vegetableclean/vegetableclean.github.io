---
layout: page
title: CV
permalink: /cv/
nav: true
nav_order: 5
description: CV (PDF)
---

# My Curriculum Vitae

Welcome to my CV page.
Here you can view or download my most updated CV.

<div class="max-w-3xl mx-auto my-8 p-4 border rounded">
  <p style="text-align:center; margin-bottom: 1rem;">
    <a class="btn btn-primary" href="{{ '/assets/cv/chieh_cv.pdf' | relative_url }}" download>
      Download CV (PDF)
    </a>
  </p>

  <div style="width: 100%; height: 90vh; border: 1px solid #ddd; border-radius: 8px; overflow: hidden;">
    <iframe
      src="{{ '/assets/cv/chieh_cv.pdf' | relative_url }}#view=FitH"
      style="width:100%; height:100%; border:0;"
      title="CV PDF"
    ></iframe>
  </div>

  <noscript>
    <p>PDF preview requires JavaScript. You can <a href="{{ '/assets/cv/chieh_cv.pdf' | relative_url }}">download the CV here</a>.</p>
  </noscript>
</div>
