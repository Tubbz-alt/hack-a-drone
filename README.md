# Hack a Drone

- De [presentatie] slides


## Doelstellingen

- Uitpakken en opladen van de drone
- Initialiseren van de Java code
- Het besturen van de drone met je toetsenbord
- Automatische piloot programmeren met Java
- Wedstrijd met jouw drone tegen andere drones


## Benodigdheden

- Een drone
- Laptop met daarop geïnstalleerd:
  - Java
  - Maven
  - IDE
- Java code om de drone aan te sturen


## De drone

*Cheerson CX-10WD-TX*

- 2.4 GHz WiFi Remote Control
- 3.7 Volt 150 mAh
- 0.3 Mega Pixel Camera (640x480)
- Weight 18 gram
- Flying time 4–5 minutes
- Charging time 20–30 minutes


## Uitpakken en opladen van de drone

- Haal de drone uit de verpakking
- Laad de drone op via USB met de meegeleverde kabel
  - Het opladen duurt ongeveer 20 minuten
- Laat de drone nog even uitstaan!


## De Java code

- Maak verbinding met Ordina WiFi "Public"
  - Wachtwoord: GuestAccess2012
- Haal de Java code op van GitHub:
  - https://github.com/Ordina-JTech/hack-a-drone.git
- Initialiseer de Java code in jouw favoriete IDE


## Verbinding maken met de Drone

- Zet de drone aan
- Maak verbinding met de drone over WiFi
- Start de Java code op vanuit:
  - nl.ordina.jtech.hackadrone.gui.GUI


## Gebruik van de GUI
  
- Klik op "Connect" om verbinding met de drone te maken
- Klik op "Start Controls" om de toetsenbordbesturing in te schakelen
- Klik op "Start Camera" om de camera in te schakelen
- Klik op "Record Video" om een opname te maken
- Klik op "Start AI" om de automatische piloot te starten


## Het besturen van de Drone

- Gebruik de linker pijltjestoets om op te stijgen
- Gebruik de rechter pijltjestoets om te landen
- Gebruik de toetsen W en A om voor- of achteruit te gaan
- Gebruik de toetsen A en D om links of rechts te gaan
- Gebruik de toetsen Q en E om links- of rechtsom te draaien


## Uitbreiden van de drone

- Schrijf je eigen AI om de drone aan te sturen
- Maak jouw AI intelligent genoeg voor het wedstrijdparkour
- Gebruik hiervoor de basis Java code van de AI:
  - nl.ordina.jtech.hackadrone.core.AI


[presentatie]: https://ordina-jtech.github.io/hack-a-drone
