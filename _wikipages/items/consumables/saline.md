---
layout: contentpage
title: Saline
category: items
subcategory: consumables
permalink: /items/consumables/saline
image: /images/svg/anybodypart.svg
inline_image: /images/items/consumables/saline.png

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
      - header: "Medical Fabricator Requirements (Output: 2x)"
        items:
            - "{{MEDICAL}} 5"
            - "{{SODIUM}} (1x)"
            - "{{CHLORINE}} (2x)"

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 50 marks"
          - "Buyable at Outposts: All"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     An isotonic solution used to replace lost fluids, or to treat {{ALKALOSIS}}.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - \+30% Blood Pressure
     - \+0.07% {{ACIDOSIS}} per second

     Effects last for 200 seconds.

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \+30% Blood Pressure
     - \+0.07% {{ACIDOSIS}} per second

     Effects last for 120 seconds.

---