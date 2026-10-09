---
layout: default
title: abso.
description: small games. strange ideas.
permalink: /
hide_theme_chrome: true
abso_landing: true
---

{% include abso-header.html %}

<section id="games" class="abso-stack" aria-label="Games">
  <figure class="abso-card abso-card--full abso-card--hero" style="margin-bottom: 20px;">
    <a href="{{ site.baseurl }}/mb-cow">
      <img src="{{ '/assets/images/abso/mahabharata-code-of-war.png' | relative_url }}" alt="Mahabharata Code of War">
    </a>
  </figure>
</section>

<div class="abso-landing" aria-label="abso. landing page">
  <section class="abso-stack" aria-label="Games">

    <figure class="abso-card abso-card--narrow">
      <a href="{{ site.baseurl }}/samosa-catcher">
        <img src="{{ '/assets/images/abso/samosa-catcher.png' | relative_url }}" alt="Samosa Catcher">
      </a>
    </figure>

    <figure class="abso-card abso-card--narrow">
      <a href="{{ site.baseurl }}/run-little-one">
        <img src="{{ '/assets/images/abso/run-little-one.png' | relative_url }}" alt="Run, Little One.">
      </a>
    </figure>

    <figure class="abso-card abso-card--narrow">
      <a href="{{ site.baseurl }}/twosome">
        <img src="{{ '/assets/images/abso/twosome.png' | relative_url }}" alt="Twosome">
      </a>
    </figure>

    <figure class="abso-card abso-card--narrow">
      <a href="{{ site.baseurl }}/duet">
        <img src="{{ '/assets/images/abso/dual-duet.png' | relative_url }}" alt="Dual">
      </a>
    </figure>
  </section>

  <section class="abso-panel abso-panel--about abso-card--narrow" aria-label="About abso.">
    <a href="{{ site.baseurl }}/about" style="text-decoration: none; color: inherit; display: block;">
      <img src="{{ '/assets/images/abso/about-banner.png' | relative_url }}" alt="">
      <div class="abso-panel__copy abso-panel__copy--about">
        <h1>small games. strange ideas.</h1>
        <p>We make little games.</p>
        <p>Some are easy.<br>Some are weird.<br>Some probably shouldn't work.<br>We make them anyway.</p>
      </div>
    </a>
  </section>

  <section class="abso-panel abso-panel--dot" aria-label="The Dot">
    <a href="{{ site.baseurl }}/the-dot" style="text-decoration: none; color: inherit; display: block;">
      <img src="{{ '/assets/images/abso/the-dot-banner.png' | relative_url }}" alt="">
      <div class="abso-panel__copy abso-panel__copy--dot">
        <h2>The Dot.</h2>
        <p>One little character.<br>Many lives.<br>Sometimes helpful.<br>Sometimes annoying.<br>Sometimes completely unnecessary.<br><span class="abso-highlight">You'll find him.</span></p>
      </div>
    </a>
  </section>

  <section class="abso-contact" aria-label="Contact">
    <h2>Contact</h2>
    <p>Made something strange?</p>
    <p><a href="mailto:abso@absoluteartt.com">abso@absoluteartt.com</a></p>
    <p>(for games, collaborations, publishing and other suspiciously good ideas)</p>
  </section>
</div>

{% include abso-footer.html %}
