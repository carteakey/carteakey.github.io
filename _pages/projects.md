---
layout: single
classes: wide
title: "Projects"
redirect_to:  https://www.carteakey.dev/projects/
permalink: /projects/

feature_row1:
  - image_path: assets/images/portfolio/vizima.png
    title: "Vizima"
    excerpt: "Website for a hospitality company using Nextjs, Chakra UI & Typescript."
    url: "https://www.vizima.in/"
    btn_label: "Website"
    btn_class: "btn--primary"
    tags:
      - react
      - nextjs
      - chakra

feature_row2:
  - image_path: assets/images/portfolio/recomovi.png
    title: "Recomovi"
    excerpt: "Content-based movie recommendation App & IMDb dataset generator written in Python."
    url: "https://github.com/carteakey/recomovi"
    btn_label: "GitHub"
    btn_class: "btn--primary"
    tags:
      - Web Scraping
      - recommendation system

feature_row3:
  - image_path: assets/images//portfolio/microhms.png
    title: "MicroHMS"
    excerpt: "Hotel Management System for small hotel owners to track bookings and generate professional looking invoices."
    btn_label: "GitHub"
    url: "https://github.com/carteakey/microhms"
    btn_class: "btn--primary"
    tags:
      - flask
      - postgres
      - bootstrap

feature_row4:
  - image_path: assets/images/portfolio/carteakey.png
    title: "carteakey.github.io"
    excerpt: "Blog and Portfolio Website. Built using Jekyll and Minimal Mistakes"
    url: "https://github.com/carteakey/carteakey.github.io"
    btn_label: "GitHub"
    btn_class: "btn--primary"
    tags:
      - blog
      - jekyll
---

{% include feature_row id="feature_row1" type="left" %}
{% include feature_row id="feature_row2" type="left" %}
{% include feature_row id="feature_row3" type="left" %}
{% include feature_row id="feature_row4" type="left" %}
