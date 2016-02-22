# esp8266-stamode-udp
ESP8266 example - How to put ESP in STA mode (station mode, i.e. wifi client), receive data over UDP and forward it to UART

# Trivia
ESP8266 is a very nice and quite popular WiFi enabled SoC manufactured by Espressif. I have a plan to create several projects which will demonstrate and make use of most important functions / features / blocks / parts of this hardware. Code for ESP8266 can be developed in many ways, i.e. in Arduino IDE, as LUA scripts, as JavaScripts, using Espressif's native C libraries. Since I preffer to work as close to the hardware as possible, my choice is obviously last option, i.e. Espressif SDK.

# Prerequisites
To build this project you have to have build environment of course. Instead of developing a wheel, I would rather redirect you to someone who did it long before me. In this case I suggest and strongly recommend video tutorial made by Neil Kolban (known as nkolban here at GitHub).
Second obvious thing is a hardware which will be flashed with our newly build firmware. ESP8266 itself is rather hard to work with but fortunatelly it comes in a form of various small modules, e.g. ESP-01, ESP-07, ESP-12F, etc. These modules has additional chip on board - SPI memory. Thare are also simple development platforms available which are very handy to work with (have buttons on board, pin-headers available, UART chip, USB connector, LDO voltage regulator, etc.)
