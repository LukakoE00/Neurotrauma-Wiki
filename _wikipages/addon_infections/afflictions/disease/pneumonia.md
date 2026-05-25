---
layout: contentpage
title: Pneumonia
addon: infections
subcategory: diseases
permalink: /afflictions/nt_infections/pneumonia/
inline_image: /images/base_neurotrauma/afflictions/lungs/respiratory_arrest.png

infobox:
  - title: Labels
    sections:
      - items:
          - Affliction
          - Infections Expansion

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Inflammation of the lung caused by various diseases. Causes -1 vitality for every 2%. Pneumonia may have an increased chance of appearing depending on infection level and immunity level.

  - type: caused_by
    header: "Caused By:"
    order: 2
    text: |
     - Blood infection level (>0%)
     - Viral infection level (>0%)

  - type: effects
    header: "Effects:"
    order: 3
    text: |
     - {{COUGH}} (>5%)
     - {{SHORTNESS_OF_BREATH}} (>10%)
     - {{CHEST_PAIN}} (>40%)
     - {{RESPIRATORY_ARREST}} (>80%)

  - type: treatments
    header: "Treatments:"
    order: 4
    text: |
     - Treat the underlying bacterial infection
     - Treat the underlying viral infection
---