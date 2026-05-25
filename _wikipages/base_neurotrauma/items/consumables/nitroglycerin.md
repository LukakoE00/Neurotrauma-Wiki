---
layout: contentpage
title: Nitroglycerin
category: items
subcategory: consumables
permalink: /items/consumables/nitroglycerin
image: /images/svg/anybodypart.svg
inline_image: //images/base_neurotrauma/items/consumables/nitroglycerin.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Niche

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 35"
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
          - "Base Price: 150 marks"
          - "Buyable at Merchant: Military, Armory, Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     A jar containing a very volatile vasodilator, liable to explode on impact or exposure to heat. While this drug is active, {{FIBRILLATION}} caused by {{HYPOTENSION}} will be reduced.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - \-45% Blood Pressure

     Effects last for 400 seconds.

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \-45% Blood Pressure

     Effects last for 200 seconds.
---