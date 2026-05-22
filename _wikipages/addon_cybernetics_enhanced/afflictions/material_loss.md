---
layout: contentpage
title: Material Loss
addon: cybernetics_enhanced
subcategory: afflictions
permalink: /afflictions/cybernetics_enhanced/material_loss/
inline_image: /images/addon_cybernetics_enhanced/afflictions/material_loss.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     When taking damage to a cyberlimb, each type of damage has a chance to cause various types and amounts of cyberlimb specific damage instead of the normal damage type.

     The amount of material loss gained scales with the amount of {{LOOSE_SCREWS}} , to a maximum of x3 at 100% loose screws)
  
  - type: caused_by
    header: "Caused By:"
    order: 2
    text: |
     - {{LOOSE_SCREWS}}  while moving (30% or more)
     - 75% chance for {{LACERATIONS}} to cause 25% of their damage as material loss
     - 80% chance for a {{GUNSHOT_WOUND}} to cause 80% of their damage as material loss
     - 75% chance for {{BITE_WOUNDS}} to cause 60% of their damage as material loss
     - 100% chance for a {{DEEP_TISSUE_INJURY}} to cause 100% of its damage as material loss
     - 80% chance for {{FOREIGN_BODIES}} to cause 50% of their damage as material loss
  
  - type: effects
    header: "Effects:"
    order: 3
    text: |
     - Loss of cyberlimb and {{TRAUMATIC_AMPUTATION}} (at 99% or more)
  
  - type: treatments
    header: "Treatments:"
    order: 4
    text: |
     - {{STEEL_BAR}}

---