---
layout: contentpage
title: MRSA Infection
addon: infections
subcategory: bacterial_infections
permalink: /afflictions/nt_infections/mrsa_infection/
inline_image: /images/addon_infections/afflictions/pus_yellow.png

infobox:
  - title: Labels
    sections:
      - items:
          - Affliction
          - Infections Expansion

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     A strain of _staphylococcus aureus_ that has gained resistance to many antibiotics due to extensive antibiotic usage. It is impervious to many penicillin-type antibiotics.

     Pus is usually yellowish in presentation.

  - type: caused_by
    header: "Caused By:"
    order: 2
    text: |
     - {{STAPHYLOCOCCAL_INFECTION}} (initial infection)
     - {{METHICILLIN_RESISTANCE_RISK}} (>0%)

  - type: effects
    header: "Effects:"
    order: 3
    text: |
     - Blood infection (>50%)
     - {{INFLAMMATION}} (>0%)
     - {{PURULENT_DRAINAGE}} (>25% with wound)
     - {{ABSCESS}} (>25% without wound)
     - {{PNEUMONIA}} (Blood infection >0%)

  - type: treatments
    header: "Treatments:"
    order: 4
    text: |
     #### Susceptible to:

     - {{VANCOMYCIN}} (98% effective)
     - {{CO_TRIMOXAZOLE}} (80% effective)
     - {{GENTAMICIN}} (10% effective)
---