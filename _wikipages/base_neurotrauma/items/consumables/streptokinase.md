---
layout: contentpage
title: Streptokinase
category: items
subcategory: consumables
permalink: /items/consumables/streptokinase
image: /images/svg/anybodypart.svg
inline_image: //images/base_neurotrauma/items/consumables/streptokinase.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Niche

  - title: Statistics
    sections:
      - items:
          - "Skill Required: None"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 2x)"
        items:
            - "{{MEDICAL}} 40"
            - "{{SLIME_BACTERIA}} (1x)"
            - "{{STABILOZINE}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{STABILOZINE}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 120 marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     A blood thinner. Using Streptokinase will prevent natural {{BLEEDING}} regeneration and increases the chance of getting a {{STROKE}} if the patient has more than 150% {{HYPERTENSION}}.

  - type: effects
    header: "Effects:"
    order: 2
    text: |

     - Fully treats {{HEART_ATTACK}} and {{HEMOTRANSFUSION_SHOCK}}

---