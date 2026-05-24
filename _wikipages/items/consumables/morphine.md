---
layout: contentpage
title: Morphine
category: items
subcategory: consumables
permalink: /items/consumables/morphine
image: /images/svg/anybodypart.svg
inline_image: /images/items/consumables/morphine.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Important

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 50"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 18"
            - "{{OPIUM}} (2x)"

      - header: "Deconstructor Yield"
        items:
            - "{{OPIUM}} (1x)"

  - title: Store
    sections:
      - items:
          - "Base Price: 100 marks"
          - "Buyable at Outposts: All"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     A moderately powerful opiate used to induce {{ANALGESIA}}.

     To prevent exploits, morphine cannot be shot as a projectile, such as out of a Syringe Gun.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - \+50% {{ANALGESIA}}
     - \+10% [Opiate Addiction](https://barotraumagame.com/wiki/Opiate_Addiction)
     - \+10% {{OPIATE_OVERDOSE}}
     - \-30% {{OPIATE_WITHDRAWAL}}

     #### While >30% drunk changes to:

     - \+100% {{ANALGESIA}}
     - \+10% [Opiate Addiction](https://barotraumagame.com/wiki/Opiate_Addiction)
     - \+20% {{OPIATE_OVERDOSE}}
     - \-30% {{OPIATE_WITHDRAWAL}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \+30% {{ANALGESIA}}
     - \+25% [Opiate Addiction](https://barotraumagame.com/wiki/Opiate_Addiction)
     - \+20% {{OPIATE_OVERDOSE}}
     - \-30% {{OPIATE_WITHDRAWAL}}

     #### While >30% drunk changes to:

     - \+60% {{ANALGESIA}}
     - \+25% [Opiate Addiction](https://barotraumagame.com/wiki/Opiate_Addiction)
     - \+40% {{OPIATE_OVERDOSE}}
     - \-30% {{OPIATE_WITHDRAWAL}}

---