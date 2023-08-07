# home assistant battery level rainmeter skin :3
A Rainmeter skin which uses the Home Assistant API to get the battery state of a device, and display it on your desktop.  

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
![image1](https://github.com/iamasink/batterydisplay/assets/35533595/c3b8b557-3e8f-4f11-bb50-0a350334cb85)
note to get multiple, you have to install the skin once, rename the installed folder and install it again.


# credits
Battery Icons from [Pictogrammers](https://pictogrammers.com/library/mdi/), and modified by me to fit the skin.  
They are renamed as such:  
battery-outline -> battery-off0  
battery-charging-outline -> battery-on0  
battery-10 through battery-90-> battery-off10 through battery-off90  
battery-charging-10 through battery-charging-100 -> battery-on10 through battery-on100  
battery -> battery-off100  
