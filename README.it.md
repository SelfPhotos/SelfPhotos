<h1 align="center">
  <img src="https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/logo.png?raw=true" height="80" alt="Self Photos Logo" />
  <p>Self Photos</p>
</h1>

<p align="center"><a href="./README.md">English</a> | <a href="./README.zh.md">中文</a> | <a href="./README.de.md">Deutsch</a> | <a href="./README.es.md">Español</a> | <a href="./README.fr.md">Français</a> | <a href="./README.hi.md">हिन्दी</a> | Italiano | <a href="./README.ja.md">日本語</a> | <a href="./README.pt.md">Português</a> | <a href="./README.ru.md">Русский</a></p>

**Self Photos** è uno **strumento multipiattaforma per la gestione di foto e video** costruito con Rust, disponibile per Windows, macOS, Linux (a breve), Android e iOS.

Pensalo come una versione completamente locale di Google Foto per i tuoi dispositivi. Ti aiuta a organizzare foto e video dal computer, da dischi esterni, NAS e telefoni, mettendo privacy e controllo al primo posto: i tuoi contenuti non vengono caricati nel cloud e restano sui tuoi dispositivi.

![Screenshot: desktop app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/self-photos-screenshot.png?raw=true)

> 👏 Unisciti a [Discord](https://discord.gg/VCqXcAz6Js) | Seguici su [X(Twitter)](https://x.com/wikkefly)

# ✨ Funzioni principali

## 1. Riunire foto e video sparsi

Self Photos analizza foto e video dal computer, da dischi esterni, da unità collegate e da NAS, poi li organizza in un'unica libreria multimediale locale.

- **Scansione con un clic**: scopri rapidamente foto e video sul tuo computer e ricava automaticamente ora dello scatto, posizione, tipo di media e altri metadati
- **Origini dati flessibili**: aggiungi cartelle locali, dischi esterni, posizioni di rete e altro; la vecchia pagina delle cartelle è stata trasformata in una pagina delle origini dati più chiara con una vista elenco migliorata
- **Supporto SMB**: scansiona e indicizza foto e video su un NAS direttamente tramite SMB senza doverli prima copiare sul computer
- **Regole di scansione flessibili**: definisci i percorsi di scansione, escludi cartelle, configura regole di percorsi annidati e filtra icone, immagini di cache e altri piccoli file irrilevanti in base alla dimensione
- **Monitoraggio file e scansione manuale**: le origini locali possono essere monitorate in tempo reale e aggiornate dinamicamente; le origini non locali possono essere scansionate manualmente quando serve
- **Rilevamento Live Photo**: rileva e collega automaticamente le Live Photo tra origini diverse, mantenendo insieme foto ferma e clip in movimento

![Screenshot: scan select](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/scan-screenshot.png?raw=true)

## 2. Eseguire il backup degli album mobili sul computer

Dopo aver installato l'app mobile Self Photos, abbinala all'app desktop sulla stessa rete locale per eseguire il backup di foto e video da dispositivi Android e iOS sul computer o su un disco esterno.

- **Collega e fai il backup**: dopo aver selezionato gli album mobili, le nuove foto e video possono sincronizzarsi automaticamente con il computer
- **Backup manuale**: scegli foto e video specifici quando devi salvarli
- **Backup per intervallo di date**: salva solo foto e video recenti, utile per organizzare velocemente nuovi contenuti
- **Qualità originale**: conserva foto e video originali senza compressione o perdita di qualità
- **Gestione indipendente di più dispositivi**: imposta cartelle di backup separate per telefoni diversi, con regole per sottocartelle e nomi file, ad esempio `E:/Backup/iPhone 16 Pro Max/2025/2025-12/2025.12.01_IMG_1234.jpg`
- **Trasferimento su rete locale**: i backup non usano dati mobili; la velocità dipende dalla rete locale e dalle prestazioni del disco

![Screenshot: mobile app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/screenshot-mobile.png?raw=true)

## 3. Rivivere i ricordi con la timeline

Self Photos organizza la tua libreria in base al vero momento di scatto di foto e video, così puoi tornare a un giorno, mese o anno preciso come se sfogliassi un diario.

- **Archiviazione automatica per data di scatto**: foto e video vengono ordinati in base a quando sono stati scattati, non solo in base alla data di creazione del file
- **Salto rapido alla data**: passa rapidamente a un anno o a un mese specifico tramite timeline e navigazione per data
- **Scorrimento fluido per grandi librerie**: esperienza desktop ottimizzata che resta scorrevole anche con centinaia di migliaia di foto
- **Anteprima al passaggio del mouse**: passa sopra per vedere rapidamente l'anteprima di foto e video, rendendo la navigazione e il filtraggio molto più veloci
- **Video player integrato**: riproduci i video direttamente nell'app, con supporto ai formati che dipende dai codec del sistema
- **Più modi per sfogliare**: usa la timeline, la struttura originale delle cartelle, i preferiti, l'app predefinita del sistema o mostra i file nel file manager di sistema

![Screenshot: timeline](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/timeline.png?raw=true)

## 4. Organizzare i momenti importanti con gli album

Oltre all'organizzazione automatica per tempo e struttura delle cartelle, Self Photos include gli album per raccogliere attivamente media di viaggi, famiglia, progetti, festività o temi specifici.

- **Crea album tematici**: raccogli foto e video da origini e date diverse in un solo album
- **Mantieni i file originali al loro posto**: gli album organizzano e mostrano i contenuti senza spostare i file originali
- **Pensato per collezioni durature**: matrimoni, crescita dei figli, raccolte di viaggio, risorse creative e altre collezioni importanti possono avere ciascuna il proprio album

![Screenshot: album](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/album.png?raw=true)

## 5. Pulire, gestire e godersi una nuova esperienza desktop

Self Photos non serve solo a guardare. Ti aiuta anche a gestire la tua libreria multimediale in modo più efficiente.

- **Rilevamento duplicati**: trova in modo intelligente foto e video duplicati, visualizzali in anteprima ed eliminali in blocco per pulire la libreria
- **Nuovo sistema di design**: un'interfaccia e un'esperienza desktop più moderne per la gestione a lungo termine di grandi archivi di foto e video
- **Preferiti e confronto**: contrassegna rapidamente i media importanti come preferiti e confronta le foto affiancate nella pagina di anteprima
- **Archiviazione e velocità illimitate**: la capacità è limitata solo dai tuoi dischi, e la velocità di trasferimento solo dalla rete locale e dalle prestazioni dei dispositivi
- **Privato e sicuro**: l'app funziona offline; foto e video non lasciano i tuoi dispositivi, e il backup mobile richiede solo che i dispositivi siano sulla stessa rete locale

![Screenshot: duplicate detection](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/duplicate.png?raw=true)

# ⬇️ Download

Scarica il più recente **installer desktop** e la **app mobile** dal sito ufficiale: [https://selfphotos.com/download](https://selfphotos.com/download)
