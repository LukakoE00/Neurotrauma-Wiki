---
layout: contentpage
title: Alien Blood
category: items
subcategory: consumables
permalink: /items/consumables/alien_blood
image: /images/svg/anybodypart.svg
inline_image: //images/base_neurotrauma/items/consumables/alien_blood.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Niche
          - First Aid

  - title: Statistics
    sections:
      - items:
          - "Skill Required: Medical 55"
          - "Maximum inventory stack: 8"

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
          - "Base Price: 100 marks"
          - "Buyable at Outposts: Research"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Using Alien Blood in place of regular blood is extremely dangerous and should only be used in dire situations.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |
     - \-20% {{BLOOD_LOSS}}
     - \+60% {{PSYCHOSIS}}
     - \+100% {{HEMOTRANSFUSION_SHOCK}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |
     - \-20% {{BLOOD_LOSS}}
     - \+60% {{PSYCHOSIS}}
     - \+100% {{HEMOTRANSFUSION_SHOCK}}
---