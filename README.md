# esp32_proxy
Wifi to ethernet proxy using an ESP32 with ethernet. Primarily used to access service interface on SunPower PVS5 & PVS6 residential solar monitor to integrate with Home Assistant. Inspired by Raspberry Pi proxy linked below.

## Related projects
[Home Assistant] (https://www.home-assistant.io/)  
[HASS Sunpower] (https://github.com/krbaker/hass-sunpower)  
[Raspberry Pi ethernet proxy {PDF}] (https://starreveld.com/PVS6%20Access%20and%20API.pdf)  

## Hardware
Built and tested with HUZZAH32 ESP32 Feather Board & Ethernet Feather Wing.  
[Adafruit HUZZAH32-ESP32 Feather Board] (https://www.adafruit.com/product/3405)
[Adafruit Ethernet FeatherWing] (https://www.adafruit.com/product/3201)
Approximate hardware cost (2022-10-01): $40 USD + tax and shipping.

## How to use
Add wireless SSID & password to secrets.h. Deploy to esp32 and watch logs.
