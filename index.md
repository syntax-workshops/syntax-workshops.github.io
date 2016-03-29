---
layout: default
title: Domotica workshop
---

# Wat is het?

Misschien heb jij dat ook wel eens:
"ik wil iets maken, maar ik weet niet precies hoe".

Nu is je kans. De activiteitencommissie van Syntax presenteert: de domotica workshop verbrand-je-handen klus-a-thon!
Tijdens deze workshop gaan we twee projecten doen. Je mag kiezen welke je wilt maken. Alles kan, alles mag. :)

We bestellen met zijn allen de nodige onderdelen (of je bestelt ze zelf),
waarna we ze op **19 mei vanaf 17:00** gezamenlijk in elkaar zetten en testen op Hogeschool Leiden (lokaal tbd).

Het idee is dat iedereen met een werkende LED strip en/of domotica Pi naar huis gaat. Voor de workshop is geen ervaring
met solderen, elektronica, of programmeren vereist! Je hoeft alleen lid van Syntax te zijn. :)

De code, ontwerpen en instructies voor de projecten zijn allemaal open-source (MIT license),
dus kun je het aanpassen zoals je zelf wilt!

## Inschrijven

Je kunt jezelf aanmelden voor deze workshop via [dit Google form](http://goo.gl/forms/DyqEM4lcrh)!

## LED strip met WiFi

<a href="https://syntaxleiden.nl/static/workshop/jacek-led-strip.jpg"><img src="https://syntaxleiden.nl/static/workshop/jacek-led-strip.jpg" style="width: 30%; float: right;" /></a>

Voor dit project stuur je RGB LED strip aan op afstand over je netwerk. Hiermee kan je iedere LED een eigen kleur en sterkte geven! Regenboog animaties, het kan allemaal.

Het brein hierachter is de esp8266 chip. Deze microcontroller kost €2,50 en verbind met je wifi netwerk. Met open-source software die wij voor je geschreven hebben kun je deze besturen vanaf je smarthpone (iPhone en Android).

<a class="button" href="https://github.com/syntax-workshops">Ga naar project &rarr;</a>

<a href="https://syntaxleiden.nl/static/workshop/led-hond.gif"><img src="https://syntaxleiden.nl/static/workshop/led-hond.gif" style="width: 30%; float: right; clear: both;" /></a>

<div style="clear: both; width: 100%;"></div>

## Lampen besturen met je Raspberry Pi

Herken je dat? Je ligt in bed, wilt het licht uitzetten, maar niet je bed uit. IT moet voor jou werken, jij niet voor de IT!
Met de Raspberry Pi, die je waarschijnlijk al hebt, en een 433mhz zender kun je stopcontacten schakelen met een KlikAanKlikUit.
Net als ons liever lui dan moe? Deze workshop komt met een open-source app en serversoftware in Node.js voor op je Raspberry. Het is bijna plug en play.

<a href="https://syntaxleiden.nl/static/workshop/help-me.gif"><img src="https://syntaxleiden.nl/static/workshop/help-me.gif" style="width: 30%; float: right;" /></a>

<a class="button" href="https://github.com/syntax-workshops">Ga naar project &rarr;</a>

<div style="clear: both; width: 100%;"></div>

# Waar is het

We zullen de workshop houden op Hogeschool Leiden. Deze
beschikt over een werkplaats met alle soorten gereedschap die we nodig hebben.

# Wat moet ik hebben

Dit zijn de parts lists (bill of materials) die je nodig hebt voor de projecten.

## Lampen besturen

| Onderdeel                | Prijs NL | Prijs CN | Shop NL                                                                                  | Shop CN                                                                                                                                               |
|--------------------------|----------|----------|------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| Raspberry Pi 1 of hoger  | €27,95   | Nvt      | [SOS Solutions](https://www.sossolutions.nl/raspberry-pi/bordjes)                                         | Nvt                                                                                                                                                   |
| 433Mhz zender            | €5,95    | €0,56    | [Kiwi Electronics](https://www.kiwi-electronics.nl/433mhz-rf-link-kit)                                       | [AliExpress](http://www.aliexpress.com/item/RF-wireless-receiver-module-transmitter-module-board-super-regeneration-433MHZ-DC5V-ASK-OOK-1pair-2pcs/1620400987.html) |
| Jumper kabeltjes (F/F)   | €5,95    | €2,62    | [Kiwi Electronics](https://www.kiwi-electronics.nl/Premium-Jumperwires-40-stuks-op-strip-20cm-female-female) | [AliExpress](http://www.aliexpress.com/item/120pcs-20cm-male-male-male-female-and-female-jumper-wire-Dupont-cable-for-Arduino/1728903423.html)                      |
| KaKu/Action beginnersset | €22,49   | Nvt      | [Gamma](https://www.gamma.nl/assortiment/klikaanklikuit-schakelset-apa3-1500r/p/B364802) of [Action](http://www.action.nl/schakelset-afstandsbediening-4dlg-rand-aarde) | Nvt                                                                                                                                                   |

## LED strip met WiFi

| Onderdeel                    | Prijs NL | Prijs CN | Shop NL                                                                  | Shop CN                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|------------------------------|----------|----------|--------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| NodeMCU bordje               | €15,76   | €3,86    | [Antratek](https://www.antratek.nl/nodemcu-v2-lua-based-esp8266-development-kit)     | [AliExpress](http://www.aliexpress.com/item/V2-4M-4FLASH-NodeMcu-Lua-WIFI-Networking-development-board-Based-ESP8266/32448662166.html)                                                                                                                                                                                                                                                                                                                         |
| ws2812b LED strip 1m 30 ip30 | €16,95   | €4,43    | [Kiwi Electronics](https://www.kiwi-electronics.nl/digitale-rgb-ledstrip-ws2812b-30-led-1m)  | [AliExpress](http://www.aliexpress.com/item/1m-4m-5m-individually-addressable-waterproof-ip65-ip67-5050-rgb-30-60-144-led-m-5v/32351194166.html)                                                                                                                                                                                                                                                                                                               |
| 5v 3a voeding                | €17,95   | €3,95    | [AlleKabels](https://www.allekabels.nl/na/0/1307590/universele-ac-dc-adapter-5-v.html) | [AliExpress](http://www.aliexpress.com/item/Best-Price-UK-US-EU-Plug-Universal-AC-Adapter-Replacement-for-DC-5V-3A-Charger-Power/32298873894.html) |
| Perfboard                    | Nvt      | €5,06    | Nvt                                                                      | [AliExpress](http://www.aliexpress.com/item/20pcs-5x7-4x6-3x7-2x8-cm-Pcb-Double-Sided-Copper-Prototype-Universal-PCB-Board-for-Arduino/32327790171.html)                                                                                                                                                                                                                                                                                                       |
| Jumper kabeltjes (F/F)       | €5,95    | €2,62    | [Kiwi Electronics](https://www.kiwi-electronics.nl/Premium-Jumperwires-40-stuks-op-strip-20cm-female-female) | [AliExpress](http://www.aliexpress.com/item/120pcs-20cm-male-male-male-female-and-female-jumper-wire-Dupont-cable-for-Arduino/1728903423.html)                      |
| Male header pins             | €8,95    | €0,66    | [Kiwi Electronics](https://www.kiwi-electronics.nl/header-strip-40-pins)                     | [AliExpress](http://www.aliexpress.com/item/20pcs-Lot-Gold-plated-Single-Row-1x40-pin-2-54mm-Male-Header-Free-shipping-hot-sales/670908618.html)                                                                                                                                                                                                                                                                                                               |

## Gereedschap

De volgende gereedschappen zullen we gebruiken op de workshop. Wij zorgen dat
er van alles minstens iets aanwezig is, maar als je het hebt, neem het dan
vooral mee!

* Soldeerbout (breng er een mee!)
* Soldeertin
* Kniptang
* Multimeter

# Formulier onderdelen inkopen

Dit komt binnenkort!
