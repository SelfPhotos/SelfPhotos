<h1 align="center">
  <img src="https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/logo.png?raw=true" height="80" alt="Self Photos Logo" />
  <p>Self Photos</p>
</h1>

<p align="center"><a href="./README.md">English</a> | <a href="./README.zh.md">中文</a> | <a href="./README.de.md">Deutsch</a> | <a href="./README.es.md">Español</a> | Français | <a href="./README.hi.md">हिन्दी</a> | <a href="./README.it.md">Italiano</a> | <a href="./README.ja.md">日本語</a> | <a href="./README.pt.md">Português</a> | <a href="./README.ru.md">Русский</a></p>

**Self Photos** est un **outil multiplateforme de gestion de photos et de videos** construit avec Rust, disponible pour Windows, macOS, Linux (bientot), Android et iOS.

Imaginez-le comme un Google Photos entierement local pour vos propres appareils. Il vous aide a organiser les photos et videos de votre ordinateur, de disques externes, de NAS et de telephones, avec la confidentialite et le controle en priorite: vos medias ne sont pas televerses dans le cloud et restent sur vos appareils.

![Screenshot: desktop app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/self-photos-screenshot.png?raw=true)

> 👏 Rejoignez [Discord](https://discord.gg/VCqXcAz6Js) | Suivez-nous sur [X(Twitter)](https://x.com/wikkefly)

# ✨ Fonctionnalites principales

## 1. Rassembler les photos et videos dispersees

Self Photos analyse les photos et videos de votre ordinateur, de disques externes, de peripheriques connectes et de NAS, puis les regroupe dans une seule bibliotheque locale.

- **Analyse en un clic**: detectez rapidement les photos et videos sur votre ordinateur et extrayez automatiquement l'heure de prise de vue, le lieu, le type de media et d'autres metadonnees
- **Sources de donnees flexibles**: ajoutez des dossiers locaux, des disques externes, des emplacements reseau et plus encore; l'ancienne page des dossiers a ete remplacee par une page de sources de donnees plus claire avec une meilleure vue en liste
- **Prise en charge SMB**: analysez et indexez directement les photos et videos sur un NAS via SMB, sans les copier d'abord sur votre ordinateur
- **Regles d'analyse flexibles**: definissez des chemins d'analyse, excluez des dossiers, configurez des regles de chemins imbriques et filtrez les petites fichiers inutiles comme les icones ou les images de cache selon un seuil de taille
- **Surveillance des fichiers et analyse manuelle**: les sources locales peuvent etre surveillees en temps reel et mettre a jour l'index dynamiquement; les sources non locales peuvent etre analysees manuellement quand necessaire
- **Detection de Live Photos**: detecte et associe automatiquement les Live Photos entre les sources de donnees pour garder ensemble l'image fixe et le clip en mouvement

![Screenshot: scan select](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/scan-screenshot.png?raw=true)

## 2. Sauvegarder les albums mobiles sur votre ordinateur

Apres avoir installe l'application mobile Self Photos, associez-la a l'application de bureau sur le meme reseau local pour sauvegarder les photos et videos des appareils Android et iOS vers votre ordinateur ou un disque externe.

- **Brancher et sauvegarder**: apres avoir choisi les albums mobiles, les nouvelles photos et videos peuvent se synchroniser automatiquement vers votre ordinateur
- **Sauvegarde manuelle**: choisissez des photos et videos precises quand vous en avez besoin
- **Sauvegarde par plage de dates**: sauvegardez seulement les photos et videos recentes, pratique pour organiser rapidement du nouveau contenu
- **Qualite originale**: conservez les photos et videos originales sans compression ni perte de qualite
- **Gestion independante de plusieurs appareils**: definissez des dossiers de sauvegarde separes pour differents telephones, avec des regles pour les sous-dossiers et les noms de fichiers, par exemple `E:/Backup/iPhone 16 Pro Max/2025/2025-12/2025.12.01_IMG_1234.jpg`
- **Transfert sur reseau local**: les sauvegardes n'utilisent pas de donnees mobiles; la vitesse depend de votre reseau local et des performances du disque

![Screenshot: mobile app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/screenshot-mobile.png?raw=true)

## 3. Revoir les souvenirs par la chronologie

Self Photos organise votre bibliotheque selon la vraie heure de prise de vue des photos et videos, pour que vous puissiez revenir a un jour, un mois ou une annee precise comme si vous tourniez les pages d'un journal.

- **Classement automatique par date de prise de vue**: les photos et videos sont rangees selon le moment ou elles ont ete prises, pas seulement selon la date de creation du fichier
- **Saut rapide par date**: accedez rapidement a une annee ou un mois precis via la chronologie et la navigation par date
- **Navigation fluide dans les grandes bibliotheques**: une experience de bureau optimisee qui reste fluide meme avec des centaines de milliers de photos
- **Apercu au survol**: survolez pour previsualiser rapidement les photos et videos, ce qui accelere fortement la consultation et le filtrage
- **Lecteur video integre**: lisez les videos directement dans l'application, avec un support dependant des codecs de votre systeme
- **Plusieurs facons de parcourir**: utilisez la chronologie, la structure originale des dossiers, les favoris, l'application par defaut du systeme ou l'ouverture de l'emplacement dans le gestionnaire de fichiers

![Screenshot: timeline](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/timeline.png?raw=true)

## 4. Organiser les moments importants avec des albums

En plus de l'organisation automatique par temps et par structure de dossiers, Self Photos inclut des albums pour rassembler activement des medias de voyage, famille, projet, vacances ou theme.

- **Creer des albums thematiques**: regroupez des photos et videos provenant de differentes sources et dates dans un seul album
- **Conserver les fichiers originaux en place**: les albums organisent et affichent les medias sans deplacer les fichiers originaux
- **Concu pour les collections durables**: mariages, croissance des enfants, voyages, ressources creatives et autres collections importantes peuvent chacune avoir leur propre album

![Screenshot: album](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/album.png?raw=true)

## 5. Nettoyer, gerer et profiter d'une nouvelle experience de bureau

Self Photos ne sert pas seulement a regarder. Il vous aide aussi a gerer votre bibliotheque de medias plus efficacement.

- **Detection des doublons**: trouvez intelligemment les photos et videos en double, previsualisez-les et supprimez-les en lot pour nettoyer votre bibliotheque
- **Nouveau systeme de conception**: une interface et une experience de bureau plus modernes pour gerer durablement de grandes bibliotheques de photos et videos
- **Favoris et comparaison**: marquez rapidement les medias importants comme favoris et comparez les photos cote a cote dans l'aperçu
- **Stockage et vitesse illimites**: la capacite est limitee uniquement par vos disques, et la vitesse de transfert uniquement par votre reseau local et les performances des appareils
- **Prive et securise**: l'application fonctionne hors ligne; les photos et videos ne quittent pas vos appareils, et la sauvegarde mobile exige seulement que les appareils soient sur le meme reseau local

![Screenshot: duplicate detection](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/duplicate.png?raw=true)

# ⬇️ Telecharger

Telechargez le dernier **installateur de bureau** et la **application mobile** depuis le site officiel: [https://selfphotos.com/download](https://selfphotos.com/download)
