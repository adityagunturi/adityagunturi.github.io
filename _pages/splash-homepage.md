---
title: "Home Page"
layout: splash
permalink: /
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/unsplash-image-1.jpg
  actions:
    - label: "About Me"
      url: "about/"
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "Bacon ipsum dolor sit amet salami ham hock ham, hamburger corned beef short ribs kielbasa biltong t-bone drumstick tri-tip tail sirloin pork chop."
intro: 
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'
feature_row:
  - image_path: assets/images/home-portfolio-image-1-th.jpg
    alt: "portfolio image 1"
    title: ""
    excerpt: ""
  - image_path: /assets/images/home-portfolio-image-2-th.jpg
    image_caption: ""
    alt: "portfolio image 2"
    title: ""
    excerpt: "Check out some of my work here!"
    url: "portfolio/"
    btn_label: "My Portfolio"
    btn_class: "btn--primary"
  - image_path: /assets/images/home-portfolio-image-3-th.jpg
    title: ""
    excerpt: ""
feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Current Projects"
    excerpt: 'I try to limit my resume to completed work, but I have some other projects in the works as well.'
    url: "#test-link"
    btn_label: "Check them out here"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Just for Fun"
    excerpt: 'A taste of what I like to do in my free time. Everyone needs hobbies!"
    url: "#test-link"
    btn_label: "Check it Out"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Get in Tough"
    excerpt: 'I try to keep my GitHub updated with my code examples, but there are some things I choose not to post for various reasons. These include some class projects, as well as more detailed fits on data that is not mine to disclose. If you are interested in learning more about me, I would love to set up a meeting!'
    url: "contact/"
    btn_label: "Get in Touch"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}
