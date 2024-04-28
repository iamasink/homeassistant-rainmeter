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
![image1](https://github.com/iamasink/rainmeter-homeassistant/assets/35533595/440b6dd9-c3c5-4bbe-8ef6-f3786e00ce46)
![image2](https://github.com/iamasink/rainmeter-homeassistant/assets/35533595/cbba36d5-002c-45cf-ae47-aaaa2a8e5e95)  
note to get multiple, you have to install the skin once, rename the installed folder and install it again.


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