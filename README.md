darktable-lua-scripts
=====================

**WARNING**
with the recent versions of darktable this script seems not working as aspected. So consider this repository as obsolete. 
I'm not planning to update the current repository.  Next days I will try to correct my script and push it to the official darktable lua script repository at https://github.com/darktable-org/lua-scripts


Unofficial collection of Lua scripts for darktable.

Description
-----------
Since few weeks ago, [darktable](https://github.com/darktable-org) master branch supports Lua scripting.

You can find informations and documentations in the darktable project pages:
- http://www.darktable.org/redmine/projects/darktable/wiki/LuaUsage
- http://www.darktable.org/redmine/projects/darktable/wiki/LuaAPI

This repository contains some script that I use to study, test and debug Lua scripting in darktable.


Thanks to Boucman for the great work on integrating Lua in darktable!


Quick Start
-----------
1. Clone this repository to your directory
2. Copy the script you want to use/test into ~/.config/darktable/lua/ directory
3. Import the script editing the /.config/darktable/rc.lua file

    require "the_script_name"

List of the working scripts
---------------------------
### cvs-list.lua
Export the information of selected images to a csv file.
This script regists a new darktable Storage; the path of exported file can be assigned in the Lua preference tab.
... of course you can do the same thing accessing directly to the darktable sqlite database!


Whishlist and ToDo list
-----------------------
- [ ] Script: quick tag assignement
- [ ] Script: auto-import new images 

- [ ] ToDo: how to use dialog with Lua?


Notes
-----
I'm not a Lua programmer, my know-how on Lua scripting is really limited, so please don't use these script in a production system without verify them.
Main purpose of this collection is to learn and test, so you are advised :)

