---
# An instance of the Contact widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 60

title: Como contactarnos?
subtitle: "Puede enviarnos un mensaje corto, o escribirnos al correo electrónico. También puede llamarnos por teléfono, seguirnos en **Twitter** o visitar nuestras oficinas."
content:
  # Automatically link email and phone or display as text?
  autolink: true
  
  # Email form provider
  form:
    provider: formspree
    formspree:
      id: xoqywdya
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false
  
design:
columns: '2'
---
