---
layout: contentpage
title: Cyberlung
addon: cybernetics_enhanced
subcategory: items
permalink: /items/cybernetics_enhanced/cyberlung
# image: /images/svg/anybodypart.svg
# inline_image: /images/addon_cybernetics_enhanced/items/cyberlung.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     A cybernetic lung replacement. Embrace the certainty of steel!

     Available as a more affordable Cyber-augmented Lung (half meat, half silicon) crafted from an extracted Lung, or the twice as effective fully-synthetic Cyberlung.

     #### Advantages of Cyberlungs:

     - Partial Pressure Protection: briefly grants protection every 30 seconds, functionally doubling the non-lethal time spent in pressure without a suit
     - Improves melee attack speed and movement speed.
     - Resistant to {{LUNG_DAMAGE}} & {{PNEUMOTHORAX}}

     #### Disadvantages of Cyberorgans:

     - Can periodically experience fits of Cyberpsychosis (regular psychosis), which can be avoided by reducing your {{IMMUNITY}} in any way, such as the very affordable Immunosuppressant Inhaler.
  
  - type: how_to_add
    header: "How to Add:"
    order: 2
    text: |
     Do {{ORGAN_TRANSPLANT_SURGERY}}, using the Cyberlung instead of a feeble meat lung. Consider refrigerating the procured meat for upgrading into a Cyber-augmented Lung.

     #### Mechanical Skill Check: 60

     #### Medical/Surgical Skill Check: 70

     #### Application Success:

     Installs the cyberorgan, healing that organ’s damage and some {{VANILLA_ORGAN_DAMAGE}} .

     #### Application Failure (Mechanical):

     Same as Success but causes 20% {{LUNG_DAMAGE}}  .

     #### Application Failure (Medical):

     Same as Success but causes {{INTERNAL_BLEEDING}}.
  
  - type: how_to_remove
    header: "How to Remove:"
    order: 3
    text: |
     {{ORGAN_TRANSPLANT_SURGERY}} will remove and return the corresponding cybernetic organ.

---