---
layout: contentpage
title: Sepsis
category: afflictions
subcategory: blood
permalink: /afflictions/blood/sepsis/
image: /images/svg/blood.svg
inline_image: /images/base_neurotrauma/afflictions/blood/sepsis.png

addons:
  - id: vanilla
    label: Base Neurotrauma

  - id: nt_infections
    label: NT Infections

infobox:
  - title: Labels
    sections:
      - items:
          - Visible on Hematology Analyzer
          - Affliction
          - Lethal

blocks:
  - type: description
    header: "Description:"
    addon: vanilla
    order: 1
    text: |
     Sepsis is a dangerous affliction caused by letting {{INFECTED_WOUNDS}} fester. Sepsis is rather easy to spot, as only one other affliction in the game will give you {{FEVER}}.
  
  - type: caused_by
    header: "Caused By:"
    addon: vanilla
    order: 2
    text: |
     - Failing {{AZATHIOPRINE}} skill check
     - {{BLOOD_PACKS}} who's donor had sepsis
     - {{GANGRENE}} (15% or more)
     - {{FOREIGN_BODIES}} (20% or more)
     - {{INFECTED_WOUNDS}} (50% or more)
     - {{DIALYSIS_FILTER}}(0.1% chance per second)
     - {{TOXIN_FILTER}} (0.1% chance per second)
  
  - type: effects
    header: "Effects:"
    addon: vanilla
    order: 3
    text: |
     - {{LIVER_DAMAGE}} (3% or more, point at which it outpaces natural regeneration)
     - {{HEART_DAMAGE}} (at 3% or more, point at which it outpaces natural regeneration)
     - {{LUNG_DAMAGE}} (at 3% or more, point at which it outpaces natural regeneration)
     - {{GANGRENE}} (at 5% or more)
     - {{FEVER}} (at 5% or more)
     - {{KIDNEY_DAMAGE}} (at 6% or more, point at which it outpaces natural regeneration, 3% if one kidney is dead)
     - {{HYPERVENTILATION}} (at 15% or more)
     - {{INCREASED_HEARTRATE}} (at 20% or more)
     - {{NEUROTRAUMA}} (at 25% or more, point at which it outpaces natural regeneration)
     - {{CONFUSION}} (at 40% or more)
     - {{BONE_DAMAGE}} (at 50% or more, point at which it outpaces natural regeneration)
  
  - type: treatments
    header: "Treatments:"
    addon: vanilla
    order: 4
    text: |
     - {{BROAD_SPECTRUM_ANTIBIOTICS}}

# ------------------------------ NT INFECTIONS OVERRIDE ----------------------------------

  - type: description
    header: "Description:"
    addon: nt_infections
    order: 1
    text: |
     The body’s improper reaction to infection. Caused by serious infections that are not treated on time. Unlike vanilla Neurotrauma, sepsis cannot be treated with antibiotics.

  - type: caused_by
    header: "Caused By:"
    addon: nt_infections
    order: 2
    text: |
     - Limb Infections (>75%)
     - Blood Infections / Bacteremia (>0%)
     - {{NECROTIZING_FASCIITIS}} (>0%)
     - {{PNEUMONIA}} (>0%)

  - type: effects
    header: "Effects:"
    addon: nt_infections
    order: 3
    text: |
     - {{CONFUSION}}
     - {{ABDOMINAL_PAIN}}
     - {{FEVER}}
     - Lowers blood pressure

  - type: treatments
    header: "Treatments:"
    addon: nt_infections
    order: 4
    text: |
     - Treat the underlying causes (limb/blood infections)
     - {{HYDROCORTISONE}}
     - {{ADRENALINE}}
---