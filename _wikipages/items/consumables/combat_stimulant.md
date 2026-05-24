---
layout: contentpage
title: Combat Stimulant
category: items
subcategory: consumables
permalink: /items/consumables/combat_stimulant
image: /images/svg/anybodypart.svg
inline_image: /images/items/consumables/combat_stimulant.png

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
          - "Skill Required: {{MEDICAL}} 35"
          - "Maximum inventory stack: 1"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "Super Soldiers Talent"
            - "{{ADRENALINE}} (2x)"
            - "{{MORPHINE}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{ADRENALINE}} (1x)"
            - "{{OPIUM}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 340 marks"
          - Cannot be bought

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Combat Stimulant is a stimulant that also doubles as a first aid item. It has the same effects as vanilla, with additional afflictions treated.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     Gain 20% {{CHEMICAL_ADDICTION}} and 75% Combat Stimulant, which between 11% to 100% strength:

     Treats:

     - {{BURNS}} by 2% per second
     - {{BLOOD_LOSS}} by 2% per second
     - {{BLEEDING}} by 2% per second
     - {{INTERNAL_BLEEDING}} by 2% per second
     - {{INTERNAL_WOUNDS}}, {{OPEN_WOUNDS}}, {{SUTURES}}, and {{CONCUSSION}},by 2% per second
     - {{CHEMICAL_WITHDRAWAL}} by 2% per second

     Grants 45% to 50% Stun resistance.

     Between 1% to 10% of Combat Stimulant, the treatment strength is halved and Stun resistance is 0% to 45%.

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     Gain 40% {{CHEMICAL_ADDICTION}} and 75% Combat Stimulant.
---