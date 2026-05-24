---
layout: contentpage
title: Surgeon Clothes
addon: surgery_plus
subcategory: items
permalink: /items/surgery_plus/surgeon_clothes
# image: /images/svg/anybodypart.svg
inline_image: /images/addon_surgery_plus/items/surgeon_clothes.png

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
            - "Cannot be fabricated."
            
      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 150 Marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     The Surgeon Clothes are a wearable item that increases sterility when worn, decreasing risk of {{SURGICAL_INFECTION}}.

     - \-10% {{BLUNT_FORCE_TRAUMA}}
     - \-10% {{LACERATIONS}}
     - \-10% {{BITE_WOUNDS}}
---