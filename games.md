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

    <figure class="abso-card abso-card--narrow" style="margin-bottom: 40px;">
      <a href="{{ site.baseurl }}/duet">
        <img src="{{ '/assets/images/abso/dual-duet.webp' | relative_url }}"
             srcset="{{ '/assets/images/abso/dual-duet-320w.webp' | relative_url }} 320w,
                     {{ '/assets/images/abso/dual-duet-600w.webp' | relative_url }} 600w,
                     {{ '/assets/images/abso/dual-duet.webp' | relative_url }} 1170w"
             sizes="(max-width: 660px) calc(100vw - 36px), 585px"
             width="1170" height="473"
             loading="lazy" decoding="async" alt="Duet">
      </a>
    </figure>
  </section>

  <!-- Home Button -->
  <div class="home-wrapper" style="justify-content: center; margin: 30px auto 40px auto;">
    <a href="{{ site.baseurl }}/">
      <img src="{{ site.baseurl }}/assets/images/abso/home-icon.webp" alt="Home" loading="lazy" decoding="async" width="160" height="81" style="height: 64px; width: auto;">
    </a>
  </div>
</div>

{% include abso-footer.html %}
