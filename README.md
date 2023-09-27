# RTCclock_RP2040_8x32leds
based on https://github.com/tehniq3/RTCclock_8x32leds/ and RP2040-zero (https://www.waveshare.com/wiki/RP2040-Zero) programmed with Arduino IDE as at https://randomnerdtutorials.com/programming-raspberry-pi-pico-w-arduino-ide/ 

article: https://nicuflorica.blogspot.com/2023/09/ceas-rtc-cu-rp2040-zero-pe-afisaj-8x32.html

// RPi Zero -> RP2040

#define LED_PIN 15      // GP15 // matrixtpin

#define RTC_SDA 4       // GP4

#define RTC_SCL 5       // GP5

#define ONE_WIRE_BUS 14 // GP14 // DS18B20 pin

![RP2040-Zero](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgzmPK0zdIuO4v8Fn4RUCzbbEVDbghPXANjEs6vOD09AZZmUdr1xvcByzLPj0XUOdRP5stzZvfufRa4lrd9c29UgcEjFW6YFKKvClgLl8HBS86RhIZ_PiRn6S1HQRR6jb5LZkDsb7KLxs_pJZDFT-tCjh7LE01ZEy7rHRvoYZtw6d8obB82wrDbNvbxV6FL/w200-h149/RP2040_RTC_DS18B20_info.jpg)
