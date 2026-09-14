---
layout: home
title: Home
---

<section class="video-hero">
  <video class="video-bg" autoplay muted loop playsinline aria-hidden="true"
         poster="{{ '/assets/video/croquis-poster.jpg' | relative_url }}">
    <source src="{{ '/assets/video/croquis-demo.mp4' | relative_url }}" type="video/mp4">
  </video>
  <div class="video-hero-overlay">
    <h1>The future of transit planning is open.</h1>
  </div>
</section>

<section class="hero-message wrapper">
  <p class="hero-message-text">Unlock open-source software to design and plan the public transport networks of tomorrow.</p>
  <div class="hero-links">
    <a class="btn-primary" href="{{ '/projects/' | relative_url }}">See our projects</a>
    <a class="btn-secondary" href="{{ '/about/' | relative_url }}">About</a>
  </div>
</section>