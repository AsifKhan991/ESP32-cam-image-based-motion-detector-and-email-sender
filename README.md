# ESP32-cam-image-based-motion-detector-and-email-sender
## This repository shows a method of detecting motion based on image frame difference only. No additional hardware needed. Also shows how to send the captured image using email without the need of SD card or SPIFFS. 

### board installation link : https://dl.espressif.com/dl/package_esp32_index.json
### library required : [EloquentArduino](https://github.com/eloquentarduino/EloquentArduino), [ESP mail client](https://github.com/mobizt/ESP-Mail-Client)

Note: It's better to power up the esp32-cam module with seperate power source and make sure your isp isn't blocking connection to smtp server.!

