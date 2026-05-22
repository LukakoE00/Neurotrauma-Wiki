---
layout: contentpage
title: Surgical Infection
addon: surgery_plus
subcategory: mechanics
permalink: /mechanics/surgery_plus/surgical_infection
inline_image: /images/addon_surgery_plus/mechanics/surgical_infection.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Surgical Infection is a mechanic that causes {{SEPSIS}} based on how sterile the patient's environment is.
     
     ####  The following will _increase_ sterility:

     - Patient wearing {{SURGICAL_DRAPES}} (+100 base sterility)
     - Nearby characters wearing {{SURGICAL_MASK}} and {{SURGEON_CLOTHES}} (scales with distance to patient)
     - Having surgery skill (sterility gained based off this equation: 10 + surgery skill / 5)
     - Having {{OINTMENTED}} on the incision (+50 sterility)

     #### The following will _decrease_ sterility:

     - Patient having no {{SURGICAL_DRAPES}} or {{OINTMENTED}} (sets sterility to the minimum)
     - Nearby characters not wearing {{SURGICAL_MASK}} or {{SURGEON_CLOTHES}} (scales with distance to patient)

     At the minimum sterility, there is a 10% chance every two seconds for the patient to acquire {{SEPSIS}}.
---