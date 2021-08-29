# Pimoroni-11x7-LED-Matrix-Arduino
Arduino library for the Pimoroni 11x7 LED Matrix - https://shop.pimoroni.com/products/11x7-led-matrix-breakout

Based on the Adafruit IS31FL3731 Library modified for the 11x7 display.

# Wiring

Connect Vin to the power supply, 3-5V is fine. 

Use the same voltage that the microcontroller logic is based off of. For most Arduinos, that is 5V

Connect GND to common power/data ground

Connect the SCL pin to the I2C clock SCL pin on your Arduino. On an UNO & '328 based Arduino, this is also known as A5, on a Mega it is also known as digital 21 and on a Leonardo/Micro, digital 3

Connect the SDA pin to the I2C data SDA pin on your Arduino. On an UNO & '328 based Arduino, this is also known as A4, on a Mega it is also known as digital 20 and on a Leonardo/Micro, digital 2

![matrix](https://user-images.githubusercontent.com/25089739/131248972-e8523b3b-8469-4e9b-91ee-40e92dcedfeb.gif)


