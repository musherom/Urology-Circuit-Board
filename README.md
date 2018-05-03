# Urology-Circuit-Board
California Plug Load Research Center (CalPlug)  This is the second version of Urology Project. 
Electrical design Schematic is designed and revised by Urology project Team leaders(Sean Santarsiero, Lifeng Liang) under supervising of Michael Klopfer. 
This is the alternative version of Schematic and Layout using Altium Designer Software by Lifeng Liang

This verson features two circuit boards and additional features from upgraded hardware such as the ESP 32 WROVER. 
The essential features of this device is a force sensor, battery management system with a guage, on board FTDI, LED indicators,
throw switch, tare button, current sync with LED bar, piezo sound generator, 3V3 Regulator/Boost and WiFi/BLE.
The reason we decided to use the ESP32 WROVER was to allow for an antenna extension to be plugged into the processor.
Our case needed to be metal to follow medical equipment guidelines and this required us to have an external antenna. 
This project has two circuit boards.  The top board is designated for all user interface controls in order to reduce 
wire connections to bottom board. The bottom board is the brains of the entire circuitry. We have made code upload
possible through USB. In addition, charging the LiPo battery is possible through USB input. To keep connections clean, 
JST connectors were used connect boards.  This is a team project with CalPlug researchers.
