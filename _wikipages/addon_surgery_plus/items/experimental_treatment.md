---
layout: contentpage
title: Experimental Treatment
addon: surgery_plus
subcategory: items
permalink: /items/surgery_plus/experimental_treatment
# image: /images/svg/anybodypart.svg
inline_image: /images/addon_surgery_plus/items/experimental_treatment.png

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
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements"
        items:
            - "Unethical Sourcing Talent (Surgeon)"
            - "{{MEDICAL}} 60"
            - "{{SURGERY}} 40"
            - "{{PROPOFOL}} (1x)"
            - "{{CYANIDE}} (1x)"
            - "{{ADRENALINE}} (1x)"
            - "{{URANIUM}} (1x)"

      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Cannot be bought"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Experimental Treatment is a talent item unlockable by the Surgeon class. It can randomly give effects both negative and positive, though it tends to give positive effects more than negative ones.
     There's a theoretical chance to get infinite effects from one use of this item; imagine flipping a coin and only stopping when you get tails. Every time you get heads, you get an additional effect from this item.
     <br><br>
     #### The list of possible positive effects are as follows:

     - {{VIGOR}} (randomly picks from 200-400% strength)
     - {{HYPERACTIVITY}} (randomly picks from 200-400% strength)
     - {{PSYCHOSIS_RESISTANCE}} (randomly picks from 200-400% strength)
     - {{HUSK_INFECTION_RESISTANCE}} (randomly picks from 200-400% strength)
     - {{PARALYSIS_RESISTANCE}} (randomly picks from 300-600% strength)
     - {{ANALGESIA}} (randomly picks from 20-100% strength)
     - {{ANESTHESIA}} (randomly picks from 1-100% strength)
     - {{OINTMENTED}} (randomly picks from 20-100% strength)
     - {{COMBAT_STIMULANT}} (randomly picks from 30-100% strength)
     - {{PRESSURE_STABILIZED}} (randomly picks from 30-100% strength)
     - A full heal (treats 20-100% of {{OPEN_WOUNDS}}, {{VANILLA_ORGAN_DAMAGE}}, {{NEUROTRAUMA}} and {{BLOOD_LOSS}}, and fully cures {{SEPSIS}})
     
     <br><br>
     #### The list of possible negative effects are as follows:

     - {{OPEN_WOUNDS}} (5-20%)
     - {{BLEEDING}} (30-80%)
     - {{STUN}} for 2-15 seconds

---