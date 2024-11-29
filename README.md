# Preisüberwachungs- und Produkt-Tracking-App

Diese Anwendung ermöglicht das Hinzufügen, Anzeigen und regelmäßige Aktualisieren von Produkten aus Online-Shops. Die Preise der Produkte werden automatisch aktualisiert und in einer JSON-Datei gespeichert. Die App unterstützt eine einfache Benutzeroberfläche zur Produktverwaltung.

## Funktionen

- **Produkt hinzufügen**: Produkte können manuell hinzugefügt werden, indem die URL, der Titel und der aktuelle Preis eingegeben werden.
- **Preisüberwachung**: Die Anwendung überprüft regelmäßig (alle 15 Sekunden) die aktuellen Preise der hinzugefügten Produkte von verschiedenen Online-Shops und zeigt Preisänderungen an.

- **Unterstützte Shops**:
  - **Amazon**
  - **eBay**
  - **Otto.de**

- **JSON-basierte Speicherung**: Alle Produktdaten werden in der `produkte.json` Datei gespeichert.
- **JSON-basierte Speicherung**: App-Version wird in der `version.json` Datei gespeichert.
- **Automatische Preisaktualisierung**: Änderungen am Preis werden in der Anwendung angezeigt, und die Preisfarbe wird abhängig von der Preiserhöhung oder -senkung entsprechend markiert.

## Installation

1. **Betriebssystemanforderungen**:
   - **Microsoft Windows 10 oder 11** mit **.NET Framework 4.8.1**
   
2. Klone dieses Repository:

   ```bash
   git clone https://github.com/xeonios-studio/scraping.git
   
3. Release:

Du kannst die neueste Version der App direkt  [Release](https://github.com/xeonios-studio/scraping/releases/) herunterladen.
