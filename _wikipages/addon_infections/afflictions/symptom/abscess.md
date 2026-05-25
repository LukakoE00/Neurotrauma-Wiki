---
layout: contentpage
title: Abscess
addon: infections
subcategory: symptoms
permalink: /afflictions/nt_infections/abscess/
inline_image: /images/addon_infections/afflictions/abscess.png

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
     Pus is accumulating under the skin, an obvious sign of an infection. They may pop when disturbed by an injury and lead to {{PURULENT_DRAINAGE}}.

  - type: caused_by
    header: "Caused By:"
    order: 2
    text: |
     -   Prerequisites
         -   Limb has an infection of at least 25% progress.
         -   Limb has --no-- wounds, burns, or sutures.

  - type: effects
    header: "Effects:"
    order: 3
    text: |
     -   If burst by the {{SAMPLER_TOOL}}, causes {{PURULENT_DRAINAGE}} and 2% Lacerations.

  - type: treatments
    header: "Treatments:"
    order: 4
    text: |
     -   A {{SAMPLER_TOOL}} with a {{CULTURE_TUBE}} can be used to collect a pus sample. This will burst the abscess.
     -   Treat the underlying infection.
---