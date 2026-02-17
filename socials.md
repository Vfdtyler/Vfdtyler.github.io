---
layout: page
title: Socials
permalink: /socials/
minima:
  social_links:
    - title: Instagram
      icon: instagram
      url: https://www.instagram.com/vfdtyler/
    - title: Letterboxd
      icon: letterboxd
      url: https://letterboxd.com/Vfdtyler/
    - title: Bluesky
      icon: bluesky
      url: https://bsky.app/profile/tylerevans.xyz
    - title: TikTok
      icon: tiktok
      url: https://www.tiktok.com/@vfdtyler
    - title: Threads
      icon: threads
      url: https://www.threads.com/@vfdtyler
    - title: GitHub
      icon: github
      url: https://github.com/Vfdtyler
    - title: Tumblr
      icon: tumblr
      url: https://vfdtyler.tumblr.com/
    - title: Mastodon
      icon: mastodon
      url: https://mastodon.social/@Vfdtyler
    - title: Twitch
      icon: twitch
      url: https://www.twitch.tv/vfdtyler
    - title: Twitter
      icon: twitter
      url: http://twitter.com/Vfdtyler
---

You can find me on social media at the links below, listed roughly in order of how often I use them.

<ul class="social-links">
  {%- for link in page.minima.social_links -%}
    <li>
      <a href="{{ link.url }}">
        <i class="fa-{{ link.style | default: 'brands' }} fa-{{ link.icon }}"></i> {{ link.title }}
      </a>
    </li>
  {%- endfor -%}
</ul>
