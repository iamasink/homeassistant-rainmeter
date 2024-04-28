# home assistant rainmeter
My rainmeter skins using homeassistant  
There are two skins: batterydisplay and binarysensor.  
They use the Home Assistant API to get the battery, or binary state of a device respectively.  
They support common icon types, such as Door, Window, Lock, Light  

---
  
You will have to modify the skin to include:
 - Your device name
 - Your home assistant url
 - Your home assistant long lived access token

To get your token:
 - Goto http://homeassistant.local:8123/profile
 - Scroll to "Long-Lived Access Tokens"
 - Create a token
 - Copy the token it gives you and put it into HomeassistantToken= in `@Resources\Variables.inc`

You might also need to enable some stuff in the app on your phone:  
Home Assistant App -> Settings -> Companion App -> Manage Sensors -> Ensure `Battery Level` and `Charger Type` are enabled  
However these are enabled by default, so this shouldn't be necessary.

# example images
![image](https://github.com/iamasink/homeassistant-rainmeter/assets/35533595/01f14071-be89-4a52-8e08-35551cf4144a)

note to get multiple of the same type, you have to install the skin once, rename the installed folder and install it again, or copy paste the skin folder.


# credits
Icons from [Pictogrammers](https://pictogrammers.com/library/mdi/), and slightly modified by me to fit the skin.  

They are renamed as such:  
for batterydisplay:  
- battery-outline -> battery-off0  
- battery-charging-outline -> battery-on0  
- battery-10 through battery-90-> battery-off10 through battery-off90  
- battery-charging-10 through battery-charging-100 -> battery-on10 through battery-on100  
- battery -> battery-off100  

for binarysensor:  
- brightness-5 -> light-off  
- brightness-7 -> light-on  
- door-closed -> door-off  
- door-open -> door-on  
- garage -> garage-on  
- garage-open -> garage-off  
- lock -> lock-off  
- lock-open -> lock-on  
- snowflake -> cold-on  
- thermometer -> cold-off  
- square -> opening-off  
- square-outline -> opening-on  
- window-open -> window-on  
- window-close -> window-off  
- help-box-outline -> unknown  
