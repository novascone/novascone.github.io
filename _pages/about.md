---
layout: about
title: about
permalink: /
subtitle: <a href='https://www.usu.edu/'>Utah State University</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: > # text shown under the photo
    <p>Department of Physics</p>
    <p>Logan, Utah</p>
    <p><a href="https://github.com/novascone">GitHub</a></p>
    <p><a href="mailto:warren.novascone@usu.edu">warren.novascone@usu.edu</a></p>

selected_papers: false
social: false

announcements:
  enabled: false

latest_posts:
  enabled: false
---

I am a physics student at Utah State University, interested in gravitation and scientific computing.

<!-- The rest of the site continues below, one section after another. Section
     content lives in _includes/sections/; nav order matches nav_order. -->

<section id="publications" class="book-section">
  <h1 class="post-title">publications</h1>
  {% include sections/publications.liquid %}
</section>

<section id="projects" class="book-section">
  <h1 class="post-title">projects</h1>
  {% include sections/projects.liquid %}
</section>

<section id="repositories" class="book-section">
  <h1 class="post-title">repositories</h1>
  {% include sections/repositories.liquid %}
</section>

<section id="cv" class="book-section">
  <h1 class="post-title">CV</h1>
  {% include sections/cv.liquid %}
</section>

{% include sections/continuous_nav.liquid %}
