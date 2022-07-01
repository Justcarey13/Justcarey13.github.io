---
heading: "Hi! I'm Carey."
layout: splash
date: 2022.1.22
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/my-awesome-post-teaser.jpg
  caption: "Photo credit: [**Carey Yang**](https://justcarey13.github.io/photography)"

excerpt: "Hey! I'm Carey - welcome to my personal website :D"

intro: 
  - excerpt: '`Good morning! Oh, in case I don’t see you, good afternoon, good evening and good night.`'

feature_row:
  - image_path: assets/images/my-awesome-post-teaser.jpg
    alt: "placeholder image 1"
    title: "More"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/my-awesome-post-teaser.jpg
    image_caption: "Photo courtesy of [**Carey Yang**](https://justcarey13.github.io/photography)"
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "https://github.com/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/my-awesome-post-teaser.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: /assets/images/my-awesome-post-teaser.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "https://github.com/"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/my-awesome-post-teaser.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "https://github.com/"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/my-awesome-post-teaser.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "https://github.com/"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}
