---
title: "9 Lives to Valhalla"
layout: splash
page_css:
  - /assets/css/ninelives.css
permalink: /9livestovalhalla/
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/ninelives/banner.png
  text_color: white
  text_font: "special elite"
  actions:
    - label: "Kickstarting Now"
      url: "/terms/"
    - label: "Preview Here"
      url: https://gemroomgames.itch.io
excerpt: "The Age of Man is Over! Now dawns the Age of Beasts!"
intro:
  - excerpt: 'In the frenetic 9 Lives to Valhalla you are a death metal viking cat earning your place in the drinking halls of Valhalla by casting a wake of blood and carnage upon the blighted earth. Guided personally by DEATH, your merry band will leave a wake of ruin ending only at the hands of a truly worthy foe. Nine lives to stalk the earth! Nine times to die with sword in paw! Nine Lives to Valhalla!'
feature_row:
  - image_path: assets/ninelives/gallery-image-1-th.png
    image_caption: "caption if we want"
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/ninelives/gallery-image-2-th.png
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--danger"
  - image_path: /assets/ninelives/gallery-image-3-th.png
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: /assets/ninelives/left-image-1-th.png
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/ninelives/right-image-1-th.png
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/ninelives/center-image-1-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}
