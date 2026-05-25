---
layout: contentpage
title: Watcher Eye Damage
addon: nt_eyes
subcategory: damage_afflictions
permalink: /afflictions/nt_eyes/watcher_eye_damage/
inline_image: /images/addon_nt_eyes/afflictions/watcher_eye_damage.png

infobox:
  - title: Labels
    sections:
      - items:
          - Affliction
          - Eyes Expansion

  - title: Respective Item
    sections:
      - items:
          - "{{WATCHER_EYE}}"

blocks:
  - type: caused_by
    header: "Caused By:"
    order: 1
    text: |
     - {{HYPOXEMIA}} (value*0.1)
     
     - {{STROKE}} (value*0.03)
     
     - {{SEPSIS}} (value*0.03)
     
     - {{RETINOPATHY}} (value*0.25)
     
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
