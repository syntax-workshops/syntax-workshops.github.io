---
layout: default
title: How-to: LED strip aansturen met esp8266
---

# Doel van het project

Bij dit project stuur je een RGB LED strip (ws2812b) aan met een Nodemcu microcontroller (gebaseerd op de esp8266 SoC). De LED strip is een lange strook met felle LED's erop, die je *individueel* in een willekeurige kleur kunt laten schijnen.

De Nodemcu beschikt over wifi, waardoor je de LED strip met een (open-source) smartphone app kunt besturen.

Het is ook mogelijk om een fysiek bedieningspaneel te bouwen voor de strip. Maar om het simpel te houden beperkt deze workshop zich tot de app.

# Inhoudsopgave

* [Over de esp8266](#over-de-esp8266)
* [Hardware](#hardware)
  * [Aansluiten](#aansluiten)
* [Software](#software)
  * [Firmware flashen](#aansluiten)
  * [Espixel installeren](#)
  * [Aansturen via Python](#)
  * [iOS app installeren](#)
  * [Android app installeren](#)

# Over de esp8266

De esp8266 is een microcontroller die in 2014 is uitgebracht door Espressif Systems. Het is een betaalbare module, ontworpen om elektronica eenvoudig met het internet te verbinden (*internet of things*).
Het kan net als een Arduino geprogrammeerd worden in C met de Arduino IDE. Ook is er een Nodemcu firmware die gebaseerd is op Lua. Hiermee kun je de module programmeren met Lua scripts.

De belangrijkste features die het biedt zijn:

* Ingebouwde WiFi en een netwerk stack
* 12 GPIO (general purpose input/output) pins
* ADC (analog to digital converter) pin
* 4Mb flash geheugen

# Hardware

In deze handleiding gebruiken we de Nodemcu developer kit. Dit apparaatje voegt nuttige functionaliteit toe aan een "kale" esp-12e module, namelijk een micro-USB aansluiting, 5 volt regulator en een on-board programmer.
Hierdoor heb je geen losse USB FTDI of *voltage regulator* nodig.

De pin aansluitingen op de module zijn als volgt:

![Pin definitie van de nodemcu. [Bron](#)](nodemcu_devkit_v1.0_pinmap.png)

## Onderdelen

Kopiëren van BOM

### Voeding

De esp8266 gebruikt weinig stroom; maximaal 400 mA (milliampere) op 3,3 volt.

De LED strip is echter zeer hongerig voor stroom.

## Aansluiten

**TODO**: Schematics voor het aansluiten

# Software

Je hebt twee opties om je module te programmeren:

* C (met Arduino API's)
* Lua (met nodemcu API's)

Voor de workshop gebruiken we Lua, omdat dit aanzienlijk makkelijker is om mee te beginnen dan C.

C is echter een uitstekende keuze als je meer of complexere code wilt dan met Nodemcu Lua mogelijk is.

## Firmware flashen

TODO: Esptool, luatool

## Espixel installeren

TODO

## Aansturen via Python

```python
# add code here
```

## iOS app installeren

Voor dit project is een open-source app gebouwd door Mathijs. Bekijk de source code en instructies [hier](#)

## Android app installeren

Voor dit project is een open-source app gebouwd door Mathijs. Bekijk de source code en instructies [hier](#)

# Resources

## Handige software tools

* Flashen van je firmware: https://github.com/themadinventor/esptool
* Uploaden van lua code: https://github.com/4refr0nt/luatool

## Hardware specificaties

* Nodemcu dev kit specificiaties: https://github.com/nodemcu/nodemcu-devkit-v1.0

## API Documentatie

* Nodemcu docs: http://nodemcu.readthedocs.org/en/dev/en/upload/
