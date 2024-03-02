---
title: "DIADZ Themes"
meta_title: ""
slug: "designs"
# meta description
description: Designs
showDate: false
showPagination: false
draft: false
showAuthor: false
showAuthorsBadges : false
showReadingTime: false
showWordCount: false
layoutBackgroundHeaderSpace: false
---

<link href="/css/privacy.css" rel="stylesheet"></link>

{{< lead >}}In diesem Repo befinden sich die quell Dateien{{< /lead >}}

{{< github repo="Die-Irrenanstalt/DIADZ-Themes" >}}

---

## Programme

Spotify: [Spicetify](https://spicetify.app/)

Discord: [Vencord](https://vencord.dev/) (Empfohlen, aber andere funktionieren auch, z.b. [BetterDiscord](https://betterdiscord.app/))

YouTube: [Enhancer for YouTube™](https://www.mrfdev.com/enhancer-for-youtube)

## Installation

### Spicetify

- Windows -> **PowerShell**:

```powershell
iwr -useb https://codeberg.org/DIADZ/DIADZ-Themes/raw/branch/main/scripts/spicetify/install.ps1 | iex
```

- macOS and Linux -> **Bash**:

```bash
curl -fsSL https://codeberg.org/DIADZ/DIADZ-Themes/raw/branch/main/scripts/spicetify/install.sh | sh
```

* **WICHTIG:** Füge folgendes der `config-xpui.ini` hinzu. Warum wird [hier](https://github.com/JulienMaille/spicetify-dynamic-theme#important) erklärt. Führe `spicetify apply` aus, nachdem diese Zeilen hinzugefügt wurden.

```ini
[Patch]
xpui.js_find_0880 = COLLAPSED\?64:32
xpui.js_repl_0880 = COLLAPSED?32:32
xpui.js_find_8008 = ,(\w+=)56,
xpui.js_repl_8008 = ,${1}32,
```

### Discord

- Stelle sicher, dass eine Client-Mod wie [Vencord](https://vencord.dev) oder [BetterDiscord](https://betterdiscord.app) installiert ist
- Lade die [diadzv10-discord.css](https://codeberg.org/DIADZ/DIADZ-Themes/raw/branch/main/themes/discord/diadzv10-discord.css) herunter
- **Vencord:** Öffne die Einstellungen und gehe zu Themen. Klicke auf **Open Themes Folder** und platziere die **diadzv10-discord.css** darin. Klicke auf **Load missing Themes** und aktiviere das Thema.
- **BetterDiscord:** Wie oben mit dem Unterschied, dass du ```CTRL+R``` drücken musst, um Discord zu aktualisieren und fehlende Themen anzuzeigen

### Brave/Chrome

- Gehe zu ```chrome://extensions``` und aktiviere den Entwicklermodus
- Lade die Erweiterungsmanagerseite neu, um Fehler zu vermeiden
- Lade die [diadz-brave.zip](https://codeberg.org/DIADZ/DIADZ-Themes/raw/branch/main/themes/brave-chrome/diadzv10-brave.zip) herunter
- Ziehe schließlich die Datei **diadz-brave.zip** per Drag & Drop in den Erweiterungsmanager

### Vivaldi

- Lade die [diadzv10-vivaldi.zip](https://codeberg.org/DIADZ/DIADZ-Themes/raw/branch/main/themes/vivaldi/diadzv10-vivaldi.zip) herunter
- Gehe in die Einstellungen und klicke auf Themen
- Klicke auf Thema öffnen und wähle die zuvor heruntergeladene **diadzv10-vivaldi.zip**
- Klicke abschließend im Popup-Fenster auf Installieren

### YouTube

- Stelle sicher das [Enhancer for YouTube™](https://www.mrfdev.com/enhancer-for-youtube) Installiert und YouTube-DeepDark Aktiviert ist
- Öffne anschließend die [diadzv10.css](https://codeberg.org/DIADZ/DIADZ-Themes/raw/branch/main/themes/youtube/diadzv10.css) und füge den darin enthaltenen Code in das benutzerdefinierte Themenfenster ein

## Deinstallation

### Spicetify

- Windows -> **PowerShell**:

```powershell
iwr -useb https://codeberg.org/DIADZ/DIADZ-Themes/raw/branch/main/scripts/spicetify/uninstall.ps1 | iex
```

- macOS and Linux -> **Bash**:

```bash
curl -fsSL https://codeberg.org/DIADZ/DIADZ-Themes/raw/branch/main/scripts/spicetify/uninstall.sh | sh
```

### Discord

- Gehe zum Theme-Ordner und lösche die CSS-Datei

### Brave/Chrome

- Gehe zu den Designeinstellungen des Browsers und setze ihn auf die Standardeinstellungen zurück

### Vivaldi

- Klicke oben rechts in der Theme-Vorschau auf das Minuszeichen

### YouTube

- Entfernene den CSS-Code und speichern ihn

## Screenshots

### Spicetify

![diadzv10-spicetify](https://codeberg.org/DIADZ/DIADZ-Themes/raw/branch/main/screenshots/diadzv10-spicetify.webp)

![diadzv10-spicetify](https://codeberg.org/DIADZ/DIADZ-Themes/raw/branch/main/screenshots/diadzv10-spicetify2.webp)

![diadzv10-spicetify](https://codeberg.org/DIADZ/DIADZ-Themes/raw/branch/main/screenshots/diadzv10-spicetify3.webp)
(Katze nicht enthalten)

### Discord

![diadzv10-discord-home](https://codeberg.org/DIADZ/DIADZ-Themes/raw/branch/main/screenshots/diadzv10-discord-home.webp)

![diadzv10-discord-server](https://codeberg.org/DIADZ/DIADZ-Themes/raw/branch/main/screenshots/diadzv10-discord-server.webp)

![diadzv10-discord-server-popout](https://codeberg.org/DIADZ/DIADZ-Themes/raw/branch/main/screenshots/diadzv10-discord-server-popout.webp)
(Katze immer noch nicht enthalten)

### Brave/Chrome

![diadzv10-chromebrave](https://codeberg.org/DIADZ/DIADZ-Themes/raw/branch/main/screenshots/diadzv10-chromebrave.webp)

### Vivaldi

![diadzv10-vivaldi](https://codeberg.org/DIADZ/DIADZ-Themes/raw/branch/main/screenshots/diadzv10-vivaldi.webp)

### YouTube

![diadzv10-youtube-home](https://codeberg.org/DIADZ/DIADZ-Themes/raw/branch/main/screenshots/diadzv10-youtube-home.webp)

![diadzv10-youtube-channel](https://codeberg.org/DIADZ/DIADZ-Themes/raw/branch/main/screenshots/diadzv10-youtube-channel.webp)

![diadzv10-youtube-video](https://codeberg.org/DIADZ/DIADZ-Themes/raw/branch/main/screenshots/diadzv10-youtube-video.webp)

![diadzv10-youtube-comments](https://codeberg.org/DIADZ/DIADZ-Themes/raw/branch/main/screenshots/diadzv10-youtube-comments.webp)

### GRUB

#### DIADZ V10 CRT

![DIADZV10CRT](https://codeberg.org/DIADZ/DIADZ-Themes/raw/branch/main/screenshots/DIADZV10CRT.webp)

---

#### DIADZ V10 OLD BIOS

![DIADZV10OLDBIOS](https://codeberg.org/DIADZ/DIADZ-Themes/raw/branch/main/screenshots/DIADZV10OLDBIOS.webp)

## Credits

[DevEvil99](https://github.com/DevEvil99) für sein [Discord Theme](https://github.com/DevEvil99/Azurite-Discord-Theme)

[darkthemer](https://github.com/darkthemer/) für ihr [Spicetify Mimic](https://github.com/spicetify/spicetify-themes/tree/master/text) von [spotify-tui](https://github.com/Rigellute/spotify-tui)

[Lordicon](https://lordicon.com) für ihre tollen animierten Icons

Ich [benni18957](https://benni18957.de) für die Erstellung der Hintergründe und Logos für DIADZ

## Lizenz

Das Projekt selbst ist unter der [MIT-Lizenz](https://codeberg.org/DIADZ/DIADZ-Themes/src/branch/main/LICENSE) lizenziert und die Bilder und Logos von [DIADZ](https://diadz.de) sind unter der [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) Lizenz lizenziert.
