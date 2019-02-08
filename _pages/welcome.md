---
title: "SoftNanoLab"
layout: splash
permalink: /
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/opal.jpg
  actions:
    - label: "Download"
      url: "https://FionaSander.github.io" #"https://github.com/FionaSander/softnanolab/"
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "What we are doing"
intro: 
  - excerpt: 'some more stuff about what we are doing'
feature_row:
  - image_path: /assets/images/0.jpeg #assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/forwebpage.png
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: "https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif"
    image_caption: "Video of the month"
    excerpt: 'the video of the month is showing truely amazing things indeed'
    url: "#test-link"
    btn_label: "More cat videos"
    btn_class: "btn--info"
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}
{% include feature_row %}
{% include feature_row id="feature_row2" type="left" %}


