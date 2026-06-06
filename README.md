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

## Was kann GrowNote?

- **Globales Push-to-talk** — rechte ⌥-Taste halten, sprechen, loslassen → Text wird am Cursor eingefügt (in jeder App)
- **Modi:** Raw (1:1), Polished (geglättet), Compose (Sprachbefehl → Antwort), Emoji
- **Offline möglich** — lokales Whisper-Modell + Ollama, ganz ohne Cloud
- **Oder Cloud** — mit eigenen OpenAI-/Anthropic-Keys (bleiben im Schlüsselbund)
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
