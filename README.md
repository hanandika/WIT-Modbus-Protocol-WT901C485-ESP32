# WIT Modbus Protocol WT901C485 ESP32
 WIT WT901C485 Modbus on ESP32

 This user Serial2 pin on ESP32 to read / write to RS485 module

 <img width="100" alt="WT901C485" src="https://github.com/hanandika/WIT-Modbus-Protocol-WT901C485-ESP32/assets/22127514/3c3169f6-9624-4751-8f0e-3a67ccb23e7a">
 
 https://www.wit-motion.com/9-axis/witmotion-wt901c485-multi.html

## Serial TTL to RS485
 
 <img width="200" alt="SerialTTLtoRS485" src="https://github.com/hanandika/WIT-Modbus-Protocol-WT901C485-ESP32/assets/22127514/4bec7d51-3569-4209-89e2-82e3c275e949">
 
 https://www.tokopedia.com/alfaelectro/serial-ttl-to-rs485-converter-modul-automatic-overflow-type-a

 ## Wiring
 ``` 
  ESP32                SerialTTLtoRS485               WT901C485
   
  5V <---------------------> VCC <------------------> VCC
   
  GND <--------------------> GND <------------------> GND
  
                              A+ <------------------> A

                              B- <------------------> B

  TX2 <---------------------> TXD

  RX2 <---------------------> RXD
  
 ```
<img width="610" alt="Screenshot 2023-11-07 at 14 28 52" src="https://github.com/hanandika/WIT-Modbus-Protocol-WT901C485-ESP32/assets/22127514/cfba115a-e858-49c0-8375-148579ae608f">

## Libraries

rename folder to wit_c_sdk, and copy all wit_c_sdk.c , wit_c_sdk.h , REG.h into wit_c_sdk folder earlier

<img width="436" alt="Screenshot 2023-11-07 at 14 34 47" src="https://github.com/hanandika/WIT-Modbus-Protocol-WT901C485-ESP32/assets/22127514/1168ae0a-c557-4856-bbed-ff652a4da330">



## Serial Monitor
<img width="963" alt="Screenshot 2023-11-07 at 14 55 57" src="https://github.com/hanandika/WIT-Modbus-Protocol-WT901C485-ESP32/assets/22127514/6c7bb059-f907-4888-8956-41daae70822c">
