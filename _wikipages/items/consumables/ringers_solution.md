---
layout: contentpage
title: Ringer's Solution
category: items
subcategory: consumables
permalink: /items/consumables/ringers_solution
image: /images/svg/anybodypart.svg
inline_image: /images/items/consumables/ringers_solution.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Important

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 20"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 25"
            - "{{SALINE}} (1x)"
            - "{{POTASSIUM}} (1x)"
            - "{{CARBON}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{SALINE}} (1x)"
            - "{{POTASSIUM}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 100 marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     An isotonic solution used to replace lost fluids, or to treat {{ACIDOSIS}}.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - \+30% Blood Pressure
     - \+0.07% {{ALKALOSIS}} per second

     Lasts for 200 seconds.

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \+30% Blood Pressure
     - \+0.07% {{ALKALOSIS}} per second

     Lasts for 120 seconds.

---