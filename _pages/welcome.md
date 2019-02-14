---
title: "SoftNanoLab"
layout: splash
classes: wide
permalink: /
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/opal.jpg
  caption: "Photo credit: [**Fiona Sander**](https://fionasander.github.io/softnanolab/fiona/)"
excerpt: "What we are doing"
intro: 
  - excerpt: 'some more stuff about what we are doing'
gallery:
  - image_path: /assets/images/clay_particles.jpg 
    width: "450" 
    height: "450"
    alt: "placeholder image 1"
    excerpt: "This is very interesting."
  - image_path: /assets/images/forwebpage.png
    image_caption: "Image credit: Kaiye Xie"
    alt: "placeholder image 2"
    excerpt: "This is really cool."
  - image_path: /assets/images/chitinrods.jpeg
    excerpt: "This is also quite cool."
  - image_path: /assets/images/clay_particles.jpg 
    alt: "placeholder image 1"
    excerpt: "This is very interesting."
feature_row2:
  - image_path: "https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif"
    image_caption: "Video of the month"
    excerpt: 'the video of the month is showing truely amazing things indeed'
    url: "#test-link"
    btn_label: "More cat videos"
    btn_class: "btn--info"
---

#{% include feature_row id="intro" type="center" %}

{% include gallery id="intro" %}
{% include gallery id="gallery" %}
{% include gallery id="feature_row2" %}

#{% include feature_row id="feature_row2" type="left" %}


