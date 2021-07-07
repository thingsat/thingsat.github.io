# Thingsat :: LoRa benchmarks from cubesat

## Aims
* Benchmarking LoRa links over very long distance (> 500 kms) for several frequency bands (868MHz, 2.4GHz).
* Repeating LoRa frames of ground LoRaWAN trackers (emergency usecase).
* Designing and evaluating  LoRa delay-tolerant networks algorithms.
* Studying frames of ground LoRaWAN endpoints from the space.
* Synchronizing ground LoRaWAN endpoints from the space.
* Monitoring with sensors in real field cases : artic glaciers, helium containers, fish farms ...

![Delay Tolerant Network](https://gricad-gitlab.univ-grenoble-alpes.fr/thingsat/public/-/raw/master/cubesat_mission/media/thingsat-dtn.png)

## LoRa communication payload onboard of Stork 1 mission. 

The CSUG designs a LoRa communication board and antenna for cubesats. The board and the antenna are hosted by the [SatRevolution's Stork mission](https://satrevolution.com/products/stork-mission/).
The board embeds one [Semtech SX1302 concentrator](https://www.semtech.com/products/wireless-rf/lora-gateways/sx1302) for communications on the 863-870 MHz band and one [Semtech SX1280 transceiver](https://www.semtech.com/products/wireless-rf/24-ghz-transceivers/sx1280) for communications on the 2400-2500 MHz band. The firmware of the two STM32 MCUs is developed with [RIOT OS](https://github.com/RIOT-OS/RIOT).

## Ground segment
Coming soon

Thingsat is registered on [TinyGS](https://tinygs.com/satellite/ThingSat)

### TinyGS ground stations
Search `CSUG` at https://tinygs.com/stations

Current gateways @ [CSUG](https://www.csug.fr/) are:
* [CSUG_01_Heltec868](https://tinygs.com/station/CSUG_02_Heltec868@1830594236)
* [CSUG_02_Heltec868](https://tinygs.com/station/CSUG_01_Heltec868@1830594236)

Coming soon:
* [ESP32 Vroom + Lambda80/E28 2.4GHz LoRa module](https://github.com/thingsat/tinygs_2g4station)

## Partners
[Université Grenoble Alpes](https://www.univ-grenoble-alpes.fr/) ([CSUG](https://www.csug.fr/), [OSUG](https://www.osug.fr/), [LIG](https://www.liglab.fr/), [IMEP-LaHC](https://imep-lahc.grenoble-inp.fr/)), [Université Polynésie Française](https://www.upf.pf/fr), [Institut Polaire Paul Emile Victor (IPEV)](https://www.institut-polaire.fr/ipev-en/the-institute/), [SpaceAble](https://spaceable.org/), [Air Liquide](https://www.airliquide.com/fr), [Gorgy Timing](https://www.gorgy-timing.fr/), [Galathea](https://www.galatea.io/).

Special thanks to [ANS Innovation](https://www.ans-innovation.fr/), [Semtech](https://www.semtech.com/), [Chipselect](http://chipselect.fr/), [ST Microelectronics](https://www.st.com/content/st_com/en.html), [Strataggem](https://www.strataggem.com/), [RIOTOS team](https://www.riot-os.org/), [CNES](https://cnes.fr/en), [RESA](http://www.resa-spatiales.com/?lang=en), [Synergie Concept](http://www.synergie-concept.fr/), [Nicomatic](https://www.nicomatic.com/), [Rogers Corp](https://rogerscorp.com/) for their help.

## Test fields
* Glaciers monitoring (French Alps & Ny Alesund, Svalbard)
* Fish farming (French Polynesia)
* Secure clock synchronization (World)
* Helium bottle maritime shipping (Oceans)

## Frequencies
Frequencies are currently requested to [IARU](https://www.iaru.org/) and [ITU](https://www.itu.int/) for eu868 and ism2400 bands.

## Gallery
![Thingsat board](https://gricad-gitlab.univ-grenoble-alpes.fr/thingsat/public/-/raw/master/cubesat_mission/media/thingsat-annotated-fm-board.jpg)
![Thingsat antenna](https://gricad-gitlab.univ-grenoble-alpes.fr/thingsat/public/-/raw/master/cubesat_mission/media/thingsat-antenna.png)
![Stork mission](https://gricad-gitlab.univ-grenoble-alpes.fr/thingsat/public/-/raw/master/cubesat_mission/media/stork-1.png)


Photo credits: [CSUG](https://www.csug.fr/), [SatRevolution](https://satrevolution.com/).
