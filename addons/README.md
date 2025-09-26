# Add-ons

Im Ordner `addons/` liegt alles, was zur Erweiterung des Spiels über Behavior- und Resource-Packs benötigt wird.

## Unterordner
- `behavior_packs/`: Enthält Logik, Skripte und JSON-Definitionen für neue Mechaniken.
- `resource_packs/`: Beinhaltet Texturen, Modelle, Sounds und UI-Anpassungen.
- `scripts/`: Automatisierungen zum Verpacken, Validieren oder Deployen der Add-ons.
- `manifest_templates/`: Vorlagen für `manifest.json`, um neue Projekte schnell aufzusetzen.

## Arbeitsablauf
1. Lege ein neues Behavior-Pack in `behavior_packs/` an und beschreibe es in einer `README.md`.
2. Ergänze dazugehörige Ressourcen (Texturen, Modelle) im passenden Unterordner von `resource_packs/`.
3. Halte Build- und Pack-Skripte in `scripts/` aktuell, um Distributionen für Realms oder dedizierte Server zu erzeugen.
