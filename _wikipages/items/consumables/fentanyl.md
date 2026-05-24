---
layout: contentpage
title: Fentanyl
category: items
subcategory: consumables
permalink: /items/consumables/fentanyl
image: /images/svg/anybodypart.svg
inline_image: /images/items/consumables/fentanyl.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
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
            - "{{MEDICAL}} 50"
            - "{{OPIUM}} (1x)"
            - "{{ADRENALINE}} (1x)"
            - "{{ETHANOL}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{OPIUM}} (1x)"
            - "{{ADRENALINE}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 190 marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     A powerful opiate used to induce {{ANALGESIA}}.

     To prevent exploits, fentanyl cannot be shot as a projectile, such as out of a Syringe Gun.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - \+75% {{ANALGESIA}}
     - \+15% {{OPIATE_ADDICTION}}
     - \+22.5% {{OPIATE_OVERDOSE}}
     - \-100%{{OPIATE_WITHDRAWAL}}

     #### While >30% drunk changes to:

     - \+150% {{ANALGESIA}}
     - \+15% {{OPIATE_ADDICTION}}
     - \+37.5% {{OPIATE_OVERDOSE}}
     - \-100% {{OPIATE_WITHDRAWAL}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \+50% {{ANALGESIA}}
     - \+40% {{OPIATE_ADDICTION}}
     - \+30% {{OPIATE_OVERDOSE}}
     - \-100% {{OPIATE_WITHDRAWAL}}

     #### While >30% drunk changes to:

     - \+100% {{ANALGESIA}}
     - \+40% {{OPIATE_ADDICTION}}
     - \+60% {{OPIATE_OVERDOSE}}
     - \-100% {{OPIATE_WITHDRAWAL}}

---