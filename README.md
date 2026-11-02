# Flimmer – Downloads

Fertige Versionen von **Flimmer**: YouTube-Videos ansehen ohne Werbung, mit SponsorBlock, DeArrow, Live-Chat,
Abos ohne Google-Konto und Mini-Player – für macOS, Windows, Linux, Android, Google TV sowie iPhone und iPad (Test).

➡️ **[Neueste Version herunterladen](https://github.com/mhd6271/flimmer-releases/releases/latest)** ·
Anleitung und Installation Schritt für Schritt: <https://muehlbronner.de/projekte/flimmer/>

Die Pakete der neuesten Version liegen auch hier im Repo, im Ordner **[`downloads/`](downloads/)** – ältere Versionen
stehen nur unter [Releases](https://github.com/mhd6271/flimmer-releases/releases).

| System | Datei |
|---|---|
| macOS (Apple-Chip) | `Flimmer-…-macOS-arm64.zip` – entpacken, in „Programme“ ziehen; beim ersten Start Systemeinstellungen → Datenschutz & Sicherheit → „Dennoch öffnen“ (bis macOS 14: Rechtsklick → Öffnen). Oder `brew install --cask mhd6271/flimmer/flimmer` |
| Windows | `Flimmer_…_x64-setup.exe` (oder `.msi`) – SmartScreen: „Weitere Informationen“ → „Trotzdem ausführen“ |
| Linux | `.AppImage`, `.deb` oder `.rpm` |
| Android und Google TV | `Flimmer-…-android.apk` – Installieren aus unbekannten Quellen erlauben; am Fernseher z. B. mit der App „Downloader“ und der Adresse `muehlbronner.de/download/flimmer/android` |
| iPhone und iPad (Test, ab iOS 15) | In AltStore oder SideStore die Quelle `https://raw.githubusercontent.com/mhd6271/flimmer-releases/main/altstore.json` hinzufügen – oder `Flimmer-…-ios.ipa` mit Sideloadly installieren. Signiert wird mit der eigenen Apple-ID (kostenlos: 7 Tage gültig). |

Die Apps sind (noch) nicht von Apple, Microsoft oder Google signiert, daher die Warnungen beim ersten Start.

**Updates:** Flimmer prüft auf dem Computer, unter Android und auf Google TV selbst auf neue Versionen
(Einstellungen → Updates); auf dem Computer installiert es nur Pakete mit gültiger Signatur. Die Dateien
`latest.json` und `*.sig` in den Releases sind dafür da. Auf iPhone und iPad melden AltStore/SideStore Updates über
die Quelle `altstore.json`.

Dieses Repo enthält nur die fertigen Programme, nicht den Quellcode.
Flimmer ist mit YouTube und Google nicht verbunden.
