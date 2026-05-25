---
layout: contentpage
title: Sample Collection
category: procedures
addon: infections
subcategory: procedures
permalink: /afflictions/nt_infections/sample_collection/
inline_image: /images/addon_infections/procedures/sample_collection.png

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
     The process of obtaining biological samples for pathogen analysis.

  - type: bacterial_collection
    header: "For Bacterial Samples (Precedence):"
    order: 2
    text: |
     1. **Pus Sample:** Use {{SAMPLER_TOOL}} on {{PURULENT_DRAINAGE}} or {{ABSCESS}}.

     <br>
     2. **Tissue Sample:** 
        - Apply Anesthetic.
        - Use {{SCALPEL}}, {{HEMOSTAT}}, and {{SKIN_RETRACTORS}}.
        - Use {{SAMPLER_TOOL}} on the open incision.

     <br>
     3. **Blood Sample:** Use {{SAMPLER_TOOL}} on any limb.

  - type: viral_collection
    header: "For Viral Samples:"
    order: 3
    text: |
     1. Use {{SAMPLER_TOOL}} with {{VIRAL_TRANSPORT_MEDIUM}} on any limb.
---