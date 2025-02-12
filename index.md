---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
# This is the front-matter. Below the hyphens are the content.
layout: splash
author_profile: false

header:
  overlay_color: "#000"
  overlay_filter: "0.45"
  overlay_image: assets/images/background.jpg
  actions:
    - label: "About"
      url: "/about/"
  caption: "[**SUndwich**](https://web.archive.org/web/20220301205859/http://acoustics.sabanciuniv.edu/~abozkurt/)"
excerpt: "SUndwich is an open-source FPGA daughterboard designed for use in introductory digital design courses."
intro:
  - excerpt: 'SUndwich provides the basic input/output accessories to the Tang Nano 9K FPGA board. The design is open-source and allows for anyone to modify it.'
feature_row:
  - title: "Cross Platform"
    excerpt: "Students can run the open-source toolchain on Windows, MacOS, or Linux."
  - title: "Open Source"
    excerpt: "SUndwich is licensed under MIT."
  - title: "All The Basics Included"
    excerpt: "SUndwich includes push-buttons, sliders, LEDs and a four-digit seven segment display."
---

<style>
  .splash {
    max-width: 1060px;
    margin: 0 auto;
  }

  .page__title {
    display: none;
  }

  .intro_text .archive__item-body {
      max-width: 700px;
      width: auto;
  }
</style>

<div class="intro_text">
  {% include feature_row id="intro" type="center" %}
</div>

{% include feature_row %}