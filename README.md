# ESP32-cam-image-based-motion-detector-and-email-sender
## This repository shows a method of detecting motion based on image frame difference only. No additional hardware needed. Also shows how to send the captured image using email without the need of SD card or SPIFFS. 

### board installation link : https://randomnerdtutorials.com/installing-the-esp32-board-in-arduino-ide-windows-instructions/
### library required : [EloquentArduino](https://github.com/eloquentarduino/EloquentArduino), [ESP mail client](https://github.com/mobizt/ESP-Mail-Client)

Note: 
  1) It's better to power up the esp32-cam module with seperate power source or it might cause brownout while processing frames
  2) Make sure your isp isn't blocking connection to smtp server.!
  3) Don't exceed frame quality of SVGA
  4) Jpeg conversion quality in line 133 effects the heap memory required to store the image
  5) Becareful of heap memory usage as smptp ssl connection depends on it. Less memory might cause problem when handling ssl connection. 

