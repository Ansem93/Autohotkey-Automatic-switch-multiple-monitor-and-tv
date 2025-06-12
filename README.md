# Autohotkey-automaticcaly-switch-double-monitor-and-tv

Hi!
I created this script for AutoHotKey 2 to switch back and forth between my TV and my desk.
The main issue to made it automatic was that my TV was keeping the HDMI always active, so I had to use the ping to check if it was actually turned on.

I'm not a dev, so any advice about how to improve the code is welcomed!

1) First off you need monitor profile switcher:
https://sourceforge.net/projects/monitorswitcher/
2) create 2 profiles: desk and TV
 - If you want to use the test script assign them the shortcut ctr+alt+shift+8 and ctr+alt+shift+9
3) Create the folder Links inside the autohotkey directory ("C:\Program Files\AutoHotkey)
4) Copy the whatsapp shortcut in it
5) Assign a fixed IP to the TV
   
In all the files there are a few data that you need to compile, I put it between [] 

After this will make you switch between the TV and and desk.
I also added a few things:
1) Playnite fullscreen since I use the controller when I'm on the couch
2) Open/close some app that I won't need while playing from the tv like whatsapp and discord, but you can add telegram and so on
