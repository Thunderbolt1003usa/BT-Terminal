This is an Arduino Project to Display varios Text with your phone via Bluetooth on an 128x64 px 0.96 inch OLED Display.
You need to use "Serial Bluetooth Terminal" on your Phone. Then you need to connect to "HC 05" and then you can type in "Serial Bluetooth Terminal" various Text and it will be displayed!
Needed Libraries: Adafruit_SSD1306.h ,Adafruit_GFX.h and Wire.h.
All .bmp are included as binaries in the code. Needed components: hc05  BT module ,i2C 0.96 128x64 oled display and an arduino nano.
Wiring:

    Arduino Nano <-> I2C Display:

    A4 (SDA) <-> SDA pin on the display
    A5 (SCL) <-> SCL pin on the display
    5V <-> VCC pin on the display
    GND <-> GND pin on the display

    Arduino Nano <-> HC-05 Bluetooth Module:

    TX <-> RX pin on the HC-05 Bluetooth module
    RX <-> TX pin on the HC-05 Bluetooth module
    5V <-> VCC pin on the HC-05 Bluetooth module
    GND <-> GND pin on the HC-05 Bluetooth module

If you have questions or Problems just write an "Issue".
