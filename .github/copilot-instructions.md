Die Versionsnummer hat die Form Major.Minor.Patch-YYYYMMDD (als aktuelles Datum des GitPushs). Jede Änderung die du durchführst und die wir pushen MUSS eine erhöhung der Versionsnummer zur Folge haben.

Wann immer du während des Chats neuen Kontext enthälst den du für wichtig erachtest aufzuheben um dir später weiter zu helfen füge ihn einfach in die copilot-instructions.md Datei ein. Es ist wichtig, dass du die Versionsnummer erhöhst, wenn du neue Informationen hinzufügst, damit wir den Überblick behalten können.

## Projekt-Kontext

**Aktuelle Version:** 0.4.4-20260313

### Header / Logo-Bereich
- Das Logo (PNG, 550×219px, Ratio ~2.51) liegt in `.logo-mark` (160px breit, border-box).
- Die Versionsnummern (TRACKER v / IRR VER) befinden sich AUSSERHALB des Logo-Rahmens, direkt darunter – in einem wrapper-div mit `float:left;margin-right:18px`.
- Das `<img>` im logo-mark hat `width:100%;height:auto;` (nicht fixe px), damit "Red River" am unteren Bildrand nicht abgeschnitten wird.
- Credits können unabhängiger von der Versionsinfo positioniert sein (im `.header-title` Bereich).

### Manual-Modal (Bedienungsanleitung)
- Das Inhaltsverzeichnis (TOC) ist **standardmäßig eingeklappt** (collapsed).
- Aufklappen per Klick auf den TOC-Header (`toggleToc()`-Funktion).
- Nach Klick auf einen TOC-Link scrollt der Inhalt zur gewählten Sektion UND das TOC klappt sich automatisch wieder ein (in `scrollToSection()`).

### Technische Details
- Einzelne HTML-Datei ohne externe Abhängigkeiten (offline-fähig).
- LocalStorage-Key: `irr-sfv4`
- Tablet-Device-Layout mit `.tablet-outer` / `.tablet-screen`.
- Drag-to-scroll für das Tablet-Screen und das Manual-Content-Bereich.
