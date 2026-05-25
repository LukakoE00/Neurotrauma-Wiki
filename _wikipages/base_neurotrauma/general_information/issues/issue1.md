---
layout: contentpage
title: Items will not work
contentheader: Items will not work
category: general_information
subcategory: issues
permalink: /general_information/issues/issue1/

blocks:
  - type: description
    header: "Explanation:"
    order: 1
    text: |
      If (certain) items don't do anything, it's most likely because you have a faulty Lua installation.

      Lua for Barotrauma is a Barotrauma modification that adds Lua and Cs modding, this is not a direct replacement for XML, but works great in doing things that weren't possible in XML.

      #### How to Install Lua: Check out the [Lua for Barotrauma](https://steamcommunity.com/workshop/filedetails/?id=2559634234) workshop page for specific installation guide for your OS.

      <br><br>
      #### Server Side Lua:

      Many Lua mods are server-sided, meaning Lua is only required to work on the server for those mods to work, to enable the mod on the server-side simply select the Server Executable when in the hosting menu.
      **If you want to checkout if the Lua is working properly on the server, open the debug console (F3) and run the command "reloadlua"**

      Note: This obviously doesn't work if you play on singleplayer, for that you will need to install Client-side Lua.

      <br><br>
      #### Client Side Lua:

      Client-side Lua is when the mod is running in your game client, many mods make use of it to either do more extensive changes to the game or to add singleplayer support.

      For example Neurotrauma will work mostly fine if you are playing multiplayer and only the server has Lua installed, it straightforward won't work on singleplayer if you don't have Client-side Lua installed, while -as examples- NT: Eyes and NT: Cybernetics Enhanced (Neurotrauma expansions) require both Server-side Lua and Client-side Lua to work properly in **multiplayer**. That means for these mods everyone will need Client-side Lua installed for it to work properly. It depends on each mod, so consult the description/author of the mod to make sure.

      **If you want to checkout if the mod is working properly on the client, open the debug console (F3) and run the command "cl_reloadlua".**

---