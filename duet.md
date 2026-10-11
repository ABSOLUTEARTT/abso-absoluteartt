---
layout: default
title: Duet
permalink: /duet/
hide_theme_chrome: true
abso_landing: true
---

<link href="https://fonts.googleapis.com/css2?family=Lato:wght@400;600;700;900&display=swap" rel="stylesheet">
<style>
  .game-container {
    width: min(100%, 660px);
    margin: 0 auto;
    box-sizing: border-box;
    padding-top: 20px;
    background: #ffffff;
  }
  .game-center {
    display: block;
    margin: 0 auto;
    max-width: 100%;
    width: auto;
    height: auto;
  }
  .img-rounded {
    display: block;
    margin: 0 auto;
    width: 88.7%;
    border-radius: 20px;
    margin-bottom: 20px;
  }
  .banner-wrapper {
    position: relative;
    width: 100%;
    margin-bottom: 20px;
    border-radius: 42px;
    overflow: hidden;
  }
  .banner-wrapper img {
    width: 100%;
    display: block;
  }

  .banner-overlay {
    position: absolute;
    bottom: 5.5%;
    left: 8%;
    right: 8%;
    text-align: left;
    pointer-events: none;
    z-index: 10;
  }
  .banner-overlay .banner-logo {
    width: clamp(75px, 20.7%, 138px);
    height: auto;
    display: block;
    margin-bottom: 8px;
    filter: drop-shadow(0 2px 4px rgba(0, 0, 0, 0.4));
  }
  .banner-overlay .banner-text {
    color: #e8e2d9;
    font-family: 'Lato', -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    font-size: clamp(10px, 2.3vw, 15px);
    font-weight: 700;
    line-height: 1.3;
    letter-spacing: -0.01em;
    margin: 0;
    white-space: nowrap;
    text-shadow: 0 2px 6px rgba(0, 0, 0, 0.5);
  }

  .info-banner-wrapper {
    position: relative;
    width: 88.7%;
    margin: 0 auto 40px auto;
    border-radius: 20px;
    overflow: hidden;
  }
  .info-banner-wrapper > img.info-banner-bg {
    width: 100%;
    display: block;
  }
  .info-banner-text {
    position: absolute;
    top: 50%;
    left: 8%;
    transform: translateY(-50%);
    color: #fff;
    font-size: 11px;
    line-height: 1.5;
    text-align: left;
  }
  .info-banner-text h2 {
    margin: 0 0 4px 0;
    font-size: 14px;
    font-weight: 700;
    color: #fff;
  }
  .info-banner-text p {
    margin: 0;
  }
  .info-banner-wrapper .info-badge {
    position: absolute;
    bottom: 8%;
    right: 6%;
    width: clamp(38px, 9.5%, 60px) !important;
    height: auto !important;
    display: block !important;
    z-index: 10;
  }

  @media (max-width: 520px) {
    .banner-wrapper {
      border-radius: 28px;
    }
    .banner-overlay {
      bottom: 4.5%;
      left: 7%;
      right: 7%;
    }
    .banner-overlay .banner-logo {
      margin-bottom: 4px;
    }
    .banner-overlay .banner-text {
      font-size: clamp(8.5px, 2.5vw, 12px);
    }
    .info-banner-text {
      font-size: 8px;
    }
    .info-banner-text h2 {
      font-size: 10px;
    }
  }
</style>

{% include abso-header.html %}

<div class="banner-wrapper">
  <img src="{{ site.baseurl }}/assets/images/abso/duet-banner.webp" alt="Duet Banner" fetchpriority="high" decoding="async" width="1320" height="1060">
  <div class="banner-overlay">
    <img class="banner-logo" src="{{ site.baseurl }}/assets/images/abso/duet-logo.webp" alt="Duet" width="300" height="100">
    <p class="banner-text">Two circles. Two colours. One perfect rhythm.</p>
  </div>
</div>

<div class="game-container">
  <!-- Info Banner -->
  <div class="info-banner-wrapper">
    <img class="info-banner-bg" src="{{ site.baseurl }}/assets/images/abso/duet-info-banner.webp" alt="Duet Info" width="1024" height="365">
    <div class="info-banner-text">
      <h2>Duet</h2>
      <p>Genre: Hyper/Micro-Casual, Arcade<br>
      Rating: Everyone<br>
      Release Date: TBA<br>
      Developer: ABSOLUTEARTT&reg; / abso.<br>
      Platforms: iOS, Android</p>
    </div>
    <img class="info-badge" src="{{ site.baseurl }}/assets/images/abso/micro-icon.webp" alt="Micro Badge" width="115" height="108">
  </div>

  <!-- Screenshots Header -->
  <img src="{{ site.baseurl }}/assets/images/abso/screenshots-icon.webp" alt="Screenshots" class="abso-section-icon" width="671" height="333">
  
  <!-- Screenshots -->
  <img src="{{ site.baseurl }}/assets/images/abso/duet-screenshot1.webp" alt="Screenshot 1" class="img-rounded" loading="lazy" decoding="async" width="1164" height="1945" style="margin-bottom: 40px;">
  
  <!-- Download Header -->
  <img src="{{ site.baseurl }}/assets/images/abso/download-icon.webp" alt="Download" class="abso-section-icon" width="650" height="325">
  
  <!-- Badges -->
  <div style="text-align: center; margin-bottom: 20px;">
    <img src="{{ site.baseurl }}/assets/images/abso/app-store-icons.webp" alt="Google Play and App Store" style="width: 140px;" class="game-center" width="866" height="612">
  </div>
  
  <!-- Coming Soon -->
  <div class="abso-coming-soon-btn">coming soon</div>
  
  <!-- Home Button -->
  <div class="home-wrapper">
    <a href="{{ site.baseurl }}/twosome/"><img src="{{ site.baseurl }}/assets/images/abso/icon-left.webp" alt="Previous" loading="lazy" decoding="async" width="101" height="80" style="height: 40px; width: auto;"></a>
    <a href="{{ site.baseurl }}/">
      <img src="{{ site.baseurl }}/assets/images/abso/home-icon.webp" alt="Home" loading="lazy" decoding="async" width="160" height="81" style="height: 64px; width: auto;">
    </a>
    <a href="{{ site.baseurl }}/mb-cow/"><img src="{{ site.baseurl }}/assets/images/abso/icon-right.webp" alt="Next" loading="lazy" decoding="async" width="94" height="80" style="height: 40px; width: auto;"></a>
  </div>
</div>

{% include abso-footer.html %}





