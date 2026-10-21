# LoxBerry-Plugins Musterprojekt

Eine gemeinsame Loxone-Config-Projektdatei mit je einer Seite pro LoxBerry-Plugin. Jede Seite zeigt die Bausteine aus dem Reiter „Einbindung in Loxone“ des Plugins, fertig verbunden.

## Inhalt

| Datei | Zweck |
|---|---|
| `LoxBerry-Plugins_Musterprojekt.Loxone` | Projektdatei (Loxone Config 17.2), eine Seite je Plugin |
| `vorlagen/*.xml` | Vorlagen für „Virtuelle HTTP-Eingänge“ und „Virtuelle Ausgänge“, die die Seiten benutzen (Werte über das MQTT-Gateway brauchen keine Vorlage, siehe unten) |
| `bilder/einbindung_<plugin>.png` | Bild jeder Seite, wie es im Reiter „Einbindung in Loxone“ erscheint |

## Seiten

| Seite | Plugin |
|---|---|
| Abfahrtsassistent | [LoxBerry-Plugin-Abfahrtsassistent](https://github.com/timanders22/LoxBerry-Plugin-Abfahrtsassistent) |
| Alexa NG | [LoxBerry-Plugin-Alexa-NG](https://github.com/timanders22/LoxBerry-Plugin-Alexa-NG) |
| Alexa NG Radio | [LoxBerry-Plugin-Alexa-NG](https://github.com/timanders22/LoxBerry-Plugin-Alexa-NG) |
| Alexa NG Lampen | [LoxBerry-Plugin-Alexa-NG](https://github.com/timanders22/LoxBerry-Plugin-Alexa-NG) |
| AnkerSolix | [LoxBerry-Plugin-AnkerSolix](https://github.com/timanders22/LoxBerry-Plugin-AnkerSolix) |
| AnkerSolix Steuerung | [LoxBerry-Plugin-AnkerSolix](https://github.com/timanders22/LoxBerry-Plugin-AnkerSolix) |
| APC-UPS NG | [LoxBerry-Plugin-APC-UPS](https://github.com/timanders22/LoxBerry-Plugin-APC-UPS) |
| APC-UPS NG Akku und Netz | [LoxBerry-Plugin-APC-UPS](https://github.com/timanders22/LoxBerry-Plugin-APC-UPS) |
| BatterieBMS | [LoxBerry-Plugin-BatterieBMS](https://github.com/timanders22/LoxBerry-Plugin-BatterieBMS) |
| BatterieBMS Spotpreis-Laden | [LoxBerry-Plugin-BatterieBMS](https://github.com/timanders22/LoxBerry-Plugin-BatterieBMS) |
| Beschattungswächter | [LoxBerry-Plugin-Beschattungswaechter](https://github.com/timanders22/LoxBerry-Plugin-Beschattungswaechter) |
| Bewässerung | [LoxBerry-Plugin-Bewaesserung](https://github.com/timanders22/LoxBerry-Plugin-Bewaesserung) |
| Bewässerung Zonen | [LoxBerry-Plugin-Bewaesserung](https://github.com/timanders22/LoxBerry-Plugin-Bewaesserung) |
| Chromecast4lox | [LoxBerry-Plugin-Chromecast4lox](https://github.com/timanders22/LoxBerry-Plugin-Chromecast4lox) |
| Chromecast4lox Steuerung | [LoxBerry-Plugin-Chromecast4lox](https://github.com/timanders22/LoxBerry-Plugin-Chromecast4lox) |
| Dashboard | [LoxBerry-Plugin-Dashboard](https://github.com/timanders22/LoxBerry-Plugin-Dashboard) |
| Dashboard Steuerung | [LoxBerry-Plugin-Dashboard](https://github.com/timanders22/LoxBerry-Plugin-Dashboard) |
| Docker NG | [LoxBerry-Plugin-Docker-NG](https://github.com/timanders22/LoxBerry-Plugin-Docker-NG) |
| Ecowitt-Weiche | [LoxBerry-Plugin-Ecowitt-Weiche](https://github.com/timanders22/LoxBerry-Plugin-Ecowitt-Weiche) |
| Ecowitt-Weiche Wetterwerte | [LoxBerry-Plugin-Ecowitt-Weiche](https://github.com/timanders22/LoxBerry-Plugin-Ecowitt-Weiche) |
| Ecowitt-Weiche Batterien | [LoxBerry-Plugin-Ecowitt-Weiche](https://github.com/timanders22/LoxBerry-Plugin-Ecowitt-Weiche) |
| Einspeisebremse | [LoxBerry-Plugin-Einspeisebremse](https://github.com/timanders22/LoxBerry-Plugin-Einspeisebremse) |
| Einspeisebremse Speicher | [LoxBerry-Plugin-Einspeisebremse](https://github.com/timanders22/LoxBerry-Plugin-Einspeisebremse) |
| EVCC | [LoxBerry-Plugin-EVCC](https://github.com/timanders22/LoxBerry-Plugin-EVCC) |
| EVCC Ladepunkt 1 | [LoxBerry-Plugin-EVCC](https://github.com/timanders22/LoxBerry-Plugin-EVCC) |
| EVCC Steuerung | [LoxBerry-Plugin-EVCC](https://github.com/timanders22/LoxBerry-Plugin-EVCC) |
| EVCC Hausspeicher und Tarif | [LoxBerry-Plugin-EVCC](https://github.com/timanders22/LoxBerry-Plugin-EVCC) |
| Fensterbilanz | [LoxBerry-Plugin-Beschattung_Fensterbilanz](https://github.com/timanders22/LoxBerry-Plugin-Beschattung_Fensterbilanz) |
| Fensterbilanz Messwerte | [LoxBerry-Plugin-Beschattung_Fensterbilanz](https://github.com/timanders22/LoxBerry-Plugin-Beschattung_Fensterbilanz) |
| Fensterbilanz Werte | [LoxBerry-Plugin-Beschattung_Fensterbilanz](https://github.com/timanders22/LoxBerry-Plugin-Beschattung_Fensterbilanz) |
| Funkwacht | [LoxBerry-Plugin-Funkwacht](https://github.com/timanders22/LoxBerry-Plugin-Funkwacht) |
| Funkwacht Sticks | [LoxBerry-Plugin-Funkwacht](https://github.com/timanders22/LoxBerry-Plugin-Funkwacht) |
| Funkwacht Steuerung | [LoxBerry-Plugin-Funkwacht](https://github.com/timanders22/LoxBerry-Plugin-Funkwacht) |
| Heimkino | [LoxBerry-Plugin-Heimkino](https://github.com/timanders22/LoxBerry-Plugin-Heimkino) |
| Heimkino Steuerung | [LoxBerry-Plugin-Heimkino](https://github.com/timanders22/LoxBerry-Plugin-Heimkino) |
| Heimkino Geräte | [LoxBerry-Plugin-Heimkino](https://github.com/timanders22/LoxBerry-Plugin-Heimkino) |
| Heimkino Bild und Ton | [LoxBerry-Plugin-Heimkino](https://github.com/timanders22/LoxBerry-Plugin-Heimkino) |
| Kodi-NG | [LoxBerry-Plugin-KODI-NG](https://github.com/timanders22/LoxBerry-Plugin-KODI-NG) |
| Kodi-NG Fernbedienung | [LoxBerry-Plugin-KODI-NG](https://github.com/timanders22/LoxBerry-Plugin-KODI-NG) |
| Kodi-NG Wiedergabe | [LoxBerry-Plugin-KODI-NG](https://github.com/timanders22/LoxBerry-Plugin-KODI-NG) |
| Pumpenwacht | [LoxBerry-Plugin-Pumpenwacht](https://github.com/timanders22/LoxBerry-Plugin-Pumpenwacht) |
| Pumpenwacht Betrieb | [LoxBerry-Plugin-Pumpenwacht](https://github.com/timanders22/LoxBerry-Plugin-Pumpenwacht) |
| Raumklima | [LoxBerry-Plugin-Raumklima](https://github.com/timanders22/LoxBerry-Plugin-Raumklima) |
| Raumklima 2 | [LoxBerry-Plugin-Raumklima](https://github.com/timanders22/LoxBerry-Plugin-Raumklima) |
| Raumklima Werte | [LoxBerry-Plugin-Raumklima](https://github.com/timanders22/LoxBerry-Plugin-Raumklima) |
| Raumklima Lüften und Kühlen | [LoxBerry-Plugin-Raumklima](https://github.com/timanders22/LoxBerry-Plugin-Raumklima) |
| Robonect | [LoxBerry-Plugin-Robonect](https://github.com/timanders22/LoxBerry-Plugin-Robonect) |
| Robonect Steuerung | [LoxBerry-Plugin-Robonect](https://github.com/timanders22/LoxBerry-Plugin-Robonect) |
| Saugroboter | [LoxBerry-Plugin-Saugroboter-Valetudo](https://github.com/timanders22/LoxBerry-Plugin-Saugroboter-Valetudo) |
| Saugroboter Steuerung | [LoxBerry-Plugin-Saugroboter-Valetudo](https://github.com/timanders22/LoxBerry-Plugin-Saugroboter-Valetudo) |
| Saugroboter Wartung | [LoxBerry-Plugin-Saugroboter-Valetudo](https://github.com/timanders22/LoxBerry-Plugin-Saugroboter-Valetudo) |
| Smartmeter klassisch | [LoxBerry-Plugin-Smartmeter-classic](https://github.com/timanders22/LoxBerry-Plugin-Smartmeter-classic) |
| Smartmeter Kosten und Fahrplan | [LoxBerry-Plugin-Smartmeter-classic](https://github.com/timanders22/LoxBerry-Plugin-Smartmeter-classic) |
| Smartmeter vzLogger | [LoxBerry-Plugin-Smartmeter-classic](https://github.com/timanders22/LoxBerry-Plugin-Smartmeter-classic) |
| Ultraschall | [LoxBerry-Plugin-Ultraschall](https://github.com/timanders22/LoxBerry-Plugin-Ultraschall) |
| WaermepumpeCloud | [LoxBerry-Plugin-WaermepumpeCloud](https://github.com/timanders22/LoxBerry-Plugin-WaermepumpeCloud) |
| WaermepumpeCloud Ausfall | [LoxBerry-Plugin-WaermepumpeCloud](https://github.com/timanders22/LoxBerry-Plugin-WaermepumpeCloud) |
| WaermepumpeCloud Werte | [LoxBerry-Plugin-WaermepumpeCloud](https://github.com/timanders22/LoxBerry-Plugin-WaermepumpeCloud) |
| WiFi-Scanner-NG | [LoxBerry-Plugin-WiFi-Scanner-NG](https://github.com/timanders22/LoxBerry-Plugin-WiFi-Scanner-NG) |
| Zendure SolarFlow | [LoxBerry-Plugin-ZendureSolarFlow](https://github.com/timanders22/LoxBerry-Plugin-ZendureSolarFlow) |
| Zendure SolarFlow Steuerung | [LoxBerry-Plugin-ZendureSolarFlow](https://github.com/timanders22/LoxBerry-Plugin-ZendureSolarFlow) |
| Zigbee2MqttNG | [LoxBerry-Plugin-Zigbee2MqttNG](https://github.com/timanders22/LoxBerry-Plugin-Zigbee2MqttNG) |
| Zigbee2MqttNG Geräte | [LoxBerry-Plugin-Zigbee2MqttNG](https://github.com/timanders22/LoxBerry-Plugin-Zigbee2MqttNG) |
| Spotpreis aWATTar | [LoxBerry-Plugin-Spotpreis-aWATTar](https://github.com/timanders22/LoxBerry-Plugin-Spotpreis-aWATTar) |
| Spotpreis aWATTar Steuerung | [LoxBerry-Plugin-Spotpreis-aWATTar](https://github.com/timanders22/LoxBerry-Plugin-Spotpreis-aWATTar) |
| Spotpreis aWATTar Werte | [LoxBerry-Plugin-Spotpreis-aWATTar](https://github.com/timanders22/LoxBerry-Plugin-Spotpreis-aWATTar) |
| Spotpreis aWATTar Freigaben und Tarif | [LoxBerry-Plugin-Spotpreis-aWATTar](https://github.com/timanders22/LoxBerry-Plugin-Spotpreis-aWATTar) |
| Spotpreis aWATTar Stundenprofil | [LoxBerry-Plugin-Spotpreis-aWATTar](https://github.com/timanders22/LoxBerry-Plugin-Spotpreis-aWATTar) |
| Spotpreis Octopus | [LoxBerry-Plugin-Spotpreis-Octopus](https://github.com/timanders22/LoxBerry-Plugin-Spotpreis-Octopus) |
| Spotpreis Octopus Steuerung | [LoxBerry-Plugin-Spotpreis-Octopus](https://github.com/timanders22/LoxBerry-Plugin-Spotpreis-Octopus) |
| Spotpreis Octopus Werte | [LoxBerry-Plugin-Spotpreis-Octopus](https://github.com/timanders22/LoxBerry-Plugin-Spotpreis-Octopus) |
| Spotpreis Octopus Freigaben und Tarif | [LoxBerry-Plugin-Spotpreis-Octopus](https://github.com/timanders22/LoxBerry-Plugin-Spotpreis-Octopus) |
| Spotpreis Octopus Stundenprofil | [LoxBerry-Plugin-Spotpreis-Octopus](https://github.com/timanders22/LoxBerry-Plugin-Spotpreis-Octopus) |
| Spotpreis Tibber | [LoxBerry-Plugin-Spotpreis-Tibber](https://github.com/timanders22/LoxBerry-Plugin-Spotpreis-Tibber) |
| Spotpreis Tibber Steuerung | [LoxBerry-Plugin-Spotpreis-Tibber](https://github.com/timanders22/LoxBerry-Plugin-Spotpreis-Tibber) |
| Spotpreis Tibber Werte | [LoxBerry-Plugin-Spotpreis-Tibber](https://github.com/timanders22/LoxBerry-Plugin-Spotpreis-Tibber) |
| Spotpreis Tibber Verbrauch | [LoxBerry-Plugin-Spotpreis-Tibber](https://github.com/timanders22/LoxBerry-Plugin-Spotpreis-Tibber) |
| Spotpreis Tibber Stundenprofil | [LoxBerry-Plugin-Spotpreis-Tibber](https://github.com/timanders22/LoxBerry-Plugin-Spotpreis-Tibber) |
| Marstek Venus E | [LoxBerry-Plugin-MarstekVenus](https://github.com/timanders22/LoxBerry-Plugin-MarstekVenus) |
| Marstek Venus E Steuerung | [LoxBerry-Plugin-MarstekVenus](https://github.com/timanders22/LoxBerry-Plugin-MarstekVenus) |
| Marstek Venus E Werte | [LoxBerry-Plugin-MarstekVenus](https://github.com/timanders22/LoxBerry-Plugin-MarstekVenus) |
| Weissware | [LoxBerry-Plugin-Weissware](https://github.com/timanders22/LoxBerry-Plugin-Weissware) |
| Weissware PV-Start | [LoxBerry-Plugin-Weissware](https://github.com/timanders22/LoxBerry-Plugin-Weissware) |
| Weissware Steuerung und Verbrauch | [LoxBerry-Plugin-Weissware](https://github.com/timanders22/LoxBerry-Plugin-Weissware) |
| AudiConnect | [LoxBerry-Plugin-AudiConnect](https://github.com/timanders22/LoxBerry-Plugin-AudiConnect) |
| AudiConnect Laden | [LoxBerry-Plugin-AudiConnect](https://github.com/timanders22/LoxBerry-Plugin-AudiConnect) |
| AudiConnect Klima und Befehle | [LoxBerry-Plugin-AudiConnect](https://github.com/timanders22/LoxBerry-Plugin-AudiConnect) |
| AudiConnect Fahrzeug | [LoxBerry-Plugin-AudiConnect](https://github.com/timanders22/LoxBerry-Plugin-AudiConnect) |
| BYD Autos | [LoxBerry-Plugin-BYD-Autos](https://github.com/timanders22/LoxBerry-Plugin-BYD-Autos) |
| BYD Autos Laden und Klima | [LoxBerry-Plugin-BYD-Autos](https://github.com/timanders22/LoxBerry-Plugin-BYD-Autos) |
| BYD Autos Fahrzeug | [LoxBerry-Plugin-BYD-Autos](https://github.com/timanders22/LoxBerry-Plugin-BYD-Autos) |
| BYD Autos Werte | [LoxBerry-Plugin-BYD-Autos](https://github.com/timanders22/LoxBerry-Plugin-BYD-Autos) |
| Renault NG | [LoxBerry-Plugin-Renault-NG](https://github.com/timanders22/LoxBerry-Plugin-Renault-NG) |
| Renault NG Laden und Klima | [LoxBerry-Plugin-Renault-NG](https://github.com/timanders22/LoxBerry-Plugin-Renault-NG) |
| Renault NG Fahrzeug | [LoxBerry-Plugin-Renault-NG](https://github.com/timanders22/LoxBerry-Plugin-Renault-NG) |
| Skoda-Connect-NG | [LoxBerry-Plugin-Skoda-Connect-NG](https://github.com/timanders22/LoxBerry-Plugin-Skoda-Connect-NG) |
| Skoda-Connect-NG Laden | [LoxBerry-Plugin-Skoda-Connect-NG](https://github.com/timanders22/LoxBerry-Plugin-Skoda-Connect-NG) |
| Skoda-Connect-NG Klima und Befehle | [LoxBerry-Plugin-Skoda-Connect-NG](https://github.com/timanders22/LoxBerry-Plugin-Skoda-Connect-NG) |
| Skoda-Connect-NG Fahrzeug | [LoxBerry-Plugin-Skoda-Connect-NG](https://github.com/timanders22/LoxBerry-Plugin-Skoda-Connect-NG) |
| VolkswagenID | [LoxBerry-Plugin-VolkswagenID](https://github.com/timanders22/LoxBerry-Plugin-VolkswagenID) |
| VolkswagenID Laden | [LoxBerry-Plugin-VolkswagenID](https://github.com/timanders22/LoxBerry-Plugin-VolkswagenID) |
| VolkswagenID Klima und Befehle | [LoxBerry-Plugin-VolkswagenID](https://github.com/timanders22/LoxBerry-Plugin-VolkswagenID) |
| VolkswagenID Fahrzeug | [LoxBerry-Plugin-VolkswagenID](https://github.com/timanders22/LoxBerry-Plugin-VolkswagenID) |
| LoxBerry MQTT-Gateway | alle Plugins mit MQTT (Neusenden nach Neustart) |
| Abfuhrkalender | [LoxBerry-Plugin-AWM-Abfuhr](https://github.com/timanders22/LoxBerry-Plugin-AWM-Abfuhr) |
| Abfuhrkalender Tonnen | [LoxBerry-Plugin-AWM-Abfuhr](https://github.com/timanders22/LoxBerry-Plugin-AWM-Abfuhr) |
| Abfuhrkalender Erinnerung und Ansage | [LoxBerry-Plugin-AWM-Abfuhr](https://github.com/timanders22/LoxBerry-Plugin-AWM-Abfuhr) |
| Ferien und Feiertage | [LoxBerry-Plugin-FerienFeiertage](https://github.com/timanders22/LoxBerry-Plugin-FerienFeiertage) |
| Ferien und Feiertage Meldungen | [LoxBerry-Plugin-FerienFeiertage](https://github.com/timanders22/LoxBerry-Plugin-FerienFeiertage) |
| Ferien und Feiertage Haus | [LoxBerry-Plugin-FerienFeiertage](https://github.com/timanders22/LoxBerry-Plugin-FerienFeiertage) |
| Intercom | [LoxBerry-Plugin-Intercom](https://github.com/timanders22/LoxBerry-Plugin-Intercom) |
| SignalBot | [LoxBerry-Plugin-SignalBot](https://github.com/timanders22/LoxBerry-Plugin-SignalBot) |
| SignalBot Befehle und Meldungen | [LoxBerry-Plugin-SignalBot](https://github.com/timanders22/LoxBerry-Plugin-SignalBot) |
| Sprachsteuerung | [LoxBerry-Plugin-Sprachsteuerung](https://github.com/timanders22/LoxBerry-Plugin-Sprachsteuerung) |
| Sprachsteuerung Befehle | [LoxBerry-Plugin-Sprachsteuerung](https://github.com/timanders22/LoxBerry-Plugin-Sprachsteuerung) |
| Sprachsteuerung Ansagen | [LoxBerry-Plugin-Sprachsteuerung](https://github.com/timanders22/LoxBerry-Plugin-Sprachsteuerung) |
| Govee | [LoxBerry-Plugin-Govee](https://github.com/timanders22/LoxBerry-Plugin-Govee) |
| Govee Licht | [LoxBerry-Plugin-Govee](https://github.com/timanders22/LoxBerry-Plugin-Govee) |
| Govee Szenen und Balken | [LoxBerry-Plugin-Govee](https://github.com/timanders22/LoxBerry-Plugin-Govee) |
| Midea2Lox | [LoxBerry-Plugin-Midea2Lox](https://github.com/timanders22/LoxBerry-Plugin-Midea2Lox) |
| Midea2Lox Betrieb | [LoxBerry-Plugin-Midea2Lox](https://github.com/timanders22/LoxBerry-Plugin-Midea2Lox) |
| Midea2Lox Komfort und Energie | [LoxBerry-Plugin-Midea2Lox](https://github.com/timanders22/LoxBerry-Plugin-Midea2Lox) |
| Matter2Lox | [LoxBerry-Plugin-Matter2Lox](https://github.com/timanders22/LoxBerry-Plugin-Matter2Lox) |
| Matter2Lox Geräte | [LoxBerry-Plugin-Matter2Lox](https://github.com/timanders22/LoxBerry-Plugin-Matter2Lox) |
| Matter2Lox Bridge | [LoxBerry-Plugin-Matter2Lox](https://github.com/timanders22/LoxBerry-Plugin-Matter2Lox) |
| BLE-Scanner NG | [LoxBerry-Plugin-BLE-Scanner](https://github.com/timanders22/LoxBerry-Plugin-BLE-Scanner) |
| BLE-Scanner NG Tags | [LoxBerry-Plugin-BLE-Scanner](https://github.com/timanders22/LoxBerry-Plugin-BLE-Scanner) |
| BLE-Scanner NG Messwerte | [LoxBerry-Plugin-BLE-Scanner](https://github.com/timanders22/LoxBerry-Plugin-BLE-Scanner) |
| MGiSmart | [LoxBerry-Plugin-MGiSmart](https://github.com/timanders22/LoxBerry-Plugin-MGiSmart) |
| MGiSmart Laden | [LoxBerry-Plugin-MGiSmart](https://github.com/timanders22/LoxBerry-Plugin-MGiSmart) |
| MGiSmart Klima und Befehle | [LoxBerry-Plugin-MGiSmart](https://github.com/timanders22/LoxBerry-Plugin-MGiSmart) |
| MGiSmart Fahrzeug | [LoxBerry-Plugin-MGiSmart](https://github.com/timanders22/LoxBerry-Plugin-MGiSmart) |
| ACTi-Kamera | [LoxBerry-Plugin-ACTiKamera](https://github.com/timanders22/LoxBerry-Plugin-ACTiKamera) |
| ACTi-Kamera Aufnahmen | [LoxBerry-Plugin-ACTiKamera](https://github.com/timanders22/LoxBerry-Plugin-ACTiKamera) |
| GARDENA smart system | [LoxBerry-Plugin-GardenaSmartSystem](https://github.com/timanders22/LoxBerry-Plugin-GardenaSmartSystem) |
| GARDENA smart system Mähroboter | [LoxBerry-Plugin-GardenaSmartSystem](https://github.com/timanders22/LoxBerry-Plugin-GardenaSmartSystem) |
| GARDENA smart system Ventil | [LoxBerry-Plugin-GardenaSmartSystem](https://github.com/timanders22/LoxBerry-Plugin-GardenaSmartSystem) |
| GARDENA smart system Sensor und Steckdose | [LoxBerry-Plugin-GardenaSmartSystem](https://github.com/timanders22/LoxBerry-Plugin-GardenaSmartSystem) |
| WOLF ISM NG | [LoxBerry-Plugin-WOLF-ISM-NG](https://github.com/timanders22/LoxBerry-Plugin-WOLF-ISM-NG) |
| WOLF ISM NG Werte | [LoxBerry-Plugin-WOLF-ISM-NG](https://github.com/timanders22/LoxBerry-Plugin-WOLF-ISM-NG) |
| WOLF ISM NG Bedienung | [LoxBerry-Plugin-WOLF-ISM-NG](https://github.com/timanders22/LoxBerry-Plugin-WOLF-ISM-NG) |

Weitere Plugins folgen.

## Werte über das MQTT-Gateway

Seit Oktober 2026 stellen die Plugins nach und nach auf MQTT um (zuerst Spotpreis aWATTar, Marstek Venus E, Smartmeter classic, FerienFeiertage und Abfuhrkalender, danach Abfahrts-Assistent, Bewässerung, Saugroboter und Robonect, dann Ecowitt-Weiche, Einspeisebremse, Govee, Raumklima und Fensterbilanz, zuletzt WaermepumpeCloud und EVCC). Für diese Plugins gilt, wie es die [LoxBerry-Anleitung zum MQTT-Gateway](https://wiki.loxberry.de/konfiguration/widget_help/widget_mqtt) verlangt:

- Die Werte kommen über das MQTT-Gateway des LoxBerry in **einfache Virtuelle Eingänge** (Texte in Virtuelle Texteingänge) – **keine** Virtuellen HTTP-Eingänge und keine Vorlage. Der Name jedes Eingangs ist genau der Name, den das Gateway vergibt; die Namenstabelle mit Kopierknopf steht im Reiter „Einbindung in Loxone“ des Plugins. Wer die Seiten aus diesem Projekt kopiert, bekommt die Eingänge mit.
- „Als Digitaleingang verwenden“ nicht aktivieren. Der am Miniserver hinterlegte LoxBerry-Benutzer braucht Rechte auf die Eingänge.
- Gateway V1: Abo `<plugin>/#` (die Plugins tragen es selbst ein). Gateway V2: die Datenpunkte aus der Hakenliste im Reiter des Plugins anhaken.
- Befehle gehen über den Virtuellen Ausgang `VQ_loxberry_mqtt_gateway.xml` (UDP-Eingang des Gateways, `publish <plugin>/befehl/<name> …`). Im Plugin den Haken „Befehle über MQTT annehmen“ setzen (Reiter MQTT); Befehle, die etwas in Gang setzen (z. B. Mäher oder Saugroboter fahren), brauchen zusätzlich den zweiten Haken dort. Beide sind ab Werk aus. Ein Ausgangsbefehl darf nie so heißen wie ein Eingang, den das Gateway beschreibt.
- Die Seite „LoxBerry MQTT-Gateway“ schickt nach jedem Start des Miniservers einmal `reconnect` an das Gateway, damit alle Werte neu ankommen.

## Benutzen

1. Projektdatei in Loxone Config öffnen. Der Miniserver darin ist ein Platzhalter („Demo-Miniserver“) – die Datei nie unverändert auf den eigenen Miniserver laden.
2. Die gewünschte Seite ansehen und die Bausteine in das eigene Projekt kopieren (markieren, Strg+C, im eigenen Projekt Strg+V).
3. Die passende Vorlage importieren: Peripherie → Virtuelle Eingänge → „Vordefinierte HTTP-Geräte“ → „Vorlage importieren“. Steht in der Adresse `loxberry` und `DEIN_TOKEN` (ACTi-Kamera, AnkerSolix, BatterieBMS, Beschattungswächter, Dashboard, Docker NG, Funkwacht, Heimkino, Spotpreis Tibber, Weissware, Zendure SolarFlow), beides durch die Adresse des eigenen LoxBerry und den Schlüssel aus dem Plugin ersetzen; bei Kodi NG (`tcp://loxberry:9090`) und Chromecast4lox (`/dev/udp/loxberry/11884`, UDP-Eingang des MQTT-Gateways – Port aus den MQTT-Einstellungen des LoxBerry) nur die Adresse. Vorlagen mit `http://localhost` bleiben, wie sie sind. „Netzleistung (eigene Quelle)“ auf den Steuerungsseiten ist ein Virtueller Eingang für den eigenen Stromzähler (plus = Bezug, minus = Einspeisung); die Seite „BatterieBMS Spotpreis-Laden“ braucht zusätzlich den Virtuellen Eingang `spot_awattar_cur_boerse` (Plugin Spotpreis aWATTar, siehe „Werte über das MQTT-Gateway“). Weitere Platzhalter für eigene Quellen: „Regensensor (eigene Quelle)“ (Robonect Steuerung), „Anwesenheit (eigene Quelle)“ (Saugroboter) sowie Ladeleistung und Ladezustand je Speicher (Einspeisebremse Speicher; diese Seite sendet über `VQ_loxberry_mqtt_gateway.xml` an den UDP-Eingang des MQTT-Gateways). Die Einspeisebremse wird über `VQ_loxberry_mqtt_gateway.xml` geschaltet (Befehle „Einspeisebremse: …“). Weitere Platzhalter: „Beschattungsfreigabe (eigene Quelle)“ (Beschattungswächter), „Anwesenheit (eigene Quelle)“ und „Türklingel (eigene Quelle)“ (Chromecast4lox Steuerung, Kodi-NG Wiedergabe), „Niemand zu Hause (eigene Quelle)“ (Kodi-NG Wiedergabe). Die Seite „Bewässerung Zonen“ zeigt die Beispielzonen „Rasen“ und „Beet“; die Namen der Eingänge folgen den eigenen Zonen (Namenstabelle im Plugin), die Rückmeldung der Durchläufe geht über `VQ_loxberry_mqtt_gateway.xml`. Smartmeter liefert alle Werte über das MQTT-Gateway (siehe „Werte über das MQTT-Gateway“). Chromecast4lox und Kodi-NG nutzen zusätzlich Virtuelle Texteingänge (Titel, Zustand), die das MQTT-Gateway füllt – Namen genau so übernehmen. Heimkino schaltet Bild und Ton über `VQ_Heimkino_Bild_und_Ton.xml`; die Seiten „EVCC Steuerung“ und „EVCC Hausspeicher und Tarif“ senden seit EVCC 0.9.45 über `VQ_loxberry_mqtt_gateway.xml` (Befehle „EVCC: …“); die Werte kommen über das MQTT-Gateway. „WaermepumpeCloud“ schaltet seit 0.9.35 über `VQ_loxberry_mqtt_gateway.xml` (Befehle „Wärmepumpe Cloud: …“; die Warmwasser-Zwangsladung gibt es nicht beim Hersteller Nibe) und nutzt für die Einschaltempfehlung zusätzlich den Virtuellen Eingang `spot_awattar_rank` (Plugin Spotpreis aWATTar); Platzhalter dort: „Sperrsignal Netzbetreiber (eigene Quelle)“, „PV-Leistung (eigene Quelle)“ sowie Netzleistung und Speicher wie oben. APC-UPS NG nutzt zusätzlich Virtuelle Texteingänge (`apcups_status` und weitere), die das MQTT-Gateway füllt – Namen genau so übernehmen. Die Seite „Fensterbilanz Messwerte“ sendet über `VQ_loxberry_mqtt_gateway.xml` (Befehle „Fensterbilanz: … melden“) alle fünf Minuten Messwerte an das Plugin; Platzhalter dort: „Globalstrahlung“, „Tageshöchstwert heute/morgen“, „PV-Leistungsprognose jetzt“ und „Raumtemperatur Wohnzimmer“, jeweils „(eigene Quelle)“. Die Texteingänge `fenster_WZ_begruendung` und `fenster_bericht` füllt das MQTT-Gateway – Namen genau so übernehmen. Bei Smartmeter steht `0001` für die Zählernummer aus den Einstellungen des Plugins – die genauen Namen stehen in der Namenstabelle des Plugins. Ausgangs-Vorlagen (`VQ_…`) kommen genauso unter Virtuelle Ausgänge → „Vordefinierte Geräte“. Die Plugins bringen ihre Vorlage zum Teil auch selbst mit. Die Geräte-Seiten nutzen Beispielgeräte mit Platzhaltern: Govee „Lichtleiste“ (IP 192.0.2.10 aus dem Dokumentationsnetz, eigene Adresse eintragen), Midea2Lox über den UDP-Eingang `/dev/udp/loxberry/7013` (im Plugin Abfragetakt 60 s einstellen), Matter2Lox getrennt nach Matter-Geräten (nach Loxone) und der Matter-Bridge (Beta, ab Werk aus), BLE-Scanner NG mit Platzhalter-Adressen AA:BB:CC:… und den fertigen Signalen „Jemand/Niemand zu Hause (BLE)“, die die Platzhalter „(eigene Quelle)“ ersetzen können; MGiSmart in der Form der übrigen Autos. ACTi-Kamera nutzt `VI_actikamera.xml`/`VQ_actikamera.xml` (Beispielkamera „Haustür“, 192.0.2.20, `DEIN_TOKEN`) und die Platzhalter „Türklingel“, „Türtaster“ und „Bewegungsmelder (eigene Quelle)“. GARDENA smart system liest über das MQTT-Gateway (`VI_gardena.xml`, `http://localhost`, Abo `gardena/#`) und steuert über `VQ_gardena_steuern.xml`; Beispielgeräte ohne Umlaut (Maehroboter, Ventil Beet, Sensor Beet, Steckdose Teich), die Texteingänge (Tätigkeit, Fehler) füllt das MQTT-Gateway – Namen genau so übernehmen. WOLF ISM NG nutzt `VI_wolf_ism.xml` (`http://localhost`, die Werte schreibt das MQTT-Gateway) und `VQ_wolf_ism.xml` (UDP-Eingang des MQTT-Gateways); bei den Radiotasten heißt der Ausgang mit der Nummer der gewählten Taste in Config „N“. Die Seiten „Ferien und Feiertage“ setzen die Betriebsmodi „Feiertag“, „Freier Tag/Schulferien“, „Urlaub“ und „Anwesenheitssimulation“ über Ausgangsreferenzen (Betriebsmodus im Baum wählen → Menüband „Betriebsmodi“ → „Ausgangsreferenz einfügen“); damit folgen alle Schaltuhren des Projekts dem Kalender des Plugins. Intercom, SignalBot und Sprachsteuerung nutzen eigene Vorlagen (`VQ_intercom_steuern.xml`, `VI_signalbot.xml`/`VQ_signalbot.xml`, `VI_Sprachsteuerung.xml`/`VQ_Sprachsteuerung.xml`); keine echten Rufnummern. Die Auto-Seiten (AudiConnect, BYD Autos, Renault NG, Skoda-Connect-NG, VolkswagenID) nutzen je Plugin eigene Vorlagen (`VI_audi_1_*`, `VI_byd_1.xml`, `VI_skoda_*`, `VI_volkswagen_*` und die Befehlsvorlagen `VQ_*`) mit `DEIN_TOKEN`; Renault liefert seine Werte über das MQTT-Gateway (Virtuelle Eingänge, Namen genau so übernehmen). Ver- und Entriegeln sowie Hupe sind bewusst nicht im Musterprojekt. Die Klimatisierung bekommt die Zieltemperatur aus einem Schieberegler; vorklimatisiert wird Mo–Fr 06:40–07:00 nur bei „Anwesenheit (eigene Quelle)“. Spotpreis Octopus nutzt `VI_octopus_eingaenge.xml` (`http://localhost`, die Werte schreibt das MQTT-Gateway) und `VQ_octopus_befehle.xml`; Marstek Venus E liest über das MQTT-Gateway (siehe „Werte über das MQTT-Gateway“); Sollwert und Modus Auto/AI gehen seit Marstek Venus E 1.1.26 über `VQ_loxberry_mqtt_gateway.xml` (Befehle „Marstek Sollwert senden“ und „Marstek Handbetrieb: …“). Die Seiten „… Stundenprofil“ (aWATTar, Octopus, Tibber) zeigen den Spotpreis-Optimierer im Modus „Absolut“ mit den 24 Stundenpreisen des Plugins; Loxone empfiehlt alternativ den Modus „Spotmarkt“, der die Börsenpreise ohne Plugin holt.
4. Die Tabelle im Reiter „Einbindung in Loxone“ des Plugins nennt jeden Baustein mit vollem Namen. Config kürzt lange Namen auf schmalen Bausteinen ab – in den Bildern stehen deshalb nur Anfänge.

## English

A shared Loxone Config project with one page per LoxBerry plugin, showing the blocks from each plugin's "Loxone integration" tab, already wired. Open the file in Loxone Config, copy the blocks of the page you need into your own project, and import the matching template from `vorlagen/` (Virtual Inputs → Predefined HTTP devices → Import template). Where the address contains `loxberry` and `DEIN_TOKEN` (AnkerSolix, BatterieBMS, Beschattungswächter, Dashboard, Docker NG, Funkwacht, Heimkino, Zendure SolarFlow), replace them with your LoxBerry's address and the plugin's key; for Kodi NG (`tcp://loxberry:9090`) and Chromecast4lox (`/dev/udp/loxberry/11884`, the MQTT gateway's UDP input – port from the LoxBerry MQTT settings) only the address; templates with `http://localhost` stay as they are. Placeholders marked “(eigene Quelle)” (rain sensor, presence, doorbell, shading release, storage power and state of charge) stand for your own sources; replace them with your own inputs. The irrigation zone page uses the sample zones “Rasen” and “Beet”; input names follow your own zones (name table in the plugin); Chromecast4lox and Kodi-NG also use virtual text inputs filled by the MQTT gateway – keep their names exactly. Heimkino switches picture and sound via `VQ_Heimkino_Bild_und_Ton.xml`; since EVCC 0.9.45 the EVCC control pages send via `VQ_loxberry_mqtt_gateway.xml` (commands „EVCC: …“); since 0.9.35 WaermepumpeCloud switches via `VQ_loxberry_mqtt_gateway.xml` (commands „Wärmepumpe Cloud: …“; hot-water boost does not exist for Nibe) and also needs the virtual input `spot_awattar_rank` (plugin Spotpreis aWATTar); APC-UPS NG also uses virtual text inputs filled by the MQTT gateway – keep their names exactly. The page "Fensterbilanz Messwerte" sends measurements to the plugin every five minutes via `VQ_loxberry_mqtt_gateway.xml`; its inputs marked "(eigene Quelle)" are placeholders for your own sensors. Plugins that have moved to MQTT (Spotpreis aWATTar, Marstek Venus E, Smartmeter classic, FerienFeiertage, Abfuhrkalender, Abfahrts-Assistent, Bewässerung, Saugroboter, Robonect, Ecowitt-Weiche, Einspeisebremse, Govee, Raumklima, Fensterbilanz) deliver their values through the LoxBerry MQTT gateway into plain virtual inputs named exactly as the gateway names them (name table in the plugin's tab) – no virtual HTTP inputs, no template; do not tick "use as digital input", and give the LoxBerry user rights on the inputs. Commands go through `VQ_loxberry_mqtt_gateway.xml`; tick “accept commands via MQTT” in the plugin, and for commands that start something (mower, vacuum robot) also the second tick box – both are off by default. Do not upload the project unchanged to your own Miniserver.

## Lizenz

MIT, siehe `LICENSE`.
