---
layout: contentpage
title: Anaparalyzant
category: items
subcategory: consumables
permalink: /items/consumables/anaparalyzant
image: /images/svg/anybodypart.svg
inline_image: /images/items/consumables/anaparalyzant.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Niche

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 64"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 24"
            - "{{PARALYZANT}} (1x)" 
            - "{{STABILOZINE}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{STABILOZINE}} (1x)"

  - title: Store
    sections:
      - items:
          - "Minimum Difficulty: 15%"
          - "Base Price: 200 marks"
          - "Buyable at Outposts: All"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Alongside it's original use of providing paralysis resistance and treating paralysis, Anaparalyzant can be used to quickly decrease {{ANESTHESIA}} and wake a patient up much faster.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |
     - Instantly cures {{ANESTHESIA}}
     - \+800% {{PARALYSIS_RESISTANCE}}.
     - \+5% {{PSYCHOSIS}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |
     - \-3% {{ANESTHESIA}} per second for 60 seconds.
     - \+6.5% {{PARALYSIS_RESISTANCE}} per second for 60 seconds.
     - \+0.75% {{PSYCHOSIS}} per second for 60 seconds.

---