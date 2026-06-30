# 📦 Chest Scanner

Ein LabyMod-Addon für Minecraft 1.8.9, das dir auf einen Blick zeigt, was in einer Truhe, Doppeltruhe, einem Enderchest, Dropper, Dispenser oder Hopper liegt – ganz ohne jeden Slot einzeln durchzuklicken.

## ✨ Features

- **SCAN-Button** direkt in der Titelzeile jedes unterstützten Container-GUIs
- Übersichtliches **Panel** mit:
  - Anzahl belegter Slots (mit farbiger Fortschrittsleiste)
  - Gesamtzahl aller Items
  - Anzahl unterschiedlicher Item-Typen
  - Sortierte Liste aller Items nach Menge (meiste zuerst)
- **Live-Aktualisierung**, solange das Panel geöffnet ist
- **Verschiebbares Panel** per Drag & Drop (Titelzeile als Griff)
- **Auto-Scan**-Option: Panel öffnet sich automatisch beim Öffnen einer Truhe
- Frei einstellbare **Panel- und Rahmenfarbe** über einen integrierten Color-Picker
- Funktioniert mit:
  - Truhe / Doppeltruhe
  - Redstone-Truhe
  - Enderchest
  - Dropper / Dispenser
  - Hopper

## 🖥️ Vorschau

Das Scan-Panel zeigt dir kompakt Slot-Auslastung, Gesamtanzahl und eine sortierte Item-Liste – inklusive farblicher Hervorhebung großer Stacks.

## 🔧 Installation

1. Addon über LabyMod laden bzw. in den Addon-Ordner kopieren
2. Im LabyMod-Menü unter Addons aktivieren
3. Eine beliebige Truhe öffnen und auf **SCAN** klicken

## 🛠️ Entwicklung / Build

```bash
# Windows
gradlew setupDecompWorkspace
gradlew idea
gradlew genIntellijRuns

# macOS / Linux
chmod +x gradlew
./gradlew setupDecompWorkspace
./gradlew idea
./gradlew genIntellijRuns
```

Anschließend die generierte `.ipr`-Datei in IntelliJ IDEA öffnen. Das [Minecraft Dev](https://mcdev.io/) Plugin wird empfohlen, ist aber nicht zwingend erforderlich.

## 👤 Autor

Entwickelt von **EinfxchZecke**

## 📄 Lizenz

Siehe [LICENSE](LICENSE).
