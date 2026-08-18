<h1 align="center">
  <img src="https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/logo.png?raw=true" height="80" alt="Self Photos Logo" />
  <p>Self Photos</p>
</h1>

<p align="center"><a href="./README.md">English</a> | <a href="./README.zh.md">中文</a> | Deutsch | <a href="./README.es.md">Español</a> | <a href="./README.fr.md">Français</a> | <a href="./README.hi.md">हिन्दी</a> | <a href="./README.it.md">Italiano</a> | <a href="./README.ja.md">日本語</a> | <a href="./README.pt.md">Português</a> | <a href="./README.ru.md">Русский</a></p>

**Self Photos** ist eine mit Rust entwickelte **plattformübergreifende Desktop-App zur Verwaltung von Fotos und Videos**. Sie unterstützt Windows, macOS und Linux (in Kürze) und bietet Android- und iOS-Apps, um Handy-Alben auf dem Computer zu sichern. Zu den wichtigsten Funktionen gehören:

## ✨ Kernfunktionen

- 💽 **Einheitliche Medienbibliothek**: Fotos und Videos vom Computer, von externen Laufwerken und NAS scannen und in einer lokalen Bibliothek zusammenführen.
- 📱 **Automatische Handysicherung**: Mobile App und Desktop-App koppeln, um Originalfotos und -videos von Android und iOS automatisch auf dem Computer zu sichern.
- 🗓️ **Zeitachsenansicht**: automatisch nach Aufnahmezeit organisieren, schnell zu Daten springen und große Bibliotheken flüssig durchsuchen.
- 😀 **Gesichtserkennung**: dieselbe Person automatisch gruppieren, mit Benennung, Suche und der Möglichkeit, Gruppenfotos mit mehreren Personen zu finden.
- 🔍 **KI-Bildsuche**: Inhalte in natürlicher Sprache beschreiben und passende Fotos und Videos präzise finden.
- 🧹 **Duplikate bereinigen**: doppelte Dateien zwischen lokalen Laufwerken und NAS erkennen und mit einem Klick in den Papierkorb verschieben.
- 📁 **Ordnerstruktur beibehalten**: Medien nach lokaler Ordnerstruktur anzeigen und Dateien direkt verschieben, kopieren, löschen und umbenennen.
- 🗺️ **Erinnerungen auf der Karte**: Fotos nach Ort auf einer Karte ansehen; Standortdaten bleiben ausschließlich lokal.
- 📚 **Themenalben**: Fotos aus verschiedenen Quellen in Alben sammeln, ohne die Originaldateien zu verschieben.
- 🔒 **Datenschutzversprechen**: Fotos bleiben immer lokal und werden niemals in die Cloud hochgeladen.

![Screenshot: desktop app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/self-photos-screenshot.png?raw=true)

> 👏 Tritt [Discord](https://discord.gg/VCqXcAz6Js) bei | Folge uns auf [X(Twitter)](https://x.com/wikkefly)

## 1. Fotos von PC, Mac, Linux und NAS scannen und zusammenführen

Self Photos kann Fotos und Videos vom Computer, von externen Laufwerken und NAS scannen und verstreute Erinnerungen in einer lokalen Medienbibliothek indizieren.

- **Einheitliche lokale Bibliothek erstellen**: Aufnahmezeit, Ort und weitere Informationen automatisch aus EXIF-Metadaten extrahieren und auf Zeitachsen- und Kartenseiten anzeigen
- **NAS-Medien scannen**: Fotos und Videos auf dem NAS direkt über SMB scannen und indizieren, ohne sie vorher auf den Computer zu kopieren
- **Flexible Scanregeln**: Scanpfade festlegen, Ordner ausschließen und Regeln für verschachtelte Pfade konfigurieren; mit einer Dateigrößengrenze Symbole, Cache-Bilder und andere kleine Dateien herausfiltern
- **Dateiüberwachung und manuelles Scannen**: Änderungen auf lokalen Laufwerken in Echtzeit überwachen (hinzugefügt, gelöscht oder verschoben) und die Bibliothek automatisch aktualisieren; nicht lokale Quellen wie NAS mit einem Klick aktualisieren
- **Live-Photo-Erkennung**: Wenn im selben Ordner ein Foto und ein Video mit demselben Dateinamen gefunden werden, diese automatisch als Live Photo verknüpfen

![Screenshot: scan select](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/scan-screenshot.png?raw=true)

## 2. Mobile Alben auf dem Computer sichern

Installiere die mobile Self-Photos-App und kopple sie im selben lokalen Netzwerk mit der Desktop-App, um Fotos und Videos von Android- und iOS-Geräten auf dem Computer oder einem externen Laufwerk zu sichern.

- **Automatische Sicherung**: Nach der Auswahl mobiler Alben werden neue Fotos und Videos automatisch mit dem Computer synchronisiert
- **Nach Zeitraum sichern**: Nur Fotos und Videos aus einem aktuellen Zeitraum sichern oder den gesamten Zeitraum auswählen
- **Nach Typ sichern**: Standardmäßig nur Fotos, nur Videos oder beides sichern
- **Originalqualität**: Originalfotos und -videos ohne Komprimierung oder Qualitätsverlust speichern
- **Unabhängige Verwaltung mehrerer Geräte**: Für verschiedene Handys separate Sicherungsordner sowie Regeln für Unterordner und Dateinamen festlegen, zum Beispiel `E:/Backup/iPhone 16 Pro Max/2025/2025-12/2025.12.01_IMG_1234.jpg`
- **Übertragung im lokalen Netzwerk**: Sicherungen verbrauchen keine mobilen Daten; die Geschwindigkeit hängt vom lokalen Netzwerk und der Laufwerksleistung ab

![Screenshot: mobile app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/screenshot-mobile.png?raw=true)

## 3. Erinnerungen auf der Zeitachse neu erleben

Self Photos organisiert die Bibliothek automatisch nach der tatsächlichen Aufnahmezeit von Fotos und Videos und liest EXIF-Metadaten aus, um genaue Aufnahmezeiten zu ermitteln.

- **Schnell zu einem Datum springen**: Über Zeitachse und Datumsnavigation schnell zu einem bestimmten Jahr, Monat oder Tag springen
- **Flüssiges Durchsuchen großer Bibliotheken**: Optimierte Desktop-Erfahrung, die auch bei Millionen von Fotos flüssig bleibt
- **Vorschau beim Überfahren**: Fotos und Videos durch Bewegen des Mauszeigers schnell in der Vorschau ansehen und dadurch deutlich schneller durchsuchen und filtern
- **Integrierter Videoplayer**: Videos direkt in der App abspielen; die Formatunterstützung hängt von den Systemcodecs ab

![Screenshot: timeline](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/timeline.png?raw=true)

## 4. Gesichtserkennung

Self Photos erkennt Gesichter in Fotos und Videos, gruppiert dieselbe Person automatisch zu einer verwaltbaren Person und stellt sie auf der Zeitachse, in Ordnern und auf anderen Seiten bereit.

- **Gesichter automatisch gruppieren**: Gesichter intelligent erkennen und mehrere Gesichter derselben Person zu einer Person für die gemeinsame Anzeige zusammenführen
- **Personen benennen und anheften**: Erkannte Personen benennen und anheften, um wichtige Personen schnell zu finden
- **Nach Personen suchen**: In jeder Fotoliste nach Personen suchen
- **Gruppenfotos finden**: Mehrere Personen gleichzeitig auswählen und schnell Fotos finden, auf denen alle zu sehen sind
- **Unerwünschte Personen ausblenden**: Personen mit einem Klick aus der Ansicht beim Durchsuchen ausblenden
- **Individuelles Personencover**: Für jede Person ein repräsentatives Titelbild auswählen

![Screenshot: face recognition](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/face-recognition.png?raw=true)

## 5. KI-Bilderkennung und Suche per Text

Self Photos enthält integrierte KI-Modelle, die den Inhalt von Fotos und Videos verstehen und eine direkte Suche in der Bibliothek mit natürlicher Sprache ermöglichen.

- **KI-Inhaltserkennung**: Motive, Szenen und Details in Fotos und Videos intelligent erkennen und damit die Textsuche ermöglichen
- **Suche in natürlicher Sprache**: Ohne manuelle Tags in natürlicher Sprache nach passenden Fotos und Videos suchen
- **Präzise lange Suchanfragen**: Auch lange Sätze verwenden, etwa „ein Kind spielt mit einem blauen Ballon, während sich seine Eltern im Hintergrund küssen“; die KI findet das Zielfoto präzise und platziert es an erster Stelle
- **Intelligente Kategorien**: Häufige Themen sind standardmäßig kategorisiert und können sofort beim Öffnen angezeigt werden

![Screenshot: AI search](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/vision-search.png?raw=true)

## 6. Duplikaterkennung und Bereinigung mit einem Klick

- **Duplikate erkennen**: Doppelte Fotos und Videos intelligent erkennen, auch zwischen lokalen Laufwerken und NAS
- **Nach Verzeichnis gruppieren**: Duplikate automatisch nach dem Namen ihres Verzeichnisses zusammenfassen, damit sie Verzeichnis für Verzeichnis geprüft und bereinigt werden können; so werden typische Duplikatmuster ähnlicher Ordner berücksichtigt
- **Manuelle oder automatische Auswahl**: In jeder Duplikatgruppe Dateien manuell zum Löschen auswählen oder nach Name, Pfad, Größe oder Duplikatanzahl sortieren und jeweils die erste, letzte oder die Dateien im aktuellen Verzeichnis behalten
- **Bereinigung mit einem Klick**: Ausgewählte Dateien nach der Stapelauswahl in den Papierkorb verschieben. Bei SMB-Dateien ohne Papierkorb fragt die App vor dem endgültigen Löschen nach, damit eine Wiederherstellung weiterhin möglich ist

![Screenshot: duplicate detection](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/duplicate.png?raw=true)

## 7. Nach lokaler Ordnerstruktur durchsuchen und verwalten

Dienste wie Google Photos und Immich stellen die Ordnerstruktur weniger in den Mittelpunkt. Als lokaler Fotoverwalter respektiert Self Photos die vorhandene Ordnerstruktur, da sie frühere Organisationen wie Ordnergruppen und Dateinamen enthalten kann.

- **In Datenquellen nach Ordnern durchsuchen**: Die Datenquellenseite zeigt Dateien standardmäßig in einer Ordnerhierarchie und macht ihren Speicherort klar sichtbar
- **Wie in Explorer oder Finder verwalten**: Dateien direkt in der App verschieben, kopieren, löschen und umbenennen, ohne zu Explorer oder Finder wechseln zu müssen
- **Zukünftige Agenten verstehen die Ordnerhierarchie**: Der künftige Fotoverwaltungsagent nutzt die Ordnerhierarchie als Kontext, um Fotos besser zu erkennen und bei der Organisation zu helfen

![Screenshot: folder view](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/folder.png?raw=true)

## 8. Erinnerungen auf einer Karte neu erleben

Wenn Fotos Standortinformationen enthalten, kann Self Photos sie auf einer Karte anzeigen.

- **Fotos nach Ort ansehen**: Über die Karte schnell Fotos und Videos finden, die an einem bestimmten Ort aufgenommen wurden
- **Datenschutz zuerst**: Standortinformationen werden nur lokal für die Indizierung und Anzeige verwendet und niemals in die Cloud hochgeladen

![Screenshot: map](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/map-screenshot.png?raw=true)

## 9. Alben

Zusätzlich zur automatischen Organisation nach Zeit, Ort und Ordner bietet Self Photos Alben, um Medien von Reisen, der Familie, Projekten, Feiertagen oder zu beliebigen Themen aktiv zu sammeln.

- **Themenalben erstellen**: Fotos und Videos aus verschiedenen Quellen und Zeiträumen in einem Album sammeln
- **Originaldateien am ursprünglichen Ort behalten**: Alben organisieren und zeigen Medien an, ohne die Originaldateien zu verschieben
- **Für langfristige Sammlungen geeignet**: Hochzeiten, das Aufwachsen von Kindern, Reisesammlungen, kreative Inhalte und mehr können jeweils ein eigenes Album erhalten

![Screenshot: album](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/album.png?raw=true)

## 10. Unser starkes Datenschutzversprechen

- **Datenschutz zuerst**: Self Photos ist lokal und datenschutzorientiert. Deine Fotos bleiben einschließlich ihrer Metadaten immer lokal und werden niemals in die Cloud hochgeladen
- **Sicherheitsgarantie**: Wir ändern oder löschen deine Fotos nur, wenn du dies beim Organisieren in der App selbst auswählst. Löschungen verschieben Dateien standardmäßig nur in den Papierkorb, sodass Fehler rückgängig gemacht werden können

# ⬇️ Download

- GitHub (nur Desktop): [https://github.com/SelfPhotos/SelfPhotos/releases/latest](https://github.com/SelfPhotos/SelfPhotos/releases/latest)
- Offizielle Website (Desktop- und Android/iOS-App): [https://selfphotos.com/download](https://selfphotos.com/download)
