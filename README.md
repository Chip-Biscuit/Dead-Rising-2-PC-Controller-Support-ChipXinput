<div align="center">

# 🎮 Game Specific Patches & DLL Wrappers  

***created and maintained by***

[![Chip-Biscuit Website](https://img.shields.io/badge/Chip--Biscuit-Website-blue?style=for-the-badge)](https://chip-biscuit.github.io/)

Reverse Engineering • Programming • Patching • Game Improvements • DLL Creation 

</div>

# Dead Rising 2 PC Controler Fix 

# Information
This is a library I have been working on for some time now to add x-input support into games with broken or missing controller support.

# Instructions

Go to releases and download DeadRising2Controller.zip unzip it and put the contents into your games install location next to deadrising2.exe. in d3d9.ini you can fully customise the inputs its all explained in the INI you can also use [hotkey]keycodes.txt provided in the fix to help you.

Instructions:

    Put d3d9.dll & d3d9.ini files in the directory of the game (next to deadrising2.exe)


# Custom Controller Layout 

<img width="870" height="665" alt="Dead_Rising_2_Xbox_Controller_Layout_Image" src="https://github.com/user-attachments/assets/ec92a71f-89f4-428a-bf43-e1441d221080" />
<br>

<img width="928" height="1413" alt="Dead_Rising_2_Xbox_Controller_Layout" src="https://github.com/user-attachments/assets/c8b8a55c-6f59-4053-96dc-c4f32b562dab" />


# Alternative user profile if the above doesn't work:

[![PCGamingWiki](https://img.shields.io/badge/PCGamingWiki-File%20Page-0066cc?style=flat&logo=pcgamingwiki&logoColor=white)](https://community.pcgamingwiki.com/files/file/3730-chipxinput-dead-rising-2-controller-calibration-fix/)

# If you experience double input 

An effect of this fix can be the fact that in some cases it will make native X-input work again in your game, in that case it is important to note that in this fix for each input inside of the .ini file you can put ***= NONE*** 

**for example** 

***A = NONE***

***B = NONE***

you can do this for every input on the Xbox controller in the .ini file

this will disable completely the custom (chip-xinput) layer for the game but the native x-input will still work you can either put NONE for each key as in the example above OR at the top of the ini set  ***output = 0***

Otherwise you would have an xbox button doing 2 inputs inside of the game like: 

**Native A = Jump in game + Chip xinput = LMB in game at the same time**


# Issues
If you have any issues please go to discord for help 

https://discord.gg/eVJ7sQH7Cc


# Credits
Credit to Elisha Riedlinger for the base wrapper and 13 AG.

Brought to you by Fix Enhancers - https://fixenhancers.wixsite.com/fix-enhancers

---

### Fix Enhancers  
https://fixenhancers.wixsite.com/fix-enhancers

“Creating compatibility fixes and enhancements for legacy PC games.”

# Chip
- founder
- reverse engineer
- programmer
- developer
- Game Preservationist
  
<img width="250" height="500" alt="my logoo" src="https://github.com/user-attachments/assets/9bb13d3f-0734-4f1d-b68f-14114b13744a" />


# JokerAlex21 
- founder
- admin
- tester 

<img width="250" height="250" alt="YouTube_Logo" src="https://github.com/user-attachments/assets/5c7204ca-4bca-4673-8117-965732e7ee6d" />
