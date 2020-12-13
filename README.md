# Multiplayer-shooter
Ons game project

## To-do list
Zet hier taken neer die we van te voren niet hebben bedacht, maar alsnog gedaan moeten worden. Als je een taak gedaan hebt verander het kruisje in een vinkje en zet je naam erbij (je naam zet je erbij zodat anderen met vragen of probelemen over die taak weten bij wie ze moeten zijn). Als je bezig gaat met een taak zet naam in de "Wie?" kolom (zodat niet iedereen aan dezelfde taak werkt). Samenwerken met een andere an dezelfde taak kan, zet er dan 2 namen neer.

| Taak                                                      | Af?  | Gedaan door | Wie? (Alleen zelf invullen) |
|-----------------------------------------------------------|------|-------------| --------------------------- |
| Project toevoegen aan deze repo                           |  ✅  | Youri       |                             |
| Unreal Engine Multi User server opzetten                  |  ✅  | Youri       |                             |
| Herlaad functie maken                                     |  ✅  | Youri       |                             |
| Speler logica maken                                       |  ✅  | Youri       |                             |
| Mogelijkheid om speler info op te slaan toe voegen        |  ✅  | Youri       |  Youri                      |
| Mogelijkheid een speler naam in te voeren maken           |  ✅  | Youri       |                             |
| Basis map maken (een simpele versie voor development)     |  ❌  |             | Timon en Stijn
| Begin maken aan bots                                      |  ❌  |             | Youri (ik kan hulp gebruiken)
| Beginscherm mooi design maken                             |  ❌  |
| De logica achter het beginscherm maken                    |  ❌  |
| Assets voor de spelers maken/ opzoeken                    |  ❌  |
| Assets voor de bots (in stijl van robots) maken/ opzoeken |  ❌  |
| Recoil toevoegen aan wapens                               |  ✅  | Youri       | 
| Grenaten toevoegen aan speler                             |  ❌  |             | Wouter
| Grenaat gooi animatie(s) toevoegen                        |  ❌
| Random lopen als de bot de player niet ziet               |  ❌
| Heen en weer lopen tijdens schieten voor de bot           |  ❌
| Bot minstens 2000 afstand van player laten spawnen        |  ❌
<br><br/>

## Taakverdeling

| Taak                                                  | Timon | Stijn | Wouter | Youri |
|-------------------------------------------------------|-------|-------|--------|-------|
| Prototype voor het spel maken                         |       |       |        |   X   |
| Basis voor bots maken                                 |       |       |    X   |   X   |
| Basis map maken (een simpele versie voor development) |   X   |   X   |        |       |
| De binnen levelmap maken                              |   X   |   X   |        |       |
| Beginscherm design maken                              |   X   |   X   |        |       |
| Beginscherm logica erachter maken                     |       |       |    X   |   X   |
| 2e levelmap maken voor afwisseling (optioneel)        |   X   |   X   |        |       |
| Optie voor eigen levelmap toevoegen maken (optioneel) |       |       |    X   |   X   |
| Basis voor multiplayer (optioneel)                    |       |       |        |   X   |

<br><br/>

## Github dekstop
Voor het downloaden van het project en het uploaden van jouw wijzigingen naar deze repo (de multi user plugin is nog in beta en werkt nog niet perfect, daarom gebruiken we deze repo als backup) raad ik [Github desktop](https://desktop.github.com) aan.

## Mark down cheatsheet
[Hier](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) vind je een cheatsheet voor mark down (.md).

## Multi User 
Multi user server is online, maar je hebt wel een VPN verbiding nodig. Volg de stappen hiervoor hieronder:
1. Download nieuwste versie van het project vanaf hier

2. [OpenVPN client opzetten](https://openvpn.net/client-connect-vpn-for-windows/)
   OpenVPN configuratie (vpn.ovpn) bestand staat hier

3. [Multi User plugin installeren in het project](https://docs.unrealengine.com/en-US/Engine/Editor/MultiUser/QuickStart/index.html)

4. Als de Multi User plugin geinstalleerd is dan “10.11.100.12:6666” toevoeen aan “static endpoint” onder  “Edit > Project Settings > Plugins > UDP Messaging”

5. Verbinden met de sessie zoals in de [quickstart](https://docs.unrealengine.com/en-US/Engine/Editor/MultiUser/QuickStart/index.html) staat

Als het niet lukt, vraag mij dan om hulp

## Enviorments en assets
- https://www.youtube.com/watch?v=J-zJwzMTdLY
- https://www.youtube.com/watch?v=t7jvPz56mxM
- [LAVIFV](https://unrealengine.com/marketplace/en-US/product/lavifv-infantry-fighting-vehicle)
- [Modular Sci-Fi season 2 environment](https://unrealengine.com/marketplace/en-US/product/modular-scifi-season-2-starter-bundle)
- [Mech TL-22](https://sketchfab.com/3d-models/mech-tl-22-2694c68765aa4f67ab81a259ff39d654)
- [Robots hard bone](https://sketchfab.com/3d-models/robots-hard-borne-167fcf37ad404e5ca0b06b4588d3eea5)
- [Terminator T800](https://sketchfab.com/3d-models/terminator-t-800-dd9b3744c30e4bf58aa6f57da00c1eb0)
- [Drone concept](https://sketchfab.com/3d-models/drone-concept-cde78a97ce3d4882b68463e4fb821d8b)
- [Military Drone](https://sketchfab.com/3d-models/military-suppression-drone-rsd-1-droid-19994e164a0d4ba082230d98fcf58b44)
- [Realistic Forest Pack](https://www.unrealengine.com/marketplace/en-US/product/realistic-forest-pack)
- [Procedural Nature Pack](https://www.unrealengine.com/marketplace/en-US/product/procedural-nature-pack-vol)
