# Plugins

Dieser Ordner dient als Arbeitsbereich für eigene Server-Plugins der Minecraft Bedrock Edition.

## Struktur
- `src/`: Quellcode der Plugins, gegliedert nach Modulen oder einzelnen Plugin-Projekten.
- `tests/`: Automatisierte Tests, um Funktionen serverseitig zu überprüfen.
- `docs/`: Architekturbeschreibungen, Changelogs und API-Referenzen.
- `templates/`: Vorlagen für wiederkehrende Plugin-Typen (z. B. Events, Spielmodi, Utilities).
- `libs/`: Drittanbieter-Bibliotheken oder interne Module, die von mehreren Plugins genutzt werden.
- `dist/`: Gebaute Artefakte, die auf dem Server bereitgestellt werden.

## Empfehlungen
- Nutze Versionsnummern in den Build-Dateien innerhalb von `dist/`.
- Dokumentiere Plugin-spezifische Konfigurationen im jeweiligen Unterordner in `docs/`.
- Verwende Continuous-Integration-Pipelines aus dem Ordner `ci/`, um Builds zu automatisieren.
