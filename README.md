# NSpanel  
 Custom Firmware for the Sonoff NSpanel (EU) version.  
 CREDIT & THANKS TO THE FOLLOWING.  
 Initial work: Masto github: https://github.com/masto/NSPanel-Demo-Files  
 fully custom firmware: Marcfager github: https://github.com/marcfager/nspanel-mf  

# Features:  

## General: 
Touch-screen offset calibrated.  
Auto Upload .HMI file when new one is compiled in the Nextion editor.  
Auto Home.  
Auto Dim.  
Auto Screen-saver (I control this with automations in HA).  
Swipe between pages.  
Buzzer (tune after boot).  
  
Pysical Switches:  
Switch 1 turns on/off Heating.  
Switch 2 turns on/off Hot water.  
  
# Pages:  
  
## Home Page:  
Current weather symbols with transparent backgrounds.  
Home Temperature (from HA).  
Feels like Temp (needs HA addon from Hacs repos).   
Time (from HA).  
Date (from HA).  
Hot water state icon (on state only).  
Heating state icon (on state only).  

## Lights Page:  
6 Light switches(with state changing icons and transparent backgrounds).  
1 dimmer slider (controls 3 of the lights, select which light dims by long pressing whichever light).  

## Music Page:  
4 Radio station buttons (station url's setup in HA).  
Now playing song title & artist (this doesn't work when calling the url's to my google home mini, but does when I say "hey google, play smoothfm" for example.  
Play/Pause button (controls media player).  
Volume up button (controls media player).  
Volume down button (controls media player).  
  
## Thermostat Page:  
Hot water state Icon (on state only).  
Heating state Icon (on state only).  
Temperature from internal sensor.  
Target temperature (for HA climate component).  
Hot water Temperature.  
Target temperature up button.  
Target temperature down button.  
  
## Video Link:  
https://youtu.be/nDS4A_Cmsy8  


# Extra Info:    






