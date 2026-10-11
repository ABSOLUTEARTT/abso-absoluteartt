---
layout: default
title: Contact
permalink: /contact/
hide_theme_chrome: true
abso_landing: true
---

<style>
  html, body.abso-site {
    overflow-x: hidden !important;
  }

  .contact-page {
    width: min(100%, 660px);
    margin: 0 auto;
    box-sizing: border-box;
    padding-top: 20px;
    background: #ffffff;
    font-family: var(--font-family-sans, 'Lato', -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif);
    color: #111111;
    position: relative;
  }

  .contact-text-block {
    padding: 54px 8% 0 8%;
    text-align: left;
    box-sizing: border-box;
  }

  .contact-lead {
    font-size: clamp(13px, 2.4vw, 15px);
    line-height: 1.5;
    margin: 0 0 24px 0;
    color: #111111;
    font-weight: 500;
  }

  .contact-tagline {
    font-size: clamp(13px, 2.4vw, 15px);
    line-height: 1.5;
    margin: 0 0 32px 0;
    color: #111111;
    font-weight: 700;
  }

  .contact-inquiries {
    font-size: clamp(13px, 2.4vw, 15px);
    line-height: 1.6;
    margin: 0 0 20px 0;
    color: #111111;
  }

  .contact-inquiries p {
    margin: 0 0 4px 0;
  }

  .contact-inquiries strong {
    font-weight: 700;
    color: #111111;
  }

  .contact-inquiries a {
    color: #111111;
    text-decoration: none;
    font-weight: 400;
    transition: opacity 0.2s ease;
  }

  .contact-inquiries a:hover {
    opacity: 0.7;
    text-decoration: underline;
  }

  /* Artwork section: shift towards the right edge of screen */
  .contact-artwork-wrap {
    width: 100%;
    margin-top: 10px;
    margin-bottom: 20px;
    display: flex;
    justify-content: flex-end;
    align-items: flex-end;
  }

  .contact-artwork {
    width: 100%;
    height: auto;
    display: block;
  }

  /* Desktop and Tablet: expand wrapper out to the right edge of the viewport */
  @media (min-width: 661px) {
    .contact-artwork-wrap {
      width: calc(100% + (50vw - 50%));
      margin-right: calc(-1 * (50vw - 50%));
      justify-content: flex-end;
    }

    .contact-artwork {
      width: auto;
      max-width: min(100%, 880px);
      max-height: 520px;
      margin-left: auto;
    }
  }

  /* Mobile viewport */
  @media (max-width: 520px) {
    .contact-text-block {
      padding: 42px 6% 0 6%;
    }
    .contact-lead {
      margin-bottom: 18px;
    }
    .contact-tagline {
      margin-bottom: 24px;
    }
    .contact-artwork-wrap {
      width: 100%;
      margin-right: 0;
      justify-content: flex-end;
      overflow: hidden;
    }
    .contact-artwork {
      width: 112%;
      max-width: 112%;
      margin-left: auto;
      margin-right: -4%;
    }
  }

  /* Mobile Switch to Desktop View */
  body.is-desktop-view .contact-artwork-wrap {
    width: 100% !important;
    max-width: 100% !important;
    margin-right: 0 !important;
    margin-left: 0 !important;
    justify-content: flex-end !important;
    overflow: hidden !important;
  }

  body.is-desktop-view .contact-artwork {
    width: 100% !important;
    max-width: 100% !important;
    max-height: none !important;
    margin-right: 0 !important;
  }
</style>

{% include abso-header.html %}

<div class="contact-page">
  <div class="contact-text-block">
    <p class="contact-lead">
      abso. is the games practice of ABSOLUTEARTT&reg;. We make small games, strange ideas, playful characters, and tiny worlds worth getting lost in.
    </p>

    <p class="contact-tagline">
      small games. strange ideas.
    </p>

    <div class="contact-inquiries">
      <p><strong>General Enquiries:</strong> <a href="mailto:games@absoluteartt.com">games@absoluteartt.com</a></p>
      <p><strong>Legal:</strong> <a href="mailto:legal@absoluteartt.com">legal@absoluteartt.com</a></p>
      <p><strong>Privacy:</strong> <a href="mailto:privacy@absoluteartt.com">privacy@absoluteartt.com</a></p>
    </div>
  </div>

  <div class="contact-artwork-wrap">
    <img src="{{ site.baseurl }}/assets/images/abso/contact-artwork.png" alt="abso. artwork" class="contact-artwork">
  </div>

  <!-- Home Button -->
  <div class="home-wrapper" style="justify-content: center; margin: 30px auto 40px auto;">
    <a href="{{ site.baseurl }}/">
      <img src="{{ site.baseurl }}/assets/images/abso/home-icon.png" alt="Home" style="height: 64px;">
    </a>
  </div>
</div>

{% include abso-footer.html %}
