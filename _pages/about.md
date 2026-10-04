---
layout: about
title: About
permalink: /
subtitle: <a href='https://econ.wisc.edu/'>University of Wisconsin-Madison, Department of Economics</a>.

profile:
  align: right
  image: profile.jpg
  image_circular: false # crops the image to make it circular
  address: #>
    #<p>yuya.shimizu [at mark] wisc.edu</p>

news: false  # includes a list of news items
latest_posts: false  # includes a list of the newest posts
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page
---

Hi! I am a Ph.D. candidate at the University of Wisconsin-Madison. My research interests are in the intersection of Econometrics, Causal Inference, and Machine Learning for applications in Applied Microeconomics. 

<div style="height: 0.5em;"></div>

<p class="text-center"><strong>I will be on the job market for the 2026-2027 academic year.</strong></p>

<div style="height: 0.5em;"></div>

In my <a href="{{ '/assets/pdf/Shimizu_JMP_Embedding.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer" style="text-decoration: underline;">Job Market Paper</a>, I develop theoretical foundations for incorporating numerical representations of images and text into econometric models and propose a new bootstrap test for the workflow.

<style>
  .jmp-figure {
    display: flow-root;
    width: 100%;
    max-width: 100%;
  }

  .jmp-figure img {
    clip-path: inset(0 1px 0 0);
  }

  @media (min-width: 576px) {
    .jmp-figure {
      width: calc(70% - 1rem);
    }
  }
</style>

<figure class="jmp-figure mt-4 mb-4 text-center">
  <img src="{{ '/assets/img/embed.png' | relative_url }}" class="img-fluid d-block w-100" width="3376" height="1274" alt="Labor supply elasticity estimates with 90% and 95% confidence intervals for the original BERT representation, 25 random seeds, and median aggregation." loading="lazy">
  <figcaption class="mt-2" style="font-size: 0.75rem; line-height: 1.4;">
    <strong>Robustness of estimated values to nonidentification of text representations</strong><br>
    Parameter of interest: Labor supply elasticity, with controls for job description text.<br>
    Data: Amazon MTurk, an online labor market platform.
  </figcaption>
</figure>

<!--
* **Primary Interests:** Econometrics, Causal Inference, Machine Learning

* **Secondary Interests:** Applied Microeconomics, Industrial Organization
<br>
-->

<div style="height: 2em;"></div>

Email: [yuya.shimizu@wisc.edu](mailto:yuya.shimizu@wisc.edu)

<p>Links: <a href="{{ '/assets/pdf/Shimizu_JMP_Embedding.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer">JMP</a> &#124; <a href="{{ '/assets/pdf/CV_Yuya_Shimizu.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer">CV</a> &#124; <a href="https://scholar.google.com/citations?user=YB8k6cEAAAAJ&amp;hl=en" target="_blank" rel="noopener noreferrer">Google Scholar</a></p>
