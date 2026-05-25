---
layout: contentpage
title: Deusizine
category: items
subcategory: consumables
permalink: /items/consumables/deusizine
image: /images/svg/anybodypart.svg
inline_image: //images/base_neurotrauma/items/consumables/deusizine.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - First Aid
          - Niche

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 72"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 70"
            - "{{ANTIBIOTIC_GLUE}} (1x)"
            - "{{FENTANYL}} (1x)"
            - "{{LIQUID_OXYGENITE}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{ANTIBIOTIC_GLUE}} (1x)"
            - "{{OPIUM}} (1x)"
            - "{{LIQUID_OXYGENITE}} (1x)"
  - title: Store
    sections:
      - items:
          - "Minimum Difficulty: 50%"
          - "Base Price: 500 marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     A special drug, treating a variety of life-threatening afflictions over 20 seconds and providing a moderate Vigor buff.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |
     - \-20% {{INTERNAL_WOUNDS}}
     - \-50% {{BLOOD_LOSS}}
     - \-50% {{BLEEDING}}
     - \-100% {{HYPOXEMIA}}
     - \-20% {{VANILLA_ORGAN_DAMAGE}}
     - \-6% {{STUN}}
     - \+4% {{BURNS}}
     - \+40% Blood Pressure
     - \+200% {{VIGOR}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |
     - \-10% {{INTERNAL_WOUNDS}}
     - \-25% {{BLOOD_LOSS}}
     - \-10% {{BLEEDING}}
     - \-40% {{HYPOXEMIA}}
     - \-10% {{VANILLA_ORGAN_DAMAGE}}
     - \+20% {{BURNS}}
     - \+20% Blood Pressure
     - \+200% {{VIGOR}}

---