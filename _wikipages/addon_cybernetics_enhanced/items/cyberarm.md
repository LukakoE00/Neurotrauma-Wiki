---
layout: contentpage
title: Cyberarm
addon: cybernetics_enhanced
subcategory: items
permalink: /items/cybernetics_enhanced/cyberarm
# image: /images/svg/anybodypart.svg
inline_image: /images/addon_cybernetics_enhanced/items/cyberarm.png

blocks:
  - type: description
    header: "Description:"
    order: 1
    text: |
     #### Mechanical Skill Check: 70
     A cybernetic arm that can be attached to any Surgically Amputated arm socket. Can be removed with a Crowbar.

     #### Advantages of Cyberarms:

     - Improves melee attack speed and swim speed.
     - Great at taking sustained gunfire without malfunctioning.
     - Excellent at tanking attacks from creatures without malfunctioning or breaking.
     - Ideal at sustaining attacks that would otherwise cause life-threatening bleeding.
     - When well maintained, is much less likely to be forcefully amputated when attacked.
     - Does not fracture or dislocate. Make sure you fix any dislocations or fractures BEFORE you add a cyber limb or else it will be permanent until you take off the limb.

     #### Disadvantages of Cyberarms:

     - They do not mix well with water. Won’t shock you, but will break over time if you don’t wear a suit.
       - The expensive Waterproof Cyberarm upgraded item prevents this, and otherwise has identical characteristics.
     - Requires maintenance if damaged.
     - Costly maintenance, especially if your sub doesn’t have an ample source of steel and FPGA circuits.
     - Costly/expensive to make/buy.
     - Violently detach if critically damaged through material loss.

  - type: application_success
    header: "Application Success:"
    order: 2
    text: |
     - Applies the Cyberarm on the selected limb and heals any internal damage caused by any previous failed attempts.

  - type: application_failure
    header: "Application Failure:"
    order: 3
    text: |
     - Applies between 15% to 50% {{BLEEDING}} on the Torso. Does not delete the Cyberarm.
---