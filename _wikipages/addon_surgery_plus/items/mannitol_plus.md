---
layout: contentpage
title: Mannitol Plus
addon: surgery_plus
subcategory: items
permalink: /items/surgery_plus/mannitol_plus
# image: /images/svg/anybodypart.svg
inline_image: /images/addon_surgery_plus/items/mannitol_plus.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Niche
          - Surgery Plus Expansion

  - title: Statistics
    sections:
      - items:
          - "Skill Required: {{MEDICAL}} 70"
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements"
        items:
            - "Mannitol Maniac Talent (Surgeon)"
            - "{{MEDICAL}} 80"
            - "{{SURGERY}} 80"
            - "{{MANNITOL}} (1x)"
            - "{{ADRENALINE}} (1x)"
            - "{{LIQUID_OXYGENITE}} (1x)"
            - "{{STABILOZINE}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{MANNITOL}} (1x)"
            - "{{ADRENALINE}} (1x)"

  - title: Store
    sections:
      - items:
          - "Cannot be bought"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Mannitol Plus is a talent item, meaning it requires a talent to craft. Upon being administered, it will treat 30% {{NEUROTRAUMA}} over the course of 10 seconds even if the patient is unstable and apply the {{MANNITOL}} affliction without causing organ damage.
---