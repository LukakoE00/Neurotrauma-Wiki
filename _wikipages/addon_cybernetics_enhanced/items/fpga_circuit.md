---
layout: contentpage
title: FPGA Circuit
addon: cybernetics_enhanced
subcategory: items
permalink: /items/cybernetics_enhanced/fpga_circuit
# image: /images/svg/anybodypart.svg
inline_image: /images/addon_cybernetics_enhanced/items/fpga_circuit.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### Electrical Skill Check: 40

     Used to repair {{DAMAGED_ELECTRONICS}} on Cyberlimbs.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |

     - \-50% {{DAMAGED_ELECTRONICS}}

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |

     - \-20% {{DAMAGED_ELECTRONICS}}

---