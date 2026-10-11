---
layout: default
title: Games
permalink: /games/
hide_theme_chrome: true
abso_landing: true
---

{% include abso-header.html %}

<div class="abso-landing" aria-label="Games">
  <section class="abso-stack" aria-label="Games List">
    <figure class="abso-card abso-card--full abso-card--hero" style="margin-bottom: 20px;">
      <a href="{{ site.baseurl }}/mb-cow">
        <img src="{{ '/assets/images/abso/mahabharata-code-of-war.webp' | relative_url }}" fetchpriority="high" decoding="async" alt="Mahabharata Code of War">
      </a>
    </figure>

    <figure class="abso-card abso-card--narrow">
      <a href="{{ site.baseurl }}/samosa-catcher">
        <img src="{{ '/assets/images/abso/samosa-catcher.webp' | relative_url }}" loading="lazy" decoding="async" alt="Samosa Catcher" style="width: 100%; border-radius: 42px; display: block;">
      </a>
    </figure>

    <figure class="abso-card abso-card--narrow">
      <a href="{{ site.baseurl }}/run-little-one">
        <img src="{{ '/assets/images/abso/run-little-one.webp' | relative_url }}" loading="lazy" decoding="async" alt="Run, Little One.">
      </a>
    </figure>

    <figure class="abso-card abso-card--narrow">
      <a href="{{ site.baseurl }}/twosome">
        <img src="{{ '/assets/images/abso/twosome.webp' | relative_url }}" loading="lazy" decoding="async" alt="Twosome">
      </a>
    </figure>

    <figure class="abso-card abso-card--narrow" style="margin-bottom: 40px;">
      <a href="{{ site.baseurl }}/duet">
        <img src="{{ '/assets/images/abso/dual-duet.webp' | relative_url }}" loading="lazy" decoding="async" alt="Duet">
      </a>
    </figure>
  </section>

  <!-- Home Button -->
  <div class="home-wrapper" style="justify-content: center; margin: 30px auto 40px auto;">
    <a href="{{ site.baseurl }}/">
      <img src="{{ site.baseurl }}/assets/images/abso/home-icon.webp" alt="Home" loading="lazy" decoding="async" style="height: 64px;">
    </a>
  </div>
</div>

{% include abso-footer.html %}
