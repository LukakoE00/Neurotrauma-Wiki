---
layout: contentpage
title: Human Eye Damage
addon: nt_eyes
subcategory: damage_afflictions
permalink: /afflictions/nt_eyes/human_eye_damage/
inline_image: /images/addon_nt_eyes/afflictions/human_eye_damage.png

infobox:
  - title: Labels
    sections:
      - items:
          - Affliction
          - Eyes Expansion

  - title: Respective Item
    sections:
      - items:
          - "{{HUMAN_EYE}}"

blocks:
  - type: caused_by
    header: "Caused By:"
    order: 1
    text: |
     - {{HYPOXEMIA}} (value*0.05)
     
     - {{STROKE}} (value*0.1)
     
     - {{SEPSIS}} (value*0.4)
     
     - {{RETINOPATHY}} (value*0.1)
     
     - Water Pressure (3% every tick)
     
     - Physical damage.

  - type: effects
    header: "Effects:"
    order: 2
    text: |
     - Possible {{CATARACTS}}

  - type: treatments
    header: "Treatments:"
    order: 3
    text: |
     - {{EYE_REMOVAL_SURGERY}}
     
     - {{LASER_EYE_SURGERY}}
     
     - Applying {{EYE_DROPS}}
     
     - Passive regeneration. (-0.1 damage every tick)
---
