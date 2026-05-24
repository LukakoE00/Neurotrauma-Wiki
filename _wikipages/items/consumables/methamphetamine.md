---
layout: contentpage
title: Methamphetamine
category: items
subcategory: consumables
permalink: /items/consumables/methamphetamine
image: /images/svg/anybodypart.svg
inline_image: /images/items/consumables/methamphetamine.png

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
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 30"
            - "{{PHOSPHORUS}} (1x)"
            - "{{CHLORINE}} (2x)"
            - "{{CARBON}} (2x)"

      - header: "Deconstructor Yield"
        items:
            - "{{PHOSPHORUS}} (1x)"
            - "{{CHLORINE}} (1x)"
            - "{{CARBON}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 50 marks"
          - "Buyable at Outposts: Colony, Research"
          - "Buyable at Merchant: Military"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     A stimulant.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - \+70% {{HYPERACTIVITY}}
     - \+15% {{VANILLA_ORGAN_DAMAGE}}
     - \+15% {{NEUROTRAUMA}}
     - \+15% {{CHEMICAL_ADDICTION}}
     - \+30% {{PSYCHOSIS}}
     - \-22.5% {{STUN}}
     - \-90% {{CHEMICAL_WITHDRAWAL}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \+50% {{HYPERACTIVITY}}
     - \+30% {{VANILLA_ORGAN_DAMAGE}}
     - \+30% {{NEUROTRAUMA}}
     - \+30% {{CHEMICAL_ADDICTION}}
     - \+45% {{PSYCHOSIS}}
     - \-22.5% {{STUN}}
     - \-90% {{CHEMICAL_WITHDRAWAL}}

     {{HYPERACTIVITY}} occurs instantly, while the other effects occur over 30 seconds.

---