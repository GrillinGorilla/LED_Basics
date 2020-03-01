# LED_Basics


[ESP32 Pin Out](https://github.com/GrillinGorilla/LED_Basics/blob/master/images/esp32_pinout.PNG)

[How to determine which power supply I need](https://www.waveformlighting.com/home-residential/how-to-choose-a-power-supply-for-your-led-strip-project)

# Arduino IDE Set-up
### Preferences
#### Additional Board Manager URLs
```
https://dl.espressif.com/dl/package_esp32_index.json
http://arduino.esp8266.com/stable/package_esp8266com_index.json,
https://files.husarion.com/arduino/package_esp32_husarnet_index.json
```
#### Libraries
- Adafruit NeoPixel (for RGBW)
- FastLED (for RGB)
- AsyncDelay by Steve Marple
- ESP Async E1.31 
- NeoPixelBus by Makuna

#### Board Manager
- esp32 by Espressif Systems
- esp32 husarnet
