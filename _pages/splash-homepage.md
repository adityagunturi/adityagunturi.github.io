---
title: "Aditya Gunturi"
layout: splash
permalink: /
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/home-splash.jpg
  actions:
    - label: "About Me"
      url: "about/"
  caption: ""
excerpt: "Welcome to my site! Browse around to get a snapshot of what I do."
intro: 
  - excerpt: 'Third-year undergraduate with a strong focus in dynamical systems, control theory, and vehicle dynamics. Experienced in simulation, data-driven modeling, and hands-on integration through Formula SAE.'
feature_row:
  - image_path: assets/images/home-portfolio-image-1-th.jpg
    alt: ""
    title: ""
    excerpt: ""
  - image_path: /assets/images/home-portfolio-image-2-th.jpg
    image_caption: ""
    alt: ""
    title: ""
    excerpt: ""
    url: "portfolio/"
    btn_label: "My Portfolio"
    btn_class: "btn--primary"
  - image_path: 
    title: "Past Projects"
    excerpt: "Check out some of my work here!"
feature_row2:
  - image_path: /assets/images/home-current-work.jpg
    alt: "placeholder image 2"
    title: "Current Projects"
    excerpt: 'I try to limit my resume to completed work, but I have some other projects in the works as well.'
    url: "current/"
    btn_label: ""
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/home-hobby.jpg
    alt: "placeholder image 2"
    title: "Just for Fun"
    excerpt: "A taste of what I like to do in my free time. Everyone needs hobbies!"
    url: "good-times/"
    btn_label: "Check it Out"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/home-sunset.jpg
    alt: ""
    title: "Get in Touch"
    excerpt: 'I try to keep my GitHub updated with my code examples, but there are some things I choose not to post for various reasons. These include some class projects, as well as more detailed work on data that is not mine to disclose. If you are wanting to know more, I would love to set up a meeting!'
    url: "contact/"
    btn_label: "Get in Touch"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}
