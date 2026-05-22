---
layout: contentpage
title: Damaged Electronics
addon: cybernetics_enhanced
subcategory: afflictions
permalink: /afflictions/cybernetics_enhanced/damaged_electronics/
inline_image: /images/addon_cybernetics_enhanced/afflictions/damaged_electronics.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     The primary detriment of using cyberlimbs, as their electronics are damaged when exposed to water.

     When taking damage to a cyberlimb, each type of damage has a chance to cause various types and amounts of cyberlimb specific damage instead of the normal damage type.

     The amount of damaged electronics gained scales with the amount of {{MATERIAL_LOSS}} , up to a maximum of x3 at 100% material loss)
  
  - type: caused_by
    header: "Caused By:"
    order: 2
    text: |
     - Being in water without a diving suit on
     - 75% chance for {{BURNS}}  to cause 200% of their damage as damaged electronics
     - 85% chance for a {{GUNSHOT_WOUND}} to cause 75% of their damage as damaged electronics
     - 50% chance for {{BITE_WOUNDS}} to cause 25% of their damage as damaged electronics
     - 50% chance for a {{DEEP_TISSUE_INJURY}} to cause 50% of its damage as damaged electronics
     - 50% chance for {{BLUNT_FORCE_TRAUMA}} to cause 100% of its damage as damaged electronics
     - 75% chance for {{INTERNAL_DAMAGE}}  to cause 100% of its damage as damaged electronics
     - 75% chance for {{FOREIGN_BODIES}}  to cause 75% of its damage as damaged electronics
    
  - type: effects
    header: "Effects:"
    order: 3
    text: |
     - Limb occasionally stops working temporarily, frequency scales with strength
     - Limb becomes unusable (at 99% or more)
  
  - type: treatments
    header: "Treatments:"
    order: 4
    text: |
     - {{FPGA_CIRCUIT}}

---