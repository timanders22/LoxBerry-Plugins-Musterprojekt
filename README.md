# LoxBerry-Plugins Musterprojekt

Eine gemeinsame Loxone-Config-Projektdatei mit je einer Seite pro LoxBerry-Plugin. Jede Seite zeigt die Bausteine aus dem Reiter „Einbindung in Loxone“ des Plugins, fertig verbunden.

## Inhalt

| Datei | Zweck |
|---|---|
| `LoxBerry-Plugins_Musterprojekt.Loxone` | Projektdatei (Loxone Config 17.2), eine Seite je Plugin |
| `vorlagen/*.xml` | Vorlagen für „Virtuelle HTTP-Eingänge“, die die Seiten benutzen |
| `bilder/einbindung_<plugin>.png` | Bild jeder Seite, wie es im Reiter „Einbindung in Loxone“ erscheint |

## Seiten

| Seite | Plugin |
|---|---|
| Abfahrtsassistent | [LoxBerry-Plugin-Abfahrtsassistent](https://github.com/timanders22/LoxBerry-Plugin-Abfahrtsassistent) |
| Alexa NG | [LoxBerry-Plugin-Alexa-NG](https://github.com/timanders22/LoxBerry-Plugin-Alexa-NG) |
| APC-UPS NG | [LoxBerry-Plugin-APC-UPS](https://github.com/timanders22/LoxBerry-Plugin-APC-UPS) |
| Dashboard | [LoxBerry-Plugin-Dashboard](https://github.com/timanders22/LoxBerry-Plugin-Dashboard) |
| Docker NG | [LoxBerry-Plugin-Docker-NG](https://github.com/timanders22/LoxBerry-Plugin-Docker-NG) |
| Ecowitt-Weiche | [LoxBerry-Plugin-Ecowitt-Weiche](https://github.com/timanders22/LoxBerry-Plugin-Ecowitt-Weiche) |
| EVCC | [LoxBerry-Plugin-EVCC](https://github.com/timanders22/LoxBerry-Plugin-EVCC) |
| Fensterbilanz | [LoxBerry-Plugin-Beschattung_Fensterbilanz](https://github.com/timanders22/LoxBerry-Plugin-Beschattung_Fensterbilanz) |
| Funkwacht | [LoxBerry-Plugin-Funkwacht](https://github.com/timanders22/LoxBerry-Plugin-Funkwacht) |
| Pumpenwacht | [LoxBerry-Plugin-Pumpenwacht](https://github.com/timanders22/LoxBerry-Plugin-Pumpenwacht) |
| Raumklima | [LoxBerry-Plugin-Raumklima](https://github.com/timanders22/LoxBerry-Plugin-Raumklima) |
| WaermepumpeCloud | [LoxBerry-Plugin-WaermepumpeCloud](https://github.com/timanders22/LoxBerry-Plugin-WaermepumpeCloud) |
| WiFi-Scanner-NG | [LoxBerry-Plugin-WiFi-Scanner-NG](https://github.com/timanders22/LoxBerry-Plugin-WiFi-Scanner-NG) |
| Zigbee2MqttNG | [LoxBerry-Plugin-Zigbee2MqttNG](https://github.com/timanders22/LoxBerry-Plugin-Zigbee2MqttNG) |

Weitere Plugins folgen.

## Benutzen

1. Projektdatei in Loxone Config öffnen. Der Miniserver darin ist ein Platzhalter („Demo-Miniserver“) – die Datei nie unverändert auf den eigenen Miniserver laden.
2. Die gewünschte Seite ansehen und die Bausteine in das eigene Projekt kopieren (markieren, Strg+C, im eigenen Projekt Strg+V).
3. Die passende Vorlage importieren: Peripherie → Virtuelle Eingänge → „Vordefinierte HTTP-Geräte“ → „Vorlage importieren“. Steht in der Adresse `loxberry` und `DEIN_TOKEN` (Dashboard, Docker NG, Ecowitt-Weiche, EVCC, Fensterbilanz, Funkwacht, Raumklima, WaermepumpeCloud), beides durch die Adresse des eigenen LoxBerry und den Schlüssel aus dem Plugin ersetzen; Vorlagen mit `http://localhost` bleiben, wie sie sind. Ausgangs-Vorlagen (`VQ_…`) kommen genauso unter Virtuelle Ausgänge → „Vordefinierte Geräte“. Die Plugins bringen ihre Vorlage zum Teil auch selbst mit.
4. Die Tabelle im Reiter „Einbindung in Loxone“ des Plugins nennt jeden Baustein mit vollem Namen. Config kürzt lange Namen auf schmalen Bausteinen ab – in den Bildern stehen deshalb nur Anfänge.

## English

A shared Loxone Config project with one page per LoxBerry plugin, showing the blocks from each plugin's "Loxone integration" tab, already wired. Open the file in Loxone Config, copy the blocks of the page you need into your own project, and import the matching template from `vorlagen/` (Virtual Inputs → Predefined HTTP devices → Import template). Where the address contains `loxberry` and `DEIN_TOKEN` (Dashboard, Docker NG, Ecowitt-Weiche, EVCC, Fensterbilanz, Funkwacht, Raumklima, WaermepumpeCloud), replace them with your LoxBerry's address and the plugin's key; templates with `http://localhost` stay as they are. Do not upload the project unchanged to your own Miniserver.

## Lizenz

MIT, siehe `LICENSE`.
