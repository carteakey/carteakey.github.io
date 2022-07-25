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
    url: "https://github.com/kartikey-chauhan/recomovi"
    btn_label: "GitHub"
    btn_class: "btn--primary"
    tags:
      - Web Scraping
      - recommendation system

feature_row3:
  - image_path: assets/images//portfolio/er_diagram.png
    title: "Flask Hotel Billing"
    excerpt: "Web application for hotel billing and printing invoices using Flask and PostgreSQL."
    btn_label: "GitHub"
    url: "https://github.com/kartikey-chauhan/flask-hotel-billing"
    btn_class: "btn--primary"
    tags:
      - flask
      - postgres
      - bootstrap
---

## Projects

{% include feature_row id="feature_row1" type="left" %}
{% include feature_row id="feature_row2" type="left" %}
{% include feature_row id="feature_row3" type="left" %}
