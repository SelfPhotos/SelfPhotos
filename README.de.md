<h1 align="center">
  <img src="https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/logo.png?raw=true" height="80" alt="Self Photos Logo" />
  <p>Self Photos</p>
</h1>

<p align="center"><a href="./README.md">English</a> | <a href="./README.zh.md">中文</a> | Deutsch | <a href="./README.es.md">Español</a> | <a href="./README.fr.md">Français</a> | <a href="./README.hi.md">हिन्दी</a> | <a href="./README.it.md">Italiano</a> | <a href="./README.ja.md">日本語</a> | <a href="./README.pt.md">Português</a> | <a href="./README.ru.md">Русский</a></p>

**Self Photos** ist ein **plattformuebergreifendes Werkzeug zur Verwaltung von Fotos und Videos** auf Rust-Basis, verfuegbar fuer Windows, macOS, Linux (demnaechst), Android und iOS.

Stell es dir als vollstaendig lokale Google-Photos-Alternative fuer deine eigenen Geraete vor. Es hilft dabei, Fotos und Videos von Computer, externen Laufwerken, NAS und Smartphones zu organisieren und stellt Privatsphaere und Kontrolle an erste Stelle: Deine Medien werden nicht in die Cloud hochgeladen und bleiben auf deinen eigenen Geraeten.

![Screenshot: desktop app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/self-photos-screenshot.png?raw=true)

> 👏 Tritt [Discord](https://discord.gg/VCqXcAz6Js) bei | Folge uns auf [X(Twitter)](https://x.com/wikkefly)

# ✨ Kernfunktionen

## 1. Verstreute Fotos und Videos zusammenbringen

Self Photos durchsucht Fotos und Videos auf deinem Computer, externen Laufwerken, angeschlossenen Datentraegern und NAS und baut daraus eine lokale Medienbibliothek.

- **Ein-Klick-Scan**: Fotos und Videos auf deinem Computer schnell finden und Aufnahmezeit, Ort, Medientyp und weitere Metadaten automatisch extrahieren
- **Flexible Datenquellen**: lokale Ordner, externe Laufwerke, Netzwerkpfade und mehr hinzufuegen; die fruehere Ordnerseite wurde zu einer klareren Datenquellen-Seite mit besserer Ordnerliste ueberarbeitet
- **SMB-Unterstuetzung**: Fotos und Videos auf einem NAS direkt per SMB scannen und indizieren, ohne sie erst auf den Computer kopieren zu muessen
- **Flexible Scan-Regeln**: Scan-Pfade festlegen, Ordner ausschliessen, verschachtelte Pfadregeln konfigurieren und kleine, irrelevante Dateien wie Icons oder Cache-Bilder per Groessenschwelle filtern
- **Dateibeobachtung und manueller Scan**: lokale Datenquellen koennen in Echtzeit ueberwacht und dynamisch aktualisiert werden; nicht-lokale Datenquellen lassen sich bei Bedarf manuell scannen
- **Live-Photo-Erkennung**: Live Photos ueber Datenquellen hinweg automatisch erkennen und verknuepfen, damit Standbild und Bewegungsclip zusammenbleiben

![Screenshot: scan select](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/scan-screenshot.png?raw=true)

## 2. Mobile Alben auf deinen Computer sichern

Nach der Installation der Self-Photos-Mobilapp kannst du sie im selben lokalen Netzwerk mit der Desktop-App koppeln, um Fotos und Videos von Android- und iOS-Geraeten auf Computer oder externe Laufwerke zu sichern.

- **Anstecken und sichern**: Nach der Auswahl mobiler Alben koennen neue Fotos und Videos automatisch auf den Computer synchronisiert werden
- **Manuelle Sicherung**: Bei Bedarf einzelne Fotos und Videos zum Sichern auswaehlen
- **Sicherung nach Zeitraum**: Nur aktuelle Fotos und Videos sichern, praktisch fuer das schnelle Aufraeumen neuer Inhalte
- **Originalqualitaet**: Originalfotos und -videos ohne Komprimierung oder Qualitaetsverlust speichern
- **Unabhaengige Verwaltung mehrerer Geraete**: fuer verschiedene Telefone getrennte Sicherungsordner festlegen, mit Regeln fuer erzeugte Unterordner und Dateinamen, zum Beispiel `E:/Backup/iPhone 16 Pro Max/2025/2025-12/2025.12.01_IMG_1234.jpg`
- **Uebertragung im lokalen Netz**: Sicherungen nutzen keine mobilen Daten; die Geschwindigkeit haengt von deinem lokalen Netzwerk und der Laufwerksleistung ab

![Screenshot: mobile app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/screenshot-mobile.png?raw=true)

## 3. Erinnerungen nach Zeitachse neu erleben

Self Photos ordnet deine Bibliothek nach der tatsaechlichen Aufnahmezeit von Fotos und Videos, damit du wie in einem Tagebuch zu einem bestimmten Tag, Monat oder Jahr zurueckkehren kannst.

- **Automatische Sortierung nach Aufnahmedatum**: Fotos und Videos werden nach dem Zeitpunkt der Aufnahme angeordnet, nicht nur nach dem Erstellungsdatum der Datei
- **Schnelles Springen zu Datumsangaben**: Ueber Zeitachse und Datumsnavigation schnell zu einem bestimmten Jahr oder Monat springen
- **Fluessiges Durchblaettern grosser Bibliotheken**: optimiertes Desktop-Erlebnis, das auch bei Hunderttausenden von Fotos geschmeidig bleibt
- **Vorschau beim Ueberfahren**: per Hover Fotos und Videos schnell vorab ansehen, was das Stoebern und Filtern deutlich beschleunigt
- **Eingebauter Videoplayer**: Videos direkt in der App abspielen; das Format haengt von den System-Codecs ab
- **Mehrere Ansichtswege**: Zeitachse, urspruengliche Ordnerstruktur, Favoriten, Systemstandard-App oder Dateien im System-Dateimanager anzeigen

![Screenshot: timeline](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/timeline.png?raw=true)

## 4. Wichtige Momente mit Alben organisieren

Zusätzlich zur automatischen Ordnung nach Zeit und Ordnerstruktur bietet Self Photos Alben, um Reisen, Familie, Projekte, Feiertage oder thematische Medien gezielt zu sammeln.

- **Thematische Alben erstellen**: Fotos und Videos aus verschiedenen Quellen und Zeitraeumen in einem Album sammeln
- **Originaldateien bleiben an Ort und Stelle**: Alben organisieren und zeigen Medien an, ohne die Originaldateien zu verschieben
- **Fuer langfristige Sammlungen gemacht**: Hochzeiten, Kinder beim Aufwachsen, Reisealben, kreative Materialien und andere wertvolle Sammlungen koennen jeweils ihr eigenes Album haben

![Screenshot: album](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/album.png?raw=true)

## 5. Aufraeumen, verwalten und eine neue Desktop-Erfahrung geniessen

Self Photos ist nicht nur zum Ansehen da. Es hilft dir auch dabei, deine Medienbibliothek effizienter zu verwalten.

- **Dubletten-Erkennung**: doppelte Fotos und Videos intelligent finden, vorab ansehen und stapelweise loeschen, um die Bibliothek aufzuraeumen
- **Neues Designsystem**: eine modernere UI und Desktop-Erfahrung fuer die langfristige Verwaltung grosser Foto- und Videobestände
- **Favoriten und Vergleichsvorschau**: wichtige Medien schnell favorisieren und Fotos in der Vorschau nebeneinander vergleichen
- **Unbegrenzter Speicher und Tempo**: Kapazitaet ist nur durch deine Laufwerke begrenzt, die Transfergeschwindigkeit nur durch dein lokales Netzwerk und die Geraeteleistung
- **Privat und sicher**: die App laeuft offline; Fotos und Videos verlassen deine Geraete nicht, und das mobile Backup benoetigt nur Geraete im selben lokalen Netzwerk

![Screenshot: duplicate detection](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/duplicate.png?raw=true)

# ⬇️ Download

Die neueste **Desktop-Installation** und **Mobil-App** findest du auf der offiziellen Website: [https://selfphotos.com/download](https://selfphotos.com/download)
