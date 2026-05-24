---
layout: contentpage
title: Artificial Brain
addon: surgery_plus
subcategory: items
permalink: /items/surgery_plus/artificial_brain
# image: /images/svg/anybodypart.svg
inline_image: /images/addon_surgery_plus/items/artificial_brain.png

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
          - "Skill Required: None"
          - "Maximum inventory stack: 1"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements"
        items:
            - "Therapist-in-Training Talent (Surgeon)"
            - "{{MEDICAL}} 80"
            - "{{SURGERY}} 80"
            - "{{MANNITOL}} (1x)"
            - "{{FPGA_CIRCUIT}} (1x)"
            - "{{ALUMINIUM}} (1x)"
            - "{{STABILOZINE}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{FPGA_CIRCUIT}} (1x)"
            - "{{ALUMINIUM}} (1x)"

  - title: Store
    sections:
      - items:
          - "Cannot be bought"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Replaces a patients brain when used after removing it. Protects against gaining neurotrauma from not having a brain. Does nothing else.
---