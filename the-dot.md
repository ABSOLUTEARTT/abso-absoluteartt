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
  
  <div class="dot-section">
    <img src="{{ site.baseurl }}/assets/images/abso/the-dot-meet.webp" alt="Meet the Dot." fetchpriority="high" width="940" height="1535">
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
