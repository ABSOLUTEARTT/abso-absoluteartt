---
layout: default
title: Twosome
permalink: /twosome/
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
    .banner-wrapper img {
    width: 100%;
    display: block;
  }
  .banner-text {
    position: absolute;
    bottom: 5%;
    left: 0;
    width: 100%;
    text-align: center;
    color: #fff;
    font-size: clamp(11px, 2.5vw, 14px);
    line-height: 1.4;
    padding: 0 10%;
    box-sizing: border-box;
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
    .banner-text {
      padding: 0 8%;
      bottom: 4%;
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
  <img src="{{ site.baseurl }}/assets/images/abso/twosome-header.webp" alt="Twosome Banner" fetchpriority="high" decoding="async" width="1316" height="1052">
  <div class="banner-text">
    Two souls. One orbit. Tap to reverse, dodge obstacles, and stay connected.
  </div>
</div>

<div class="game-container">

  <!-- Info Banner -->
  <div class="info-banner-wrapper">
    <img class="info-banner-bg" src="{{ site.baseurl }}/assets/images/abso/twosome-info-banner.webp" alt="Twosome Info" width="1024" height="359">
    <div class="info-banner-text">
      <h2>Twosome</h2>
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
  <img src="{{ site.baseurl }}/assets/images/abso/twosome-screen2.webp" alt="Screenshot 1" class="img-rounded" loading="lazy" decoding="async" width="1164" height="1945" style="margin-bottom: 40px;">
  
  
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
    <a href="{{ site.baseurl }}/run-little-one/"><img src="{{ site.baseurl }}/assets/images/abso/icon-left.webp" alt="Previous" loading="lazy" decoding="async" width="101" height="80" style="height: 40px; width: auto;"></a>
    <a href="{{ site.baseurl }}/">
      <img src="{{ site.baseurl }}/assets/images/abso/home-icon.webp" alt="Home" loading="lazy" decoding="async" width="160" height="81" style="height: 64px; width: auto;">
    </a>
    <a href="{{ site.baseurl }}/duet/"><img src="{{ site.baseurl }}/assets/images/abso/icon-right.webp" alt="Next" loading="lazy" decoding="async" width="94" height="80" style="height: 40px; width: auto;"></a>
  </div>
</div>

{% include abso-footer.html %}










