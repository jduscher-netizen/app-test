# NYC Trip Companion 🗽🚕

Mobile-first Reisebegleiter-App für den New-York-Trip **21.–26. August 2026** (3 Personen, Hotel: 237 W 54th St, Midtown).

Alles in **einer Datei**: [`index.html`](index.html) — einfach im Browser öffnen (am besten iPhone, Hochformat).

## Features

- **Ein Tab pro Tag** (Fr–Mi) mit Datum/Wochentag, aktueller Tag hervorgehoben, Wechsel auch per Swipe
- **Karte pro Tag** (Leaflet + OpenStreetMap, kein API-Key): nummerierte Pins in Tagesreihenfolge + Route
- **Timeline** mit Uhrzeit, Name, Adresse, Kategorie-Icon und Notiz (z. B. „vorab gebucht“)
- **Transfer-Blöcke** zwischen den Stops: Subway-Linien als runde Badges in den offiziellen MTA-Farben, Start-/Zielstation, Fahrtzeit bzw. „X Min zu Fuß“, inkl. Alternativen
- **Checkboxen** je Stopp + Fortschrittsbalken pro Tag
- **Bearbeiten-Modus**: Stops ändern/hinzufügen/löschen/verschieben, Verbindungen bearbeiten, Pins direkt auf der Karte ziehen (z. B. um die Rooftop-Party-Location am Sonntag einzutragen)
- Häkchen & Änderungen bleiben auf dem Gerät gespeichert (localStorage); „Zurücksetzen“ im Edit-Modus

## Technik

- React 18 + Leaflet, geladen per CDN, kein Build-Schritt, keine Logins
- Alle Koordinaten fest hinterlegt (kein Geocoding zur Laufzeit)

## Nutzung

- Datei lokal öffnen **oder** über GitHub Pages hosten (Settings → Pages → Branch wählen), dann auf dem iPhone „Zum Home-Bildschirm hinzufügen“.
