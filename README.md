# Autohotkey-automaticcaly-switch-double-monitor-and-tv

Hi!
I created this script for AutoHotKey 2 to switch back and forth between my TV and my desk.

What the script does is straight forward:
- If the TV respond to ping: 
  1) Switch to TV profile
  2) Close all program I don't need
  3) Open Playnite in fullscreen mode
- When the TV stop responding:
   1) Wait for 3 failed pings in order to avoid some random missed ping
   2) Switch to desk profile
   3) Open the selected app
   4) Open Playnite in desktop mode
- In case something goes wrong press F7 to stop the script

Why the ping? Because my TV keep the HDMI always active even when turned off, so to Windows it's always turned ON. 


1) First off you need monitor profile switcher and autohotkey:
https://sourceforge.net/projects/monitorswitcher/
https://www.autohotkey.com/
3) create 2 profiles: desk and TV based on what you need. My desk profile has the TV (monitor 3 for Windows) disabled while TV has Monitor 1 and 2 disabled to keep only TV turned on 
 - If you want to use the test script assign them the shortcut ctr+alt+shift+8 and ctr+alt+shift+9
3) Create the folder Links inside the autohotkey directory ("C:\Program Files\AutoHotkey).
4) Copy the whatsapp shortcut in it, if you want also other apps you want to open
5) Assign a static IP to the TV
   
In all the files there are a few data that you need to compile, I put it between [] 

I juggest to use the test files before the script just to be sure everything works properly.
They also can be usefull if you prefer to manually activate the profiles
I also use Unified Remote for Android to launch manually in case something went wrong


I'm not a dev, so any advice about how to improve the code is welcomed!
