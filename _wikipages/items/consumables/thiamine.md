---
layout: contentpage
title: Thiamine
category: items
subcategory: consumables
permalink: /items/consumables/thiamine
image: /images/svg/anybodypart.svg
inline_image: /images/items/consumables/thiamine.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - First Aid
          - Important

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 10"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 3x)"
        items:
            - "{{MEDICAL}} 40"
            - "{{CARBON}} (2x)"
            - "{{SULPHURIC_ACID}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 70 marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     A container of vitamin B1 pills used to assist in organ healing. Not capable of reviving dead organs (i.e. 100% organ damage).

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - \-8% {{LUNG_DAMAGE}}
     - \-8% {{HEART_DAMAGE}}
     - \-8% {{KIDNEY_DAMAGE}}
     - \-8% {{LIVER_DAMAGE}}
     - \-8% {{VANILLA_ORGAN_DAMAGE}}

     Grants +50% Thiamine, which treats the above organ damage over 200 seconds.

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \-4.8% {{LUNG_DAMAGE}}
     - \-4.8% {{HEART_DAMAGE}}
     - \-4.8% {{KIDNEY_DAMAGE}}
     - \-4.8% {{LIVER_DAMAGE}}
     - \-4.8% {{VANILLA_ORGAN_DAMAGE}}

     Grants +30% Thiamine, which treats the above organ damage over 120 seconds.

---