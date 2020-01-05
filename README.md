# RFID_Using_HC-05
---------------------------------------------------------------------------
This sketch show a simple locking mechanism using the RC522 RFID module.
----------------------------------------------------------------------------
Typical pin layout used:
-----------------------------------------------------------------------------------------
            MFRC522      Arduino       Arduino   Arduino    Arduino          Arduino
            Reader/PCD   Uno           Mega      Nano v3    Leonardo/Micro   Pro Micro
Signal      Pin          Pin           Pin       Pin        Pin              Pin
-----------------------------------------------------------------------------------------
RST/Reset   RST          9             5         D9         RESET/ICSP-5     RST
SPI SS      SDA(SS)      10            53        D10        10               10
SPI MOSI    MOSI         11 / ICSP-4   51        D11        ICSP-4           16
SPI MISO    MISO         12 / ICSP-1   50        D12        ICSP-1           14
SPI SCK     SCK          13 / ICSP-3   52        D13        ICSP-3           15
-----------------------------------------------------------------------------------------
