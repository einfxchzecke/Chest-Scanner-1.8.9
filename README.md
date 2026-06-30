# 📦 Chest Scanner

🇩🇪 Deutsch | 🇬🇧 [English below](#-chest-scanner-english)

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

Siehe [LICENSE](LICENSE) (MIT).

---

# 📦 Chest Scanner (English)

🇬🇧 English | 🇩🇪 [Deutsch oben](#-chest-scanner)

A LabyMod addon for Minecraft 1.8.9 that shows you at a glance what's inside a chest, double chest, ender chest, dropper, dispenser, or hopper — no more clicking through every single slot.

## ✨ Features

- **SCAN button** built right into the title bar of every supported container GUI
- Clean **overview panel** showing:
  - Number of occupied slots (with a colored progress bar)
  - Total item count
  - Number of unique item types
  - Sorted list of all items by amount (highest first)
- **Live updates** while the panel is open
- **Draggable panel** (title bar acts as the drag handle)
- **Auto-scan** option: panel opens automatically whenever a chest is opened
- Freely customizable **panel and border color** via a built-in color picker
- Works with:
  - Chest / Double Chest
  - Trapped Chest
  - Ender Chest
  - Dropper / Dispenser
  - Hopper

## 🔧 Installation

1. Load the addon through LabyMod or copy it into the addons folder
2. Enable it in the LabyMod Addons menu
3. Open any chest and click **SCAN**

## 🛠️ Development / Build

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

Then open the generated `.ipr` file in IntelliJ IDEA. The [Minecraft Dev](https://mcdev.io/) plugin is recommended but not required.

## 👤 Author

Built by **EinfxchZecke**

## 📄 License

See [LICENSE](LICENSE) (MIT).
