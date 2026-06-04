# GrowNote — Release & Update-Kanal

Dieses öffentliche Repo ist **ausschließlich der Auslieferungskanal** für die
macOS-App **GrowNote** (Sprache → Text). Es enthält **keinen Quellcode**.

- `appcast.xml` — der [Sparkle](https://sparkle-project.org)-Update-Feed, den die App abfragt
- `GrowNote-vX.Y.Z.zip` — die signierten & notarisierten App-Builds

Jeder Build ist mit **Apple Developer ID** signiert + notarisiert und zusätzlich mit
einer **EdDSA-Signatur** (Sparkle) versehen. Die App lädt Updates nur, wenn beide
Signaturen stimmen.

Veröffentlicht automatisch über `release.sh` aus dem (privaten) GrowNote-Quellrepo.

© 2026 GrowMedia GmbH
