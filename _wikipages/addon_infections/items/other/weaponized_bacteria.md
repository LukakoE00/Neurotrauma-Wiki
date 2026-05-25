---
layout: contentpage
title: Weaponized bacteria
category: items
addon: infections
subcategory: consumables
permalink: /items/nt_infections/weaponized_bacteria/
inline_image: /images/addon_infections/items/weaponized_bacteria.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Infections Expansion

  - title: Statistics
    sections:
      - items:
          - "Skill Required: Medical 20"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 30"
            - "Confirmed Sample Tube (2x)"
            - "{{STABILOZINE}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Cannot be bought."

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Used maliciously to cause a blood infection in a character. Can be injected via swing, health interface, or syringe gun.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |
     - \+10% Blood Infection Severity

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |
     - \+8% Blood Infection Severity
---