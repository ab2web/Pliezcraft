# Behavior Packs

Dieser Bereich fasst alle server- und spielmechanikrelevanten Anpassungen zusammen.

## Empfohlene Struktur
- `common/`: Geteilte Komponenten wie Loot-Tabellen, Entities oder Funktionen, die mehrere Packs nutzen.
- `custom_items/`: Spezifische Behavior-Definitionen für neue Items (z. B. `minecraft:item`, `minecraft:entity`).

Lege für jedes Behavior-Pack einen eigenen Unterordner mit folgender Struktur an:
```
<Name_des_Packs>/
├── manifest.json
├── texts/
├── entities/
├── items/
└── functions/
```

Dokumentiere Besonderheiten in einer `README.md` im jeweiligen Pack.
