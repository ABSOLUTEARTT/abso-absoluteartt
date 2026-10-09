---
layout: default
title: Mahabharata Code of War
permalink: /mb-cow/
hide_theme_chrome: true
abso_landing: true
---

<link href="https://fonts.googleapis.com/css2?family=Lato:wght@400;600;700;900&display=swap" rel="stylesheet">
<style>
  body {
    background-color: #fff !important;
  }
  .cow-container {
    width: min(100%, 660px);
    margin: 0 auto;
    box-sizing: border-box;
    padding-top: 20px;
  }
  .cow-container .cow-center,
  .cow-center {
    display: block;
    margin: 0 auto;
    max-width: 100%;
    width: auto;
    height: auto;
  }

  .mb-30 { margin-bottom: 30px !important; }
  .mb-20 { margin-bottom: 20px !important; }
  .mb-10 { margin-bottom: 10px !important; }
  .mt-30 { margin-top: 30px !important; }
  
  .cow-container .img-rounded,
  .img-rounded {
    display: block;
    margin: 0 auto;
    width: 88.7%;
    border-radius: 20px;
  }
  
  /* Banner Overlay */
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
    bottom: 0;
    left: 0;
    width: 100%;
    padding: 40px 20px 25px;
    box-sizing: border-box;
    background: linear-gradient(to bottom, transparent, rgba(0,0,0,0.8) 50%, rgba(0,0,0,0.95));
    color: #fff;
    text-align: center;
  }
  .banner-overlay h1 {
    display: none;
  }
  .banner-overlay .main-logo {
    width: 85%;
    max-width: 250px;
    margin: 0 auto 10px;
    display: block;
  }
  .banner-overlay p.banner-desc {
    font-size: clamp(11px, 2.5vw, 14px);
    line-height: 1.4;
    margin: 0 0 10px 0;
    color: #e0e0e0;
  }
  .banner-overlay p.banner-tagline {
    font-size: clamp(11px, 2.5vw, 14px);
    font-weight: 700;
    margin: 0;
    color: #fff;
  }
  
  /* Info Card */
  .info-card {
    position: relative;
    width: 88.7%;
    margin: 0 auto;
    border-radius: 20px;
    background: linear-gradient(to right, #12192b 0%, #12192b 55%, transparent 100%), url('{{ site.baseurl }}/assets/images/mb-cow/Layer 4 copy.png');
    background-size: cover;
    background-position: right center;
    background-color: #12192b;
    color: #fff;
    text-align: left;
    padding: 25px 20px;
    padding-right: 90px;
    overflow: hidden;
  }
  .info-card h2 {
    margin: 0 0 10px 0;
    font-size: clamp(15px, 3.5vw, 20px);
    font-weight: 900;
  }
  .info-card p {
    margin: 2px 0;
    font-size: clamp(11px, 2.5vw, 14px);
    color: #d0d0d0;
    line-height: 1.3;
  }
  img.mp-icon {
    position: absolute !important;
    bottom: 15px !important;
    right: 15px !important;
    height: clamp(42px, 8vw, 60px) !important;
    width: auto !important;
    margin: 0 !important;
  }

  /* Download Badges */
  .download-badges {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-bottom: 15px;
  }
  .download-badges img {
    filter: contrast(1.6) brightness(0.85); /* Darkens Google Play grey to closer to black */
  }
  
  /* Coming Soon Button */
  .coming-soon {
    display: block;
    margin: 0 auto 25px auto;
    background: url('{{ site.baseurl }}/assets/images/mb-cow/coming-soon_button copy.png') no-repeat center center;
    background-size: 100% 100%;
    padding: clamp(2px, 0.5vw, 4px) clamp(18px, 4vw, 25px);
    font-size: clamp(11px, 2vw, 14px);
    font-weight: 700;
    color: #333;
    text-transform: lowercase;
    text-align: center;
    width: max-content;
  }
  

  @media (max-width: 520px) {
    .banner-wrapper {
      border-radius: 28px;
    }
  }

</style>

<!-- Logo -->
{% include abso-header.html %}

<!-- Main Banner -->
<div class="banner-wrapper">
  <img src="{{ site.baseurl }}/assets/images/mb-cow/mb-cow-base copy.png" alt="Mahabharata Code of War Banner" class="cow-center" style="width: 100%;">
  <div class="banner-overlay">
    <img src="{{ site.baseurl }}/assets/images/mb-cow/logo.png" alt="MAHABHARATA CODE OF WAR" class="main-logo cow-center">
    <p class="banner-desc">A mythological multiplayer game of deception, strategy, and social deduction. Choose your side, uncover hidden identities, and fight for Dharma or Adharma.</p>
    <p class="banner-tagline">Trust no one. Choose your Dharma.</p>
  </div>
</div>

<div class="abso-landing cow-container">
  <!-- Info Card -->
  <div class="info-card mb-30">
    <h2>Mahabharata: Code of War</h2>
    <p>Genre: Social Deduction, Strategy</p>
    <p>Battles: Every Season</p>
    <p>Release Date: TBA</p>
    <p>Developer: ABSOLUTEARTT&reg; / abso.</p>
    <p>Platforms: iOS &amp; Android</p>
    <img src="{{ site.baseurl }}/assets/images/mb-cow/mp-icon copy.png" alt="Multi-player" class="mp-icon">
  </div>

  <!-- Screenshots Header -->
  <img src="{{ site.baseurl }}/assets/images/mb-cow/screenshots-icon copy.png" alt="Screenshots" class="cow-center" style="height: 64px; margin-bottom: 20px;">
  
  <!-- Character Cards -->
  <img src="{{ site.baseurl }}/assets/images/mb-cow/arjuna-screen copy.png" alt="Arjuna" class="img-rounded" style="margin-bottom: 20px;">
  <img src="{{ site.baseurl }}/assets/images/mb-cow/shakuni-screen.png" alt="Shakuni" class="img-rounded" style="margin-bottom: 20px;">
  <img src="{{ site.baseurl }}/assets/images/mb-cow/nala-sscreenshot copy.png" alt="Nala &amp; Damayanti" class="img-rounded" style="margin-bottom: 20px;">
  
  <!-- In Game Screen -->
  <img src="{{ site.baseurl }}/assets/images/mb-cow/in-game-screen copy.png" alt="In Game Screenshots" class="img-rounded" style="margin-bottom: 30px;">
  
  <!-- Download Header -->
  <img src="{{ site.baseurl }}/assets/images/mb-cow/download-icon.png" alt="Download" class="cow-center" style="height: 64px; margin-bottom: 20px;">
  
  <!-- Badges -->
  <div class="download-badges" style="margin-bottom: 20px;">
    <a href="#"><img src="{{ site.baseurl }}/assets/images/mb-cow/Layer 31 copy.png" alt="Google Play and App Store" style="width: 140px;"></a>
  </div>
  <!-- Coming Soon -->
  <div class="coming-soon">coming soon</div>
  
  <!-- Home Button -->
  <a href="{{ site.baseurl }}/" style="display:block; margin: 0 auto 30px auto; text-align: center;">
    <img src="{{ site.baseurl }}/assets/images/mb-cow/home-icon copy.png" alt="Home" class="cow-center" style="height: 64px;">
  </a>
</div>

<!-- Footer Section -->
{% include abso-footer.html %}
