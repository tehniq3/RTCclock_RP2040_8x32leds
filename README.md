# RTCclock_RP2040_8x32leds
based on https://github.com/tehniq3/RTCclock_8x32leds/ and RP2040-zero (https://www.waveshare.com/wiki/RP2040-Zero) programmed with Arduino IDE as at https://randomnerdtutorials.com/programming-raspberry-pi-pico-w-arduino-ide/ 

// RPi Zero -> RP2040
#define LED_PIN 15      // GP15 // matrixtpin
#define RTC_SDA 4       // GP4
#define RTC_SCL 5       // GP5
#define ONE_WIRE_BUS 14 // GP14 // DS18B20 pin
