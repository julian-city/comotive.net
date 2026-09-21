---
layout: home
title: Accueil
lang: fr
permalink: /
---

<section class="video-hero">
  <video class="video-bg" autoplay muted loop playsinline aria-hidden="true"
         poster="{{ '/assets/video/croquis-poster.jpg' | relative_url }}">
    <source src="{{ '/assets/video/croquis-demo.mp4' | relative_url }}" type="video/mp4">
  </video>
  <div class="video-hero-overlay">
    <h1>{{ site.data.i18n[site.active_lang].hero_headline }}</h1>
  </div>
</section>

<section class="hero-message wrapper">
  <p class="hero-message-text">{{ site.data.i18n[site.active_lang].hero_message }}</p>
  <div class="hero-links">
    <a class="btn-primary" href="{{ '/projects/' | relative_url }}">{{ site.data.i18n[site.active_lang].btn_projects }}</a>
    <a class="btn-secondary" href="{{ '/about/' | relative_url }}">{{ site.data.i18n[site.active_lang].btn_about }}</a>
  </div>
</section>
