---
layout: contentpage
title: Hyperzine
category: items
subcategory: consumables
permalink: /items/consumables/hyperzine
image: /images/svg/anybodypart.svg
inline_image: /images/items/consumables/hyperzine.png

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
     - \+18% [Chem addiction](https://barotraumagame.com/wiki/Chem_Addiction)
     - \+18% {{NEUROTRAUMA}}
     - \+15% {{PSYCHOSIS}}
     - \+400% [Hyperactivity](https://barotraumagame.com/wiki/Hyperactivity)
     - \+400% [Vigor](https://barotraumagame.com/wiki/Vigor)
     - \-54% [Stun](https://barotraumagame.com/wiki/Stun)
     - \-90% {{CHEMICAL_WITHDRAWAL}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \-6% {{INTERNAL_DAMAGE}}
     - \+36% [Chem addiction](https://barotraumagame.com/wiki/Chem_Addiction)
     - \+36% {{NEUROTRAUMA}}
     - \+30% {{PSYCHOSIS}}
     - \+400% [Hyperactivity](https://barotraumagame.com/wiki/Hyperactivity)
     - \+400% [Vigor](https://barotraumagame.com/wiki/Vigor)
     - \-27% [Stun](https://barotraumagame.com/wiki/Stun)
     - \-90% {{CHEMICAL_WITHDRAWAL}}
     <br><br>
     [Hyperactivity](https://barotraumagame.com/wiki/Hyperactivity) and Vigor are applied instantly, while the other effects are applied over a 60 second duration.

---