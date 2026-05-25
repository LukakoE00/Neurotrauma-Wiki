---
layout: contentpage
title: Diagnosing Bacterial Infections
addon: infections
subcategory: information
permalink: /addons/infections/information/diagnosing_bacterial_infections/
infobox:
  - title: Labels
    sections:
      - items:
          - Infections Expansion

blocks:
  - type: description
    header: ""
    order: 1
    text: |
     Diagnosing bacterial infections vary depending on what kind of infection it is.

     <br>
     #### Blood Infections / Bacteremia:
     Blood infections can be diagnosed by using a {{SAMPLER_TOOL}} anywhere in the health interface.

     Using a {{HEMATOLOGY_ANALYZER}} will show bacterial presence in blood, but will not be able to identify the strains.

     <br>
     #### Limb Infections:
     To make a limb diagnosis, you will need a {{CULTURE_TUBE}}. Insert the culture tube into a {{SAMPLER_TOOL}} and use it in the health interface to grab a sample. The order at which it will attempt to take a sample is as follows:

     - If the limb has {{PURULENT_DRAINAGE}} or {{ABSCESS}}, it will grab a pus sample
     - If a limb does not have a pus sample but has {{RETRACTED_SKIN}}, it will grab a tissue sample
     - If there is no pus or tissue sample, it will grab a blood sample (which will grab a random blood infection)

     <br>
     The sample will be placed into your inventory or on the floor if your inventory is full.

     Place the unknown sample inside a {{SAMPLE_ANALYZER}} to analyze it (the machine will need to be plugged in). It will return a sample that tells you which pathogen it is. If nothing is returned, the sample tested negative for an infection.

---