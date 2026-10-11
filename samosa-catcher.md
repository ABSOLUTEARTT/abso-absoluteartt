---
layout: default
title: Samosa Catcher
permalink: /samosa-catcher/
hide_theme_chrome: true
abso_landing: true
---

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
  .banner-wrapper > img {
    width: 100%;
    display: block;
  }
  .banner-overlay {
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    padding: 36px 20px 22px;
    box-sizing: border-box;
    background: linear-gradient(to bottom, transparent 0%, rgba(0,0,0,0.7) 40%, rgba(0,0,0,0.92) 100%);
    color: #fff;
    text-align: center;
  }
  .banner-overlay .main-logo {
    width: 55%;
    max-width: 220px;
    margin: 0 auto 10px;
    display: block;
    filter: drop-shadow(0 6px 12px rgba(0,0,0,0.5));
  }
  .banner-overlay p.banner-desc {
    font-size: clamp(11px, 2.5vw, 14px);
    line-height: 1.4;
    margin: 0 0 8px 0;
    color: #e0e0e0;
  }
  .banner-overlay p.banner-tagline {
    font-size: clamp(11px, 2.5vw, 14px);
    font-weight: 700;
    margin: 0;
    color: #fff;
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
      padding: 24px 16px 16px;
    }
    .banner-overlay .main-logo {
      width: 50%;
      max-width: 180px;
      margin-bottom: 6px;
    }
    .banner-overlay p.banner-desc {
      font-size: 10.5px;
      line-height: 1.35;
      margin-bottom: 4px;
    }
    .banner-overlay p.banner-tagline {
      font-size: 11px;
    }
    .info-banner-text {
      font-size: 8px;
      line-height: 1.35;
    }
    .info-banner-text h2 {
      font-size: 10px;
      margin-bottom: 2px;
    }
  }
</style>

{% include abso-header.html %}

<div class="banner-wrapper">
  <img src="{{ site.baseurl }}/assets/images/abso/samosa-catcher-header.png" alt="Samosa Catcher Banner" fetchpriority="high">
  <div class="banner-overlay">
    <img class="main-logo" src="{{ site.baseurl }}/assets/images/abso/samosa-catcher-logo.png" alt="Samosa Catcher Logo">
    <p class="banner-desc">Catch the golden samosas, dodge rotten ones and chilli bombs, grab crazy power-ups, and chase the ultimate high score. It's desi street-food chaos, served hot with memes.</p>
    <p class="banner-tagline">Main hun Samosa Catcher! &#127925;</p>
  </div>
</div>

<div class="game-container">
  <!-- Info Banner -->
  <div class="info-banner-wrapper">
    <img class="info-banner-bg" src="{{ site.baseurl }}/assets/images/abso/game-info-banner.png" alt="Samosa Catcher Info">
    <div class="info-banner-text">
      <h2>Samosa Catcher</h2>
      <p>Genre: Hyper-Casual, Arcade<br>
      Rating: Everyone<br>
      Release Date: TBA<br>
      Developer: ABSOLUTEARTT&reg; / abso.<br>
      Platforms: iOS &amp; Android</p>
    </div>
    <img class="info-badge" src="{{ site.baseurl }}/assets/images/abso/casual-icon.png" alt="Casual Badge">
  </div>

  <!-- Screenshots Header -->
  <img src="{{ site.baseurl }}/assets/images/abso/screenshots-icon.png" alt="Screenshots" class="abso-section-icon">
  
  <!-- Screenshots -->
  <img src="{{ site.baseurl }}/assets/images/abso/samosa-catcher-screen1.png" alt="Screenshot 1" class="img-rounded" loading="lazy">
  <img src="{{ site.baseurl }}/assets/images/abso/samosa-catcher-screen2.png" alt="Screenshot 2" class="img-rounded" loading="lazy">
  <img src="{{ site.baseurl }}/assets/images/abso/samosa-catcher-screen3.png" alt="Screenshot 3" class="img-rounded" loading="lazy">
  <img src="{{ site.baseurl }}/assets/images/abso/samosa-catcher-screen4.png" alt="Screenshot 4" class="img-rounded" loading="lazy" style="margin-bottom: 40px;">
  
  <!-- Download Header -->
  <img src="{{ site.baseurl }}/assets/images/abso/download-icon.png" alt="Download" class="abso-section-icon">
  
  <!-- Badges -->
  <div style="text-align: center; margin-bottom: 20px;">
    <img src="{{ site.baseurl }}/assets/images/abso/app-store-icons.png" alt="Google Play and App Store" style="width: 140px;" class="game-center">
  </div>
  
  <!-- Coming Soon -->
  <div class="abso-coming-soon-btn">coming soon</div>
  
  <!-- Home Button -->
  <div class="home-wrapper">
    <a href="{{ site.baseurl }}/mb-cow/"><img src="{{ site.baseurl }}/assets/images/abso/icon-left.webp" alt="Previous" loading="lazy" decoding="async" style="height: 40px;"></a>
    <a href="{{ site.baseurl }}/">
      <img src="{{ site.baseurl }}/assets/images/abso/home-icon.webp" alt="Home" loading="lazy" decoding="async" style="height: 64px;">
    </a>
    <a href="{{ site.baseurl }}/run-little-one/"><img src="{{ site.baseurl }}/assets/images/abso/icon-right.webp" alt="Next" loading="lazy" decoding="async" style="height: 40px;"></a>
  </div>
</div>

{% include abso-footer.html %}










