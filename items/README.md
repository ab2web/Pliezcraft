# Eigene Items

Dieser Bereich bündelt alles rund um eigene Items mit individuellen Texturen und Verhalten.

## Empfohlener Arbeitsablauf
1. Dupliziere den Ordner `custom_item_template/` und benenne ihn nach deinem Item.
2. Lege die Behavior-Definitionen (z. B. `items/<dein_item>.json`, Funktionen) im Unterordner `behavior/` an.
3. Ergänze Texturen, Modelle und UI-Anpassungen im Unterordner `resource/`.
4. Dokumentiere das Item (Crafting, Fähigkeiten, Abhängigkeiten) in `documentation/`.
5. Verknüpfe das Item mit den entsprechenden Behavior- und Resource-Packs innerhalb des Ordners `addons/`.

## Hinweise
- Nutze konsistente UUIDs in `manifest.json` und `item_texture.json`.
- Halte Icons in 16x16 oder 32x32 Pixel bereit, um UI-Probleme zu vermeiden.
- Dokumentiere Gameplay-Relevanz und Balancing-Aspekte in `documentation/`.
