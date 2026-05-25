---
layout: contentpage
title: Debridement
category: procedures
addon: infections
subcategory: procedures
permalink: /afflictions/nt_infections/debridement/
inline_image: /images/addon_infections/procedures/debridement.png

infobox:
  - title: Labels
    sections:
      - items:
          - Surgery
          - Infections Expansion

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     A surgical procedure used to treat {{NECROTIZING_FASCIITIS}} by removing infected tissue.

     Steps:
     1. Apply an Anesthetic: ({{ANALGESIA}} or {{ANESTHESIA}}).
     2. Use {{SCALPEL}}.
     3. Use {{HEMOSTAT}}.
     4. Use {{SKIN_RETRACTORS}}.
     5. Repeatedly use {{SCALPEL}} until the infection is cleared.

  - type: application_success
    header: "Step 5 Success:"
    order: 2
    text: |
     - \+8% {{LACERATIONS}}
     - \-5% {{NECROTIZING_FASCIITIS}}

  - type: application_failure
    header: "Step 5 Failure:"
    order: 3
    text: |
     - \+10% {{LACERATIONS}}
     - \+5% {{BLEEDING}}
     - \-5% {{NECROTIZING_FASCIITIS}}
---