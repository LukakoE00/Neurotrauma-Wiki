---
layout: contentpage
title: Hyperzine
category: items
subcategory: consumables
permalink: /items/consumables/hyperzine
image: /images/svg/anybodypart.svg
inline_image: //images/base_neurotrauma/items/consumables/hyperzine.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Niche

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 50"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 40"
            - "{{METHAMPHETAMINE}} (1x)"
            - "{{ANABOLIC_STEROIDS}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{ANABOLIC_STEROIDS}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 450 marks"
          - "Buyable at Merchant: Research, Military"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     A powerful stimulant.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - \-12% {{INTERNAL_DAMAGE}}
     - \+18% {{CHEMICAL_ADDICTION}}
     - \+18% {{NEUROTRAUMA}}
     - \+15% {{PSYCHOSIS}}
     - \+400% {{HYPERACTIVITY}}
     - \+400% {{VIGOR}}
     - \-54% {{STUN}}
     - \-90% {{CHEMICAL_WITHDRAWAL}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \-6% {{INTERNAL_DAMAGE}}
     - \+36% {{CHEMICAL_ADDICTION}}
     - \+36% {{NEUROTRAUMA}}
     - \+30% {{PSYCHOSIS}}
     - \+400% {{HYPERACTIVITY}}
     - \+400% {{VIGOR}}
     - \-27% {{STUN}}
     - \-90% {{CHEMICAL_WITHDRAWAL}}
     <br><br>
     {{HYPERACTIVITY}} and Vigor are applied instantly, while the other effects are applied over a 60 second duration.

---