---
layout: contentpage
title: Sample analyzer
category: items
addon: infections
subcategory: tools
permalink: /addons/infections/items/sample_analyzer/
inline_image: /images/addon_infections/items/sample_analyzer.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Infections Expansion

  - title: Statistics
    sections:
      - items:
          - "Maximum inventory stack: 1"

  - title: Crafting
    sections:
      - header: "Fabricator Requirements (Output: 1x)"
        items:
            - "{{MEDICAL}} 40"
            - "{{FPGA_CIRCUIT}} (1x)"
            - "{{PLASTIC}} (1x)"
            - "{{STEEL_BAR}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "{{ZINC}} (1x)"
            - "{{STEEL_BAR}} (1x)"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     A specialized medical machine used to identify the specific pathogen strains within collected samples.

     The machine will only accept bacterial {{CULTURE_TUBE}} or {{VIRAL_TRANSPORT_MEDIUM}}. It must be plugged into a power source to function. If a sample is analyzed and nothing is returned, the sample has tested negative for infections.
---