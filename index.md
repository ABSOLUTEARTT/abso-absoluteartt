---
layout: default
title: "abso. — small games. strange ideas."
description: small games. strange ideas.
permalink: /
hide_theme_chrome: true
abso_landing: true
---

{% include abso-header.html %}

<section id="games" class="abso-stack" aria-label="Games">
  <figure class="abso-card abso-card--full abso-card--hero" style="margin-bottom: 20px;">
    <a href="{{ site.baseurl }}/mb-cow">
      <img src="{{ '/assets/images/abso/mahabharata-code-of-war-640w.webp' | relative_url }}"
           srcset="{{ '/assets/images/abso/mahabharata-code-of-war-360w.webp' | relative_url }} 360w,
                   {{ '/assets/images/abso/mahabharata-code-of-war-640w.webp' | relative_url }} 640w,
                   {{ '/assets/images/abso/mahabharata-code-of-war-960w.webp' | relative_url }} 960w,
                   {{ '/assets/images/abso/mahabharata-code-of-war.webp' | relative_url }} 1324w"
           sizes="(max-width: 660px) 100vw, 660px"
           width="1324" height="2353"
           fetchpriority="high" decoding="async" alt="Mahabharata Code of War">
    </a>
  </figure>
</section>

<div class="abso-landing" aria-label="abso. landing page">
  <section class="abso-stack" aria-label="Games">

    <figure class="abso-card abso-card--narrow">
      <a href="{{ site.baseurl }}/samosa-catcher">
        <img src="{{ '/assets/images/abso/samosa-catcher.webp' | relative_url }}"
             srcset="{{ '/assets/images/abso/samosa-catcher-320w.webp' | relative_url }} 320w,
                     {{ '/assets/images/abso/samosa-catcher-600w.webp' | relative_url }} 600w,
                     {{ '/assets/images/abso/samosa-catcher.webp' | relative_url }} 1024w"
             sizes="(max-width: 660px) calc(100vw - 36px), 585px"
             width="1024" height="773"
             loading="lazy" decoding="async" alt="Samosa Catcher" style="width: 100%; border-radius: 42px; display: block;">
      </a>
    </figure>

    <figure class="abso-card abso-card--narrow">
      <a href="{{ site.baseurl }}/run-little-one">
        <img src="{{ '/assets/images/abso/run-little-one.webp' | relative_url }}"
             srcset="{{ '/assets/images/abso/run-little-one-320w.webp' | relative_url }} 320w,
                     {{ '/assets/images/abso/run-little-one-600w.webp' | relative_url }} 600w,
                     {{ '/assets/images/abso/run-little-one.webp' | relative_url }} 1172w"
             sizes="(max-width: 660px) calc(100vw - 36px), 585px"
             width="1172" height="974"
             loading="lazy" decoding="async" alt="Run, Little One.">
      </a>
    </figure>

    <figure class="abso-card abso-card--narrow">
      <a href="{{ site.baseurl }}/twosome">
        <img src="{{ '/assets/images/abso/twosome.webp' | relative_url }}"
             srcset="{{ '/assets/images/abso/twosome-320w.webp' | relative_url }} 320w,
                     {{ '/assets/images/abso/twosome-600w.webp' | relative_url }} 600w,
                     {{ '/assets/images/abso/twosome.webp' | relative_url }} 1170w"
             sizes="(max-width: 660px) calc(100vw - 36px), 585px"
             width="1170" height="473"
             loading="lazy" decoding="async" alt="Twosome">
      </a>
    </figure>

    <figure class="abso-card abso-card--narrow">
      <a href="{{ site.baseurl }}/duet">
        <img src="{{ '/assets/images/abso/dual-duet.webp' | relative_url }}"
             srcset="{{ '/assets/images/abso/dual-duet-320w.webp' | relative_url }} 320w,
                     {{ '/assets/images/abso/dual-duet-600w.webp' | relative_url }} 600w,
                     {{ '/assets/images/abso/dual-duet.webp' | relative_url }} 1170w"
             sizes="(max-width: 660px) calc(100vw - 36px), 585px"
             width="1170" height="473"
             loading="lazy" decoding="async" alt="Dual">
      </a>
    </figure>
  </section>

  <section class="abso-panel abso-panel--about abso-card--narrow" aria-label="About abso.">
    <a href="{{ site.baseurl }}/about" style="text-decoration: none; color: inherit; display: block;">
      <img src="{{ '/assets/images/abso/about-banner.webp' | relative_url }}" width="1170" height="414" loading="lazy" decoding="async" alt="">
      <div class="abso-panel__copy abso-panel__copy--about">
        <h1>small games. strange ideas.</h1>
        <p>We make little games.</p>
        <p>Some are easy.<br>Some are weird.<br>Some probably shouldn't work.<br>We make them anyway.</p>
      </div>
    </a>
  </section>

  <section class="abso-panel abso-panel--dot abso-card--narrow" aria-label="The Dot">
    <a href="{{ site.baseurl }}/the-dot" style="text-decoration: none; color: inherit; display: block;">
      <img src="{{ '/assets/images/abso/the-dot-banner.webp' | relative_url }}" width="1170" height="414" loading="lazy" decoding="async" alt="">
      <div class="abso-panel__copy abso-panel__copy--dot">
        <h2>The Dot.</h2>
        <p>One little character.<br>Many lives.<br>Sometimes helpful.<br>Sometimes annoying.<br>Sometimes completely unnecessary.<br><span class="abso-highlight">You'll find him.</span></p>
      </div>
    </a>
  </section>

  <section class="abso-contact" aria-label="Contact">
    <h2>Contact</h2>
    <p>Made something strange?</p>
    <p><a href="mailto:games@absoluteartt.com">games@absoluteartt.com</a></p>
    <p>(for games, collaborations, publishing and other suspiciously good ideas)</p>
  </section>
</div>

{% include abso-footer.html %}








