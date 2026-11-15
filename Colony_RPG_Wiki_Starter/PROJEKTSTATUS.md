# Colony RPG Wiki -- Bestandsaufnahme

## Gesicherte Projektbasis

- Servername: Colony RPG
- Minecraft: 1.21.1
- Modloader: NeoForge
- Create: 6.0.10
- MineColonies ist ein zentrales Spielsystem.
- Eisenhain ist eine Stadt innerhalb der Spielwelt, nicht der Servername.
- Ziel: öffentliches deutsches Online-Wiki plus PDF-Ausgabe.
- Spieler-Wiki und Admin-Handbuch bleiben getrennte Veröffentlichungen.

## Vorhandene Quellen und Dateien

| Quelle | Vorhanden | Verwendung |
|---|---|---|
| `Colony_RPG_Modliste.txt` | Ja | Installierte Mods und Versionen |
| `config(1).zip` | Ja | Server-/Mod-Konfigurationen |
| `datapacks.zip` | Ja | Servereigene Loot- und Spielanpassungen |
| Armory JAR | Ja | Ausrüstung und Klasseninhalte |
| Arsenal JAR | Ja | Waffen-/Ausrüstungsinhalte |
| Relics JAR | Ja | Relikte und Loot-Tiers |
| Runesmith JAR (de_DE) | Ja | Lokalisierung und Runenschmied-Inhalte |

## Kapitelübersicht und redaktionelle Zusammenführung

Die folgenden Themen sind bereits in vorhandenen Artikeln enthalten. Dafür werden keine zusätzlichen Kapitel angelegt:

| Ursprünglich geplantes Thema | Wird behandelt in |
|---|---|
| Währung und Shops (Kapitel 7) | [Kapitel 6 – Wirtschaft und Währung](docs/systeme/06-wirtschaft-und-waehrung.md) |
| Dungeons und Dimensionen (Kapitel 8) | [Kapitel 5 – Dungeons und Bosse](docs/abenteuer/05-dungeons-und-bosse.md) |
| Bosse und besondere Gegner (Kapitel 9) | [Kapitel 5 – Dungeons und Bosse](docs/abenteuer/05-dungeons-und-bosse.md) und [Kapitel 17 – Kreaturen und besondere Gegner](docs/abenteuer/17-kreaturen-und-besondere-gegner.md) |
| Klassen, Waffen und Rüstungen (Kapitel 10) | [Grundlagen – RPG-System](docs/grundlagen/04-rpg-system.md) und [Kapitel 16 – Relikte, Schmuck und besondere Ausrüstung](docs/systeme/16-relikte-schmuck-ausruestung.md) |
| Dorfbewohner und NPCs (Kapitel 19) | [Kapitel 18 – MCA Reborn und die lebendige Spielwelt](docs/kolonie/18-die-welt-und-das-leben.md); MineColonies-Bürger zusätzlich in [Kapitel 12](docs/kolonie/12-minecolonies.md) |
| Reisen, Navigation und Ausrüstung (Kapitel 21) | Waystones in [Kapitel 13](docs/systeme/13-waystones.md); Traveler's Backpack in [Kapitel 22](docs/systeme/22-komfort-und-hilfsmods.md) |

Kapitel 7 bis 10, 19 und 21 sind keine eigenständigen Artikel mehr. Die entsprechenden Themen bleiben in den genannten Kapiteln erhalten.

**Kapitel 20 – Landwirtschaft, Nahrung und Versorgung entfällt.** Es gibt dafür auf Colony RPG kein eigenständiges wichtiges Spielersystem, das einen separaten Artikel rechtfertigt.

## Aktuelle Artikel

| Kapitel | Thema | Stand |
|---|---|---|
| 18 | MCA Reborn und die lebendige Spielwelt | Überarbeitet, Bilder und Quellen ergänzt |
| 22 | Komfort- und Hilfsmods | Ausgearbeitet, Bilder und Quellen ergänzt |
| 23 | Kommunikation und Mehrspieler | Ausgearbeitet, Simple Voice Chat mit Bildern und Quellen |

### Kapitel 22 – Komfort- und Hilfsmods

Der Artikel behandelt die auf Colony RPG installierten Komfortfunktionen, unter anderem:

- Traveler's Backpack
- Tree Harvester
- Easy Anvils und Easy Magic
- Easy Piglins
- Lootr
- Just Enough Items (JEI)
- Elytra Slot und Flight Ring
- Xaero's Minimap und Xaero's World Map

Easy Villagers ist zwar in der Modliste enthalten, wird aber nicht als reguläres Spielersystem beschrieben, weil die Mod für normale Minecraft-Dorfbewohner ausgelegt ist und diese auf Colony RPG durch MCA Reborn ersetzt werden. Eine Kompatibilität mit MCA-Bewohnern ist nicht als Serverfunktion bestätigt.

### Kapitel 23 – Kommunikation und Mehrspieler

Der Artikel erklärt Simple Voice Chat mit:

- Nähe-Sprachchat (Proximity Chat)
- Push-to-talk und Sprachaktivierung
- Standardtasten und Audioeinstellungen
- privaten Sprachgruppen
- grundlegender Fehlerbehebung

Die Modliste bestätigt Simple Voice Chat 2.6.22 für NeoForge. Konkrete serverseitige Sprachreichweiten oder Netzwerkeinstellungen werden nicht als feste Spielerregeln angegeben.

## Zentrale redaktionelle Regeln

- Nur Deutsch in der Spieler-Wiki.
- Spieler-Wiki enthält keine Admin-Konfigurationen oder internen Betriebsdetails.
- Keine Kampfstrategien, Dungeon-Walkthroughs oder Boss-Spoiler.
- Servereigene Regeln klar von allgemeinen Mod-Funktionen unterscheiden.
- Zahlen, Preise, Drop-Raten und Rezepte nur veröffentlichen, wenn sie durch Dateien, Tests oder eindeutige Quellen belegt sind.
- Jede Seite erhält Quellen und einen Versions-/Prüfhinweis.
- Änderungen müssen später in Website und PDF konsistent übernommen werden.

## Noch zu erledigen

1. Vorhandene Kapiteltexte und ältere Entwürfe vollständig abgleichen, damit keine Inhalte fehlen oder doppelt vorkommen.
2. Kapitelnummerierung, Navigation und Querverweise vereinheitlichen.
3. Mod- und Datapack-Aussagen einzeln gegen die Quelldateien prüfen.
4. Bilder, Bildnachweise und externe Links auf Erreichbarkeit prüfen.
5. Website-Navigation und Startseite finalisieren.
6. Online-Wiki mit GitHub Pages veröffentlichen.
7. PDF-Export konfigurieren und beide Ausgabeformate testen.
