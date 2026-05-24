---
layout: contentpage
title: Naloxone
category: items
subcategory: consumables
permalink: /items/consumables/naloxone
image: /images/svg/anybodypart.svg
inline_image: /images/items/consumables/naloxone.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Niche

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 39"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 23"
            - "{{OPIUM}} (1x)"
            - "{{STABILOZINE}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{STABILOZINE}} (1x)"

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
     Naloxone is used to treat the effects of opiates.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - \-60% {{OPIATE_WITHDRAWAL}}
     - \-60% {{OPIATE_OVERDOSE}}
     - \-60% {{OPIATE_ADDICTION}}
     - \-60% {{ANALGESIA}}
     - \-60% Opioids

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \-30% {{OPIATE_WITHDRAWAL}}
     - \-30% {{OPIATE_OVERDOSE}}
     - \-30% {{OPIATE_ADDICTION}}
     - \-60% {{ANALGESIA}}
     - \-60% Opioids
     - \+15% {{COMA}} (50% chance)
---