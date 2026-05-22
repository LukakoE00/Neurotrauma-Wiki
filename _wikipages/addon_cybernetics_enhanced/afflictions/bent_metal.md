---
layout: contentpage
title: Bent Metal
addon: cybernetics_enhanced
subcategory: afflictions
permalink: /afflictions/cybernetics_enhanced/bent_metal/
inline_image: /images/addon_cybernetics_enhanced/afflictions/bent_metal.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     When taking damage to a cyberlimb, each type of damage has a chance to cause various types and amounts of cyberlimb specific damage instead of the normal damage type.
  
  - type: caused_by
    header: "Caused By:"
    order: 2
    text: |
     - 85% chance for {{BURNS}}  to cause 25% of their damage as bent metal
     - 50% chance for {{LACERATIONS}} to cause 25% of their damage as bent metal
     - 50% chance for {{BITE_WOUNDS}} to cause 50% of their damage as bent metal
     - 85% chance for a {{DEEP_TISSUE_INJURY}} to cause 100% of its damage as bent metal
     - 75% chance for {{BLUNT_FORCE_TRAUMA}} to cause 200% of its damage as bent metal
  
  - type: effects
    header: "Effects:"
    order: 3
    text: |
     - Makes you slower if on a {{CYBERLEG}}, scales with strength
     - Limb becomes unusable (at 99% or more)
  
  - type: treatments
    header: "Treatments:"
    order: 4
    text: |
     - {{WELDING_TOOL}}  (requires welding fuel)
---