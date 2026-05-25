---
layout: contentpage
title: Retinopathy
addon: nt_eyes
subcategory: mechanic_afflictions
permalink: /afflictions/nt_eyes/retinopathy/
inline_image: /images/addon_nt_eyes/afflictions/retinopathy.png
infobox:
  - title: Labels
    sections:
      - items:
          - Affliction
          - Eyes Expansion
blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Autoimmune Retinopathy, or damage to the retina, may be caused by having a singular dead eye if your immunity is above 10%. The other eye (if biological!) will rapidly sustain damage as the body overreacts.

     Will not be visible on the Health Scanner until it is above 5% strength; though symptoms will appear before then.

     The possibility of this happening can be disabled in the {{CONFIGURATION_MENU}}.

  - type: caused_by
    header: "Caused By:"
    order: 2
    text: |
     - {{DEAD_EYE}}

  - type: effects
    header: "Effects:"
    order: 3
    text: |
     - Massive eye damage.

  - type: treatments
    header: "Treatments:"
    order: 4
    text: |
     - {{EYE_REMOVAL_SURGERY}}
     
     - {{AZATHIOPRINE}} until ({{IMMUNITY}} < 10%)
---
