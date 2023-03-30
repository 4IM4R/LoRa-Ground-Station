# LoRa Lurreko Estazioa

Proiektu hau honako proiektuetan oinarritua izan da:
  - "Ground station for LoRa satellites" by [alberto nunez](https://hackaday.io/project/186243-ground-station-for-lora-satellites)
  - [TinyGS](https://github.com/G4lile0/tinyGS)
  
Beharrezko materiala:
  - TTGO LORA32 ESP32 433MHz bertsioa
  - RP-SMA flange to U.FL pigtail (10cm)
  - 100x68x50mm waterproof “Sonoff” kaxa
  - 18650 3,7V pila rekargablea eta pila euskarria
  - TP4056 karga kudeatzailea
  - 2.54mm konektore emea
  - PCB konektorea Screw terminal kf350 3.5mm 2 pin
  - MCP1700-3302E tentsio erregulatzailea
  - 1uF kondentsagailu elektrolitikoa
  - 100nF film kondentsagailua
  - Plaka fotoboltaikoa
  
 ![alt text](images/Components.png)

Eguneratu behar da => Electronic design:
  [Proteus project file](https://github.com/4IM4R/LoRa-Ground-Station/blob/e2a53dc4b7f0d562ad7ddc52352c304cba657683/proteus/LoRa_GS.pdsprj)
  
  Eguneratu behar da => Schematic:

![alt text](images/Schematic.png)

  Eguneratu behar da => PCB layout:

![alt text](images/PCB_layout.png)

Softwarearen insatalazioa:
  - Jarraitu ondorengo estekako [argibideak](https://github.com/G4lile0/tinyGS/wiki/Quick-Start)
  
Konfigurazioa:
  - Jarraitu ondorengo estekako [argibideak](https://github.com/G4lile0/tinyGS/wiki/Ground-Station-configuration)
  - Estazioaren konfigurazioa burutu eta gero, Telegrameko bot pertsonalaren bidez web-login tokena sortu (TinyGS Personal Bot txatean /weblogin idatziz)
  ![alt text](images/weblogin.png)
  - Sortuko den esteka ireki eta bertan ondorengo aldaketak egin:
  - "Edit Station" atalean sartu eta antena mota eta funtzionamendu frenkuentzia eremua aukeratu. Nahi izan ezkero estazioaren argazki bat ere gehitu daiteke. Aldaketak gorde
![alt text](images/Edit_station.png)
  - "Operate" atalean sartu eta "Auto Tune" atalean Enabled 433 aukeratu (garrantzitsua da estazioak sateliteen seinalea behar bezala jasotzeko). Aldaketak gorde
![alt text](images/Operate.png)
  - Behin aldaketak gorde eta gero, saioa itxi eta hasierako konfigurazioa egin den lekutik (estazioaren IP-a nabigatzailean idatziz), estazioa berrabiaraztea komenigarria da "Restart station" aukeratuz
![alt text](images/TinyGS_dashboard.png)
  
  
