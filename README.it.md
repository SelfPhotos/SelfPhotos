<h1 align="center">
  <img src="https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/logo.png?raw=true" height="80" alt="Self Photos Logo" />
  <p>Self Photos</p>
</h1>

<p align="center"><a href="./README.md">English</a> | <a href="./README.zh.md">中文</a> | <a href="./README.de.md">Deutsch</a> | <a href="./README.es.md">Español</a> | <a href="./README.fr.md">Français</a> | <a href="./README.hi.md">हिन्दी</a> | Italiano | <a href="./README.ja.md">日本語</a> | <a href="./README.pt.md">Português</a> | <a href="./README.ru.md">Русский</a></p>

**Self Photos** è una **app desktop multipiattaforma per la gestione di foto e video**, sviluppata con Rust. Supporta Windows, macOS e Linux (in arrivo) e offre app per Android e iOS per eseguire il backup degli album del telefono sul computer. Le funzionalità principali includono:

## ✨ Funzionalità principali

- 💽 **Libreria multimediale unificata**: analizza foto e video dal computer, da unità esterne e NAS e riuniscili in un’unica libreria locale.
- 📱 **Backup automatico del telefono**: abbina l’app mobile a quella desktop per salvare automaticamente sul computer foto e video originali da Android e iOS.
- 🗓️ **Esplorazione nella timeline**: organizza automaticamente per data di scatto, consente di raggiungere rapidamente le date e di navigare senza problemi nelle librerie grandi.
- 😀 **Riconoscimento facciale**: raggruppa automaticamente la stessa persona, con funzioni per assegnare nomi, cercare persone e trovare foto di gruppo.
- 🔍 **Ricerca immagini con IA**: descrivi il contenuto in linguaggio naturale per trovare con precisione foto e video.
- 🧹 **Pulizia dei duplicati**: rileva i file duplicati tra dischi locali e NAS e spostali nel cestino con un clic.
- 📁 **Conservazione della struttura delle cartelle**: visualizza i media secondo la struttura locale e sposta, copia, elimina e rinomina i file direttamente.
- 🗺️ **Ricordi sulla mappa**: rivedi le foto sulla mappa in base alla posizione; le informazioni sulla posizione restano solo in locale.
- 📚 **Album tematici**: raccogli foto da fonti diverse negli album senza spostare i file originali.
- 🔒 **Impegno per la privacy**: le foto restano sempre in locale e non vengono mai caricate sul cloud.

![Screenshot: desktop app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/self-photos-screenshot.png?raw=true)

> 👏 Unisciti a [Discord](https://discord.gg/VCqXcAz6Js) | Seguici su [X(Twitter)](https://x.com/wikkefly)

## 1. Scansionare dischi PC, Mac, Linux e foto del NAS e riunirle

Self Photos può scansionare foto e video dal computer, da unità esterne e NAS e indicizzare i ricordi sparsi in un’unica libreria multimediale locale.

- **Creare una libreria locale unificata**: estrarre automaticamente dai metadati EXIF data di scatto, posizione e altre informazioni e mostrarle nelle pagine timeline e mappa
- **Scansionare i media sul NAS**: scansionare e indicizzare direttamente tramite SMB foto e video sul NAS, senza copiarli prima sul computer
- **Regole di scansione flessibili**: specificare i percorsi, escludere cartelle e configurare regole per percorsi annidati; impostare una soglia di dimensione per filtrare icone, immagini cache e altri file piccoli
- **Monitoraggio dei file e scansione manuale**: monitorare in tempo reale le modifiche alle unità locali (aggiunte, eliminazioni o spostamenti) e aggiornare automaticamente la libreria; aggiornare con un clic le fonti non locali come il NAS
- **Rilevamento Live Photo**: quando nella stessa cartella vengono trovati una foto e un video con lo stesso nome, associarli automaticamente come Live Photo

![Screenshot: scan select](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/scan-screenshot.png?raw=true)

## 2. Eseguire il backup degli album mobili sul computer

Installa l’app mobile Self Photos e abbinala all’app desktop sulla stessa rete locale per eseguire il backup di foto e video da dispositivi Android e iOS sul computer o su un’unità esterna.

- **Backup automatico**: dopo aver selezionato gli album mobili, le nuove foto e i nuovi video vengono sincronizzati automaticamente con il computer
- **Backup per intervallo di date**: esegui il backup solo di foto e video di un periodo recente oppure seleziona l’intero intervallo
- **Backup per tipo**: scegli di eseguire il backup solo delle foto, solo dei video o di entrambi per impostazione predefinita
- **Qualità originale**: salva foto e video originali senza compressione o perdita di qualità
- **Gestione indipendente di più dispositivi**: imposta cartelle di backup separate per telefoni diversi, con regole per sottocartelle e nomi file, ad esempio `E:/Backup/iPhone 16 Pro Max/2025/2025-12/2025.12.01_IMG_1234.jpg`
- **Trasferimento sulla rete locale**: i backup non consumano dati mobili; la velocità dipende dalla rete locale e dalle prestazioni del disco

![Screenshot: mobile app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/screenshot-mobile.png?raw=true)

## 3. Rivivere i ricordi con la timeline

Self Photos organizza automaticamente la libreria in base all’ora effettiva dello scatto di foto e video e analizza i metadati EXIF per estrarre orari precisi.

- **Passaggio rapido a una data**: raggiungi rapidamente un anno, mese o giorno specifico usando timeline e navigazione per data
- **Navigazione fluida nelle librerie grandi**: esperienza desktop ottimizzata, fluida anche con milioni di foto
- **Anteprima al passaggio del mouse**: visualizza rapidamente foto e video in anteprima passando il mouse, per navigare e filtrare molto più velocemente
- **Lettore video integrato**: riproduci i video direttamente nell’app; il supporto dei formati dipende dai codec del sistema

![Screenshot: timeline](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/timeline.png?raw=true)

## 4. Riconoscimento facciale

Self Photos riconosce in modo intelligente i volti nelle foto e nei video, raggruppa automaticamente la stessa persona e la rende disponibile nella timeline, nelle cartelle e nelle altre pagine.

- **Raggruppamento automatico dei volti**: riconosci i volti e unisci più volti della stessa persona in un’unica persona per una visualizzazione centralizzata
- **Dare un nome e fissare le persone**: assegna un nome alle persone riconosciute e fissale per trovare rapidamente quelle importanti
- **Cercare per persona**: cerca foto e video per persona in qualsiasi elenco di foto
- **Trovare le foto di gruppo**: seleziona più persone contemporaneamente per trovare rapidamente le foto che le includono tutte
- **Nascondere le persone indesiderate**: nascondi con un clic una persona che non vuoi visualizzare durante la navigazione
- **Copertina personalizzata**: cambia la foto di copertina di ogni persona e scegli quella più rappresentativa

![Screenshot: face recognition](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/face-recognition.png?raw=true)

## 5. Riconoscimento delle immagini con IA e ricerca testuale

Self Photos include modelli IA integrati che comprendono il contenuto di foto e video e consentono di cercare direttamente nella libreria usando il linguaggio naturale.

- **Riconoscimento dei contenuti con IA**: riconosce intelligentemente soggetti, scene e dettagli di foto e video, fornendo la base per la ricerca testuale
- **Ricerca in linguaggio naturale**: inserisci una descrizione naturale per cercare foto e video corrispondenti, senza tag manuali
- **Query lunghe e precise**: cerca frasi lunghe come «un bambino gioca con un palloncino blu mentre i suoi genitori si baciano sullo sfondo»; l’IA troverà con precisione la foto e la posizionerà al primo posto
- **Categorie intelligenti**: i temi comuni sono categorizzati per impostazione predefinita e mostrano i risultati appena vengono aperti

![Screenshot: AI search](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/vision-search.png?raw=true)

## 6. Rilevamento dei duplicati e pulizia con un clic

- **Rilevamento dei duplicati**: identifica intelligentemente foto e video duplicati, inclusi quelli tra dischi locali e NAS
- **Raggruppamento per directory**: raggruppa automaticamente i duplicati in base al nome della directory in cui si trovano, così puoi esaminarli e pulirli una directory alla volta, come avviene nei casi reali di cartelle simili
- **Selezione manuale o automatica**: scegli manualmente i file da eliminare in ogni gruppo oppure ordina per nome, percorso, dimensione o numero di duplicati e conserva il primo, l’ultimo o i file della directory corrente
- **Pulizia con un clic**: dopo la selezione multipla, sposta i file selezionati nel cestino. Per i file SMB, che non dispongono di cestino, l’app chiederà conferma prima dell’eliminazione permanente

![Screenshot: duplicate detection](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/duplicate.png?raw=true)

## 7. Esplorare e gestire la struttura delle cartelle locali

Servizi come Google Photos e Immich danno meno importanza alla struttura delle cartelle. In quanto gestore fotografico locale, Self Photos rispetta la struttura che hai già creato, perché può conservare la tua precedente organizzazione, come raggruppamenti e nomi dei file.

- **Esplorare per cartella nelle fonti dati**: la pagina delle fonti dati mostra per impostazione predefinita i file in una gerarchia di cartelle e indica chiaramente dove si trovano
- **Gestire come in Esplora file o Finder**: sposta, copia, elimina e rinomina i file direttamente nell’app, senza passare a Explorer o Finder
- **I futuri agenti comprenderanno la gerarchia**: il futuro agente di gestione fotografica userà la gerarchia delle cartelle come contesto per riconoscere meglio le foto e aiutarti a organizzarle

![Screenshot: folder view](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/folder.png?raw=true)

## 8. Rivivere i ricordi sulla mappa

Se le foto includono informazioni sulla posizione, Self Photos può mostrarle su una mappa.

- **Rivedere le foto per luogo**: trova rapidamente sulla mappa foto e video scattati in una posizione
- **Privacy prima di tutto**: le informazioni sulla posizione vengono usate solo localmente per l’indicizzazione e la visualizzazione e non vengono mai caricate sul cloud

![Screenshot: map](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/map-screenshot.png?raw=true)

## 9. Album

Oltre all’organizzazione automatica per tempo, posizione e cartella, Self Photos include album per raccogliere attivamente media di viaggi, famiglia, progetti, vacanze o qualsiasi tema.

- **Creare album tematici**: raccogli foto e video da fonti e date diverse in un unico album
- **Conservare i file originali al loro posto**: gli album organizzano e mostrano i media senza spostare i file originali
- **Ideali per raccolte a lungo termine**: matrimoni, crescita dei figli, raccolte di viaggi, risorse creative e altro possono avere ciascuno il proprio album

![Screenshot: album](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/album.png?raw=true)

## 10. Il nostro forte impegno per la privacy

- **Privacy prima di tutto**: Self Photos è locale e orientato alla privacy. Le tue foto, inclusi i metadati, restano sempre in locale e non vengono mai caricate sul cloud
- **Garanzia di sicurezza**: non modifichiamo né eliminiamo le tue foto a meno che tu non scelga di farlo mentre le organizzi nell’app. Per impostazione predefinita, le eliminazioni spostano solo i file nel cestino, lasciandoti la possibilità di recuperare gli errori

# ⬇️ Download

- GitHub (solo desktop): [https://github.com/SelfPhotos/SelfPhotos/releases/latest](https://github.com/SelfPhotos/SelfPhotos/releases/latest)
- Sito ufficiale (app desktop e Android/iOS): [https://selfphotos.com/download](https://selfphotos.com/download)
