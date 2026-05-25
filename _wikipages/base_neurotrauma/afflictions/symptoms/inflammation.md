---
layout: contentpage
title: Inflammation
category: afflictions
subcategory: symptoms
permalink: /afflictions/symptoms/inflammation/
image: /images/svg/symptoms.svg
inline_image: /images/base_neurotrauma/afflictions/symptoms/inflammation.png

addons:
  - id: vanilla
    label: Base Neurotrauma

  - id: nt_infections
    label: NT Infections


infobox:
  - title: Labels
    sections:
      - items:
          - Non-Lethal
          - Affliction
          - Visible on Health Interface

blocks:
  - type: description
    header: "Description:"
    addon: vanilla
    order: 1
    text: |
     Inflammation is a symptom, which means that it isn't fatal and doesn't cause any other afflictions.
  
  - type: caused_by
    header: "Caused By:"
    addon: vanilla
    order: 2
    text: |
     - {{INFECTED_WOUNDS}} (10% or more)
     - {{FOREIGN_BODIES}} (15% or more)
  
  - type: treatments
    header: "Treatments:"
    addon: vanilla
    order: 3
    text: |
     - Treating the causes



# ------------------------------ NT INFECTIONS OVERRIDE ----------------------------------

  - type: description
    header: "Description:"
    addon: nt_infections
    order: 1
    text: |
     The skin presents with redness. This is a common sign of infection, but it can also be a useful way of determining an infection's progress or the presence of debris.

  - type: caused_by
    header: "Caused By:"
    addon: nt_infections
    order: 2
    text: |
     -   {{FOREIGN_BODIES}} (>15%)
     -   Bacterial infection with at least 0% progress (though it usually only becomes visible after >20%).

  - type: effects
    header: "Effects:"
    addon: nt_infections
    order: 3
    text: |
     -   Redness of the skin on the affected limb.

  - type: treatments
    header: "Treatments:"
    addon: nt_infections
    order: 4
    text: |
     -   Treat the underlying infection.
     -   Remove any {{FOREIGN_BODIES}} via surgery.
---