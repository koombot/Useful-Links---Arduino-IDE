# Useful-Links---Arduino-IDE
Links to useful repos and code for working with Arduino IDE
I2C scanner for Raspberry Pi Pico:
https://github.com/lkoepsel/I2C/tree/main/Arduino/Pico/I2C_Scanner

Scan SPI Ports on PICO
     void setup() {
      Serial.begin(115200);
    }
    
    void loop() {
      Serial.print("MOSI: ");
      Serial.println(MOSI);
      Serial.print("MISO: ");
      Serial.println(MISO);
      Serial.print(" SCK: ");
      Serial.println(SCK);
      Serial.print("  SS: ");
      Serial.println(SS);
      Serial.println();
      delay(5000);
    }

Link to Bodmer post about SPI Display in TFT_eSPI on RP2040.  Has a really nice bouncing balls animation
https://forum.arduino.cc/t/tft_espi-support-for-raspberry-pi-pico-added/702551/7

Link to earlephilhower skeetch to test SPI.  Needed to check how to properly change SPI ports
https://github.com/earlephilhower/arduino-pico/tree/master/libraries/SPISlave/examples/SPItoMyself
