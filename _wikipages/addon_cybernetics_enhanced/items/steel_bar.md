---
layout: contentpage
title: Steel Bar
addon: cybernetics_enhanced
subcategory: items
permalink: /items/cybernetics_enhanced/steel_bar
# image: /images/svg/anybodypart.svg
inline_image: /images/addon_cybernetics_enhanced/items/steel_bar.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### Mechanical Skill Check: 60

     Used to repair {{MATERIAL_LOSS}} on Cyberlimbs.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - \-50% {{MATERIAL_LOSS}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \-20% {{MATERIAL_LOSS}}

---