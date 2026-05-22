---
layout: contentpage
title: Screwdriver
addon: cybernetics_enhanced
subcategory: items
permalink: /items/cybernetics_enhanced/screwdriver
# image: /images/svg/anybodypart.svg
inline_image: /images/addon_cybernetics_enhanced/items/screwdriver.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### Mechanical Skill Check: 50

     Used to repair {{LOOSE_SCREWS}} on Cyberlimbs.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - \-20% {{LOOSE_SCREWS}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \-5% {{LOOSE_SCREWS}}

---