---
layout: contentpage
title: Surgical Drapes
addon: surgery_plus
subcategory: items
permalink: /items/surgery_plus/surgical_drapes
# image: /images/svg/anybodypart.svg
inline_image: /images/addon_surgery_plus/items/surgical_drapes.png

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
            - "{{MEDICAL}} 15"
            - "{{PLASTIC}} (1x)"
            - "{{RUBBER}} (1x)"
            
      - header: "Deconstructor Yield"
        items:
            - "{{PLASTIC}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 100 Marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Surgical Drapes are a clothing item used to increase the wearer's sterility and thus decreasing the risk of {{SURGICAL_INFECTION}}.

     - \+100 Base sterility
     - \-50% {{TRAUMATIC_SHOCK}} gain while worn
---