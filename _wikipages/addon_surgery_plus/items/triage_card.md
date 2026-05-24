---
layout: contentpage
title: Triage Card
addon: surgery_plus
subcategory: items
permalink: /items/surgery_plus/triage_card
# image: /images/svg/anybodypart.svg
inline_image: /images/addon_surgery_plus/items/triage_card.png

infobox:
  - title: Labels
    sections:
      - items:
          - Item
          - Surgery Plus Expansion

  - title: Statistics
    sections:
      - items:
          - "Maximum inventory stack: 8"

  - title: Crafting
    sections:
      - header: "Medical Fabricator Requirements"
        items:
            - "{{MEDICAL}} 5"
            - "{{PLASTIC}} (1x)"
            
      - header: "Deconstructor Yield"
        items:
            - "Has no deconstructor outputs."

  - title: Store
    sections:
      - items:
          - "Base Price: 50 Marks"
          - "Buyable at Merchant: Medical"

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     Triage Cards are used to mark patients based on severity of injury. There are two types of triage cards, those being manual and automatic. The manual triage card works as follows:

     Attaching the triage card to the legs will mark it as green, meaning that the patient is minimally injured and will most likely survive.
     Attaching the triage card to the arms will mark it as yellow, meaning that the patient is injured, and will most likely die if treatment is delayed for a long period of time.
     Attaching the triage card to the torso will mark it as red, meaning that the patient is critically injured and needs immediate assistance.
     Attaching the triage card to the head will mark it as black, meaning that the patient is either dead or extremely close to death.

     The automatic triage cards will rate your victim's health based off of their afflictions and vitality, and will give a rating of green, yellow, red or black.
---