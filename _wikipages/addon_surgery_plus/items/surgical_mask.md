---
layout: contentpage
title: Surgical Mask
addon: surgery_plus
subcategory: items
permalink: /items/surgery_plus/surgical_mask
# image: /images/svg/anybodypart.svg
inline_image: /images/addon_surgery_plus/items/surgical_mask.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Surgery Plus Expansion

  - title: Statistics
    sections:
      - items:
          - "Maximum inventory stack: 1"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements"
        items:
            - "{{MEDICAL}} 20"
            - "{{PLASTIC}} (1x)"
            
      - header: "Deconstructor Yield"
        items:
            - "{{PLASTIC}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 50 Marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     The Surgical Mask is a wearable item that increases sterility when worn, decreasing risk of {{SURGICAL_INFECTION}}.

     - \-10% {{OPEN_WOUNDS}}
     - \-20% {{BLEEDING}}
---