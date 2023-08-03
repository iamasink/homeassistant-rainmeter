# home assistant battery level rainmeter skin :3
You will have to modify the skin to include:
 - Your device name
 - Your home assistant url
 - Your home assistant long lived access token

To get your token:
 - Goto http://homeassistant.local:8123/profile
 - Scroll to "Long-Lived Access Tokens"
 - Create a token
 - Copy the token it gives you and put it into HomeassistantToken= in `@Resources\Variables.inc`

# example images
![image1](https://github.com/iamasink/Rainmeter-homeassistantbattery/assets/35533595/440b6dd9-c3c5-4bbe-8ef6-f3786e00ce46)
![image2](https://github.com/iamasink/Rainmeter-homeassistantbattery/assets/35533595/cbba36d5-002c-45cf-ae47-aaaa2a8e5e95)  
note to get multiple, you have to install the skin once, rename the installed folder and install it again.




# credits
Battery Icons from [Pictogrammers](https://pictogrammers.com/library/mdi/), and modified by me to fit the skin.  
They are renamed as such:  
battery-outline -> battery-off0  
battery-charging-outline -> battery-on0  
battery-10 through battery-90-> battery-off10 through battery-off90  
battery-charging-10 through battery-charging-100 -> battery-on10 through battery-on100  
battery -> battery-off100  
