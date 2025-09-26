# Pliezcraft – Projektstruktur für Minecraft Bedrock Erweiterungen

Dieses Repository stellt eine modulare Struktur bereit, um eigene Minecraft-Bedrock-Projekte zu planen, zu entwickeln und zu veröffentlichen. Es umfasst Bereiche für Server-Plugins, Add-ons (Behavior- & Resource-Packs) sowie eigene Items mit individuellen Texturen und Verhalten.

## Verzeichnisübersicht
```
.
├── addons/
│   ├── behavior_packs/
│   ├── manifest_templates/
│   ├── resource_packs/
│   └── scripts/
├── ci/
├── docs/
├── items/
├── plugins/
└── tools/
```

### `addons/`
Sammelstelle für alle Bedrock-Add-ons.
- **behavior_packs/** – Mechaniken, Skripte und Item-Definitionen.
- **resource_packs/** – Texturen, Modelle, Sounds und UI-Anpassungen.
- **manifest_templates/** – Vorlagen für neue `manifest.json` Dateien.
- **scripts/** – Automatisierte Packager-, Validierungs- und Deployment-Skripte.

### `plugins/`
Arbeitsbereich für serverseitige Erweiterungen. Unterordner für Quellcode (`src/`), Tests (`tests/`), Dokumentation (`docs/`), Bibliotheken (`libs/`), Build-Artefakte (`dist/`) und Vorlagen (`templates/`).

### `items/`
Zentrale Ablage für eigene Items mit dedizierter Vorlage (`custom_item_template/`), die Behavior- und Resource-Komponenten trennt. Ergänzende Beschreibungen, Balancing-Notizen und Crafting-Rezepte gehören nach `items/documentation/`.

### `docs/`
Projektweite Wissensbasis: Guides, Referenzen und Checklisten für Konsistenz und Qualitätssicherung.

### `tools/`
Hilfsskripte und Pipeline-Definitionen zur Automatisierung von Build-, Test- und Release-Prozessen.

### `ci/`
Konfigurationsdateien für Continuous-Integration-Läufe (z. B. GitHub Actions, Jenkins).

## Empfohlener Workflow
1. **Konzeption** – Plane neue Features im Ordner `docs/` und erstelle Checklisten für Qualitätssicherung.
2. **Implementierung** – Entwickle Plugins in `plugins/` und Add-ons in `addons/`. Nutze bei eigenen Items die Vorlage unter `items/`.
3. **Ressourcenpflege** – Hinterlege Texturen und Modelle im Resource-Pack, synchronisiere Behavior-Änderungen und halte Manifeste aktuell.
4. **Automatisierung** – Erstelle Skripte in `tools/` und CI-Konfigurationen in `ci/`, um Builds, Tests und Deployments zu automatisieren.
5. **Dokumentation & Release** – Dokumentiere Änderungen und veröffentliche Artefakte (`dist/`, gepackte Add-ons) für Server oder Realms.

## Nächste Schritte
- Fülle die `.gitkeep`-Platzhalterverzeichnisse mit deinem Code, JSON-Dateien, Texturen und Skripten.
- Ergänze in `docs/` projektspezifische Leitfäden (z. B. Coding-Guidelines, Naming-Konventionen, Release-Prozesse).
- Versioniere veröffentlichte Artefakte und tracke Änderungen in einer zentralen Änderungsdokumentation.
