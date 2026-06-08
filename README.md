<div align="center">

# GrowNote

**Diktier-App für den Mac — Taste halten, sprechen, Text erscheint am Cursor.**

[![Download](https://img.shields.io/badge/⬇_GrowNote_laden-.zip-2C435E?style=for-the-badge)](https://github.com/GrowMedia-CH/grownote-releases/releases/latest/download/GrowNote.zip)
&nbsp;
[![Latest Release](https://img.shields.io/github/v/release/GrowMedia-CH/grownote-releases?label=Version&color=2C435E&style=for-the-badge)](https://github.com/GrowMedia-CH/grownote-releases/releases/latest)

</div>

---

## Installation

1. **[GrowNote.zip herunterladen](https://github.com/GrowMedia-CH/grownote-releases/releases/latest/download/GrowNote.zip)**
2. Entpacken und **GrowNote.app** nach **/Programme** ziehen
3. Öffnen — fertig. (Developer-ID-signiert + von Apple notarisiert, **kein** Rechtsklick-Öffnen nötig.)

Beim ersten Diktieren fragt macOS nach **Mikrofon**- und **Bedienungshilfen/Eingabeüberwachungs**-Rechten — diese in den Systemeinstellungen erlauben.

## API-Keys einrichten (für die Cloud-Modi)

GrowNote enthält **keine** API-Keys — du nutzt deine **eigenen**. Die Keys bleiben lokal im macOS-Schlüsselbund, die Nutzungskosten laufen über deinen eigenen Anbieter-Account. Du brauchst sie nur für die **Cloud**-Variante. **Die Keys musst du zuerst beim Anbieter erstellen:**

| Wofür | Key erstellen unter |
|---|---|
| Cloud-Transkription (Whisper) | **OpenAI** → [platform.openai.com/api-keys](https://platform.openai.com/api-keys) |
| Schriftsprache / LLM | **Anthropic** → [console.anthropic.com](https://console.anthropic.com) → API Keys |

1. Beim jeweiligen Anbieter einen Key **erstellen** (Account nötig, ggf. Guthaben aufladen).
2. In GrowNote: **Einstellungen → API-Keys** eintragen.

> **Komplett ohne Keys / offline:** In den Einstellungen die Transkription auf **Lokal** stellen (lädt einmalig ein Whisper-Modell) und für die Schriftsprache **Ollama** lokal nutzen.

## Was kann GrowNote?

**Globales Push-to-talk:** rechte ⌥-Taste (Option) **halten** + zweite Taste, sprechen, loslassen → Text erscheint am Cursor (in jeder App). Zwei Modi:

| Tastenkombination | Modus | Was es macht |
|---|---|---|
| **⌥ᴿ + ⇧** (Shift) | **Diktat** | 1:1-Transkript, kein LLM |
| **⌥ᴿ + ⌘** (Command) | **Schriftsprache** | sauberes, geglättetes Deutsch (LLM) |

- **Offline möglich** — lokales Whisper-Modell (+ Ollama für Schriftsprache), ganz ohne Cloud und ohne Keys
- **Oder Cloud** — mit eigenen OpenAI-/Anthropic-Keys (siehe oben)
- **Aktualisiert sich selbst** — sichere Auto-Updates via [Sparkle](https://sparkle-project.org)

## Updates

Installierte Versionen aktualisieren sich automatisch. Manuell: **GrowNote → Einstellungen → Updates → Jetzt prüfen**. Jeder Build ist mit **Apple Developer ID** notarisiert **und** per **EdDSA** signiert — die App installiert nur Updates, deren beide Signaturen stimmen.

## Über dieses Repo

Dieses öffentliche Repo ist **nur der Auslieferungskanal** — es enthält **keinen Quellcode**:
- [`Releases`](https://github.com/GrowMedia-CH/grownote-releases/releases) — die fertigen App-Builds zum Download
- `appcast.xml` — der Sparkle-Update-Feed, den die App abfragt

---

<div align="center">

**[GrowMedia GmbH](https://www.growmedia.ch)** · Chastelstrasse 14, 8732 Neuhaus · info@growmedia.ch

© 2026 GrowMedia GmbH

</div>
