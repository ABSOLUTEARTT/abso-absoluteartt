---
layout: default
title: The Dot
permalink: /the-dot/
hide_theme_chrome: true
abso_landing: true
---

<style>
  .dot-container {
    width: min(100%, 660px);
    margin: 0 auto;
    box-sizing: border-box;
    padding-top: 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .dot-section {
    position: relative;
    width: min(88.7%, 420px);
    margin: 0 auto 30px auto;
    border-radius: 28px;
    overflow: hidden;
  }
  .dot-section img {
    width: 100%;
    height: auto;
    display: block;
  }
  @media (max-width: 520px) {
    .dot-section {
      width: min(92%, 360px);
      border-radius: 22px;
      margin-bottom: 24px;
    }
  }
</style>

{% include abso-header.html %}

<div class="dot-container">

  <!-- Interactive Dot Mood Lab (GSAP Feature 1) -->
  <div class="abso-mood-stage" id="abso-mood-stage">
    <div class="abso-mood-speech" id="abso-mood-speech">
      <span class="abso-mood-speech__emoji" id="abso-mood-emoji">👋</span>
      <span class="abso-mood-speech__text" id="abso-mood-text">“Tap me to poke my moods!”</span>
    </div>

    <div class="abso-mood-avatar-wrap" id="abso-mood-avatar" role="button" tabindex="0" aria-label="Poke The Dot to cycle moods">
      <img id="abso-mood-img" src="{{ site.baseurl }}/assets/images/abso/the-dot-meet.webp" alt="The Dot - Current Mood" width="940" height="1535" fetchpriority="high">
    </div>

    <div class="abso-mood-controls" aria-label="Select mood">
      <button type="button" class="abso-mood-pill is-active" data-mood="0" data-img="{{ site.baseurl }}/assets/images/abso/the-dot-meet.webp" data-quote="“Hi! I am The Dot. Perfectly round, surprisingly unpredictable.”" data-emoji="👋">
        <span class="abso-mood-pill__dot"></span>Meet
      </button>
      <button type="button" class="abso-mood-pill" data-mood="1" data-img="{{ site.baseurl }}/assets/images/abso/the-dot-many-lives.webp" data-quote="“One Dot. Many Lives. An artist, a dreamer, a rogue runaway pebble.”" data-emoji="🎭">
        <span class="abso-mood-pill__dot"></span>Many Lives
      </button>
      <button type="button" class="abso-mood-pill" data-mood="2" data-img="{{ site.baseurl }}/assets/images/abso/the-dot-cute-curious.webp" data-quote="“Cute. Curious. Pure unadulterated Chaos!”" data-emoji="💥">
        <span class="abso-mood-pill__dot"></span>Chaos & Cute
      </button>
      <button type="button" class="abso-mood-pill" data-mood="3" data-img="{{ site.baseurl }}/assets/images/abso/the-dot-endless.webp" data-quote="“One little Dot. Endless possibilities across every canvas.”" data-emoji="✨">
        <span class="abso-mood-pill__dot"></span>Endless
      </button>
    </div>

    <p class="abso-mood-hint">💡 Tap The Dot above or pick a mood pill to see it react!</p>
  </div>

  <div class="dot-section">
    <img src="{{ site.baseurl }}/assets/images/abso/the-dot-meet.webp" alt="Meet the Dot." loading="lazy" decoding="async" width="940" height="1535">
  </div>
  
  <div class="dot-section">
    <img src="{{ site.baseurl }}/assets/images/abso/the-dot-many-lives.webp" alt="One Dot. Many Lives." loading="lazy" decoding="async" width="941" height="1489">
  </div>
  
  <div class="dot-section">
    <img src="{{ site.baseurl }}/assets/images/abso/the-dot-cute-curious.webp" alt="Cute. Curious. Chaos." loading="lazy" decoding="async" width="940" height="1490">
  </div>
  
  <div class="dot-section">
    <img src="{{ site.baseurl }}/assets/images/abso/the-dot-endless.webp" alt="One little Dot. Endless possibilities." loading="lazy" decoding="async" width="1059" height="1718">
  </div>
  
  <!-- Home Button -->
  <div class="home-wrapper" style="justify-content: center; margin: 20px auto 40px auto;">
    <a href="{{ site.baseurl }}/">
      <img src="{{ site.baseurl }}/assets/images/abso/home-icon.webp" alt="Home" loading="lazy" decoding="async" width="160" height="81" style="height: 64px; width: auto;">
    </a>
  </div>

</div>

{% include abso-footer.html %}
