---
layout: single
title: "Projects"
permalink: /projects/

feature_row1:
  - image_path: assets/images/portfolio/vizima.png
    title: "Vizima"
    excerpt: "Company website for a hospitality company using Nextjs, Chakra UI & Typescript."
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
    excerpt: "Content-based movie recommendation system & IMDb dataset generator written in Python."
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
---

---
{% include feature_row id="feature_row1" type="left" %}
{% include feature_row id="feature_row2" type="left" %}
{% include feature_row id="feature_row3" type="left" %}
