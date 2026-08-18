<h1 align="center">
  <img src="https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/logo.png?raw=true" height="80" alt="Self Photos Logo" />
  <p>Self Photos</p>
</h1>

<p align="center"><a href="./README.md">English</a> | <a href="./README.zh.md">中文</a> | <a href="./README.de.md">Deutsch</a> | <a href="./README.es.md">Español</a> | Français | <a href="./README.hi.md">हिन्दी</a> | <a href="./README.it.md">Italiano</a> | <a href="./README.ja.md">日本語</a> | <a href="./README.pt.md">Português</a> | <a href="./README.ru.md">Русский</a></p>

**Self Photos** est une **application de bureau multiplateforme de gestion de photos et de vidéos**, développée avec Rust. Elle prend en charge Windows, macOS et Linux (bientôt disponible), et propose des applications Android et iOS pour sauvegarder les albums du téléphone sur votre ordinateur. Ses principales fonctions sont les suivantes :

## ✨ Fonctionnalités principales

- 💽 **Bibliothèque multimédia unifiée** : analysez les photos et vidéos de votre ordinateur, de disques externes et d’un NAS pour les réunir dans une bibliothèque locale.
- 📱 **Sauvegarde automatique du téléphone** : associez l’application mobile à l’application de bureau pour sauvegarder automatiquement les photos et vidéos originales d’Android et d’iOS sur votre ordinateur.
- 🗓️ **Navigation par chronologie** : organisez automatiquement les médias par date de prise de vue, accédez rapidement à une date et parcourez les grandes bibliothèques avec fluidité.
- 😀 **Reconnaissance faciale** : regroupez automatiquement une même personne, nommez-la, recherchez-la et trouvez les photos de groupe où apparaissent plusieurs personnes.
- 🔍 **Recherche d’images par IA** : décrivez le contenu en langage naturel pour trouver précisément des photos et vidéos.
- 🧹 **Nettoyage des doublons** : détectez les fichiers en double entre disques locaux et NAS et déplacez-les vers la corbeille en un clic.
- 📁 **Conservation de l’arborescence** : affichez les médias selon l’arborescence locale et déplacez, copiez, supprimez ou renommez les fichiers directement.
- 🗺️ **Souvenirs sur une carte** : consultez les photos sur une carte par lieu ; les informations de localisation restent uniquement en local.
- 📚 **Albums thématiques** : rassemblez des photos provenant de différentes sources dans des albums sans déplacer les fichiers originaux.
- 🔒 **Engagement de confidentialité** : les photos restent toujours en local et ne sont jamais envoyées dans le cloud.

![Screenshot: desktop app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/self-photos-screenshot.png?raw=true)

> 👏 Rejoignez [Discord](https://discord.gg/VCqXcAz6Js) | Suivez-nous sur [X(Twitter)](https://x.com/wikkefly)

## 1. Analyser les disques PC, Mac, Linux et les photos du NAS pour tout réunir

Self Photos peut analyser les photos et vidéos de votre ordinateur, de disques externes et d’un NAS, puis indexer vos souvenirs dispersés dans une bibliothèque multimédia locale.

- **Créer une bibliothèque locale unifiée** : extraire automatiquement la date de prise de vue, le lieu et d’autres informations des métadonnées EXIF, puis les afficher dans les pages de chronologie et de carte
- **Analyser les médias d’un NAS** : analyser et indexer directement les photos et vidéos d’un NAS via SMB, sans les copier d’abord sur l’ordinateur
- **Règles d’analyse flexibles** : définir les chemins à analyser, exclure des dossiers et configurer des règles pour les chemins imbriqués ; fixer une taille minimale pour filtrer les icônes, images de cache et autres petits fichiers
- **Surveillance des fichiers et analyse manuelle** : surveiller en temps réel les changements sur les disques locaux (ajouts, suppressions ou déplacements) et mettre à jour automatiquement la bibliothèque ; actualiser les sources non locales comme un NAS en un clic
- **Détection des Live Photos** : lorsque la même arborescence contient une photo et une vidéo portant le même nom, les associer automatiquement en Live Photo

![Screenshot: scan select](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/scan-screenshot.png?raw=true)

## 2. Sauvegarder les albums mobiles sur votre ordinateur

Installez l’application mobile Self Photos et associez-la à l’application de bureau sur le même réseau local pour sauvegarder les photos et vidéos de vos appareils Android et iOS sur votre ordinateur ou un disque externe.

- **Sauvegarde automatique** : après avoir sélectionné les albums mobiles, les nouvelles photos et vidéos se synchronisent automatiquement avec l’ordinateur
- **Sauvegarde par période** : sauvegarder uniquement les photos et vidéos récentes ou choisir toute la période disponible
- **Sauvegarde par type** : choisir de sauvegarder uniquement les photos, uniquement les vidéos ou les deux par défaut
- **Qualité originale** : conserver les photos et vidéos originales sans compression ni perte de qualité
- **Gestion indépendante de plusieurs appareils** : définir des dossiers de sauvegarde séparés pour différents téléphones, avec des règles de sous-dossiers et de noms de fichiers, par exemple `E:/Backup/iPhone 16 Pro Max/2025/2025-12/2025.12.01_IMG_1234.jpg`
- **Transfert sur le réseau local** : les sauvegardes n’utilisent pas les données mobiles ; la vitesse dépend du réseau local et des performances du disque

![Screenshot: mobile app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/screenshot-mobile.png?raw=true)

## 3. Revivre ses souvenirs grâce à la chronologie

Self Photos organise automatiquement votre bibliothèque selon la date réelle de prise de vue des photos et vidéos et analyse les métadonnées EXIF pour obtenir des dates précises.

- **Accès rapide à une date** : accéder rapidement à une année, un mois ou un jour précis grâce à la chronologie et à la navigation par date
- **Navigation fluide dans les grandes bibliothèques** : une expérience de bureau optimisée qui reste fluide même avec des millions de photos
- **Aperçu au survol** : prévisualiser rapidement les photos et vidéos en passant la souris dessus pour accélérer considérablement la navigation et le tri
- **Lecteur vidéo intégré** : lire les vidéos directement dans l’application ; les formats pris en charge dépendent des codecs du système

![Screenshot: timeline](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/timeline.png?raw=true)

## 4. Reconnaissance faciale

Self Photos reconnaît intelligemment les visages dans les photos et vidéos, regroupe automatiquement une même personne et la rend disponible dans la chronologie, les dossiers et les autres pages.

- **Regroupement automatique des visages** : reconnaître les visages et fusionner les différents visages d’une même personne en une seule personne
- **Nommer et épingler les personnes** : donner un nom aux personnes reconnues et les épingler pour retrouver rapidement les plus importantes
- **Recherche par personne** : rechercher des photos et vidéos par personne dans n’importe quelle liste de photos
- **Trouver les photos de groupe** : sélectionner plusieurs personnes simultanément pour trouver rapidement les photos où elles apparaissent toutes
- **Masquer les personnes indésirables** : masquer une personne en un clic si vous ne souhaitez pas la voir pendant la navigation
- **Photo de couverture personnalisée** : changer la photo de couverture de chaque personne et choisir la plus représentative

![Screenshot: face recognition](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/face-recognition.png?raw=true)

## 5. Reconnaissance d’images par IA et recherche textuelle

Self Photos intègre des modèles d’IA qui comprennent le contenu des photos et vidéos et permettent de rechercher directement dans la bibliothèque en langage naturel.

- **Reconnaissance du contenu par IA** : reconnaître intelligemment les sujets, scènes et détails des photos et vidéos pour alimenter la recherche textuelle
- **Recherche en langage naturel** : saisir une description naturelle pour trouver les photos et vidéos correspondantes, sans étiquetage manuel
- **Requêtes longues et précises** : rechercher des phrases longues comme « un enfant joue avec un ballon bleu tandis que ses parents s’embrassent en arrière-plan » ; l’IA trouvera précisément la photo cible et la placera en première position
- **Catégories intelligentes** : les thèmes courants sont classés par défaut et leurs résultats sont disponibles dès l’ouverture

![Screenshot: AI search](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/vision-search.png?raw=true)

## 6. Détection des doublons et nettoyage en un clic

- **Détection des doublons** : identifier intelligemment les photos et vidéos en double, y compris entre disques locaux et NAS
- **Regroupement par répertoire** : regrouper automatiquement les doublons selon le nom de leur répertoire afin de les examiner et de les nettoyer répertoire par répertoire, comme cela correspond aux doublons généralement présents dans des dossiers similaires
- **Sélection manuelle ou automatique** : choisir manuellement les photos à supprimer dans chaque groupe, ou trier par nom, chemin, taille ou nombre de doublons pour conserver la première, la dernière ou les fichiers du répertoire actuel
- **Nettoyage en un clic** : déplacer les fichiers sélectionnés vers la corbeille après une sélection groupée. Pour les fichiers SMB, qui n’ont pas de corbeille, l’application demande confirmation avant la suppression définitive

![Screenshot: duplicate detection](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/duplicate.png?raw=true)

## 7. Parcourir et gérer les médias selon l’arborescence locale

Des services comme Google Photos et Immich accordent moins d’importance à l’arborescence. En tant que gestionnaire photo local, Self Photos respecte l’organisation existante, qui peut conserver votre historique de classement, comme les groupes de dossiers et les noms de fichiers.

- **Parcourir les dossiers dans les sources de données** : la page des sources de données affiche par défaut les fichiers dans une hiérarchie de dossiers et indique clairement leur emplacement
- **Gérer comme dans l’Explorateur ou le Finder** : déplacer, copier, supprimer et renommer les fichiers directement dans l’application, sans changer d’outil
- **Les futurs agents comprendront la hiérarchie** : le futur agent de gestion photo utilisera l’arborescence comme contexte pour mieux reconnaître les photos et vous aider à les organiser

![Screenshot: folder view](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/folder.png?raw=true)

## 8. Revivre ses souvenirs sur une carte

Si vos photos contiennent des informations de localisation, Self Photos peut les afficher sur une carte.

- **Consulter les photos par lieu** : retrouver rapidement sur la carte les photos et vidéos prises à un endroit donné
- **La confidentialité avant tout** : les informations de localisation sont utilisées uniquement en local pour l’indexation et l’affichage, et ne sont jamais envoyées dans le cloud

![Screenshot: map](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/map-screenshot.png?raw=true)

## 9. Albums

En plus de l’organisation automatique par date, lieu et dossier, Self Photos propose des albums pour rassembler activement des médias de voyage, de famille, de projets, de vacances ou de tout autre thème.

- **Créer des albums thématiques** : rassembler dans un album des photos et vidéos provenant de sources et de dates différentes
- **Conserver les fichiers originaux à leur place** : les albums organisent et affichent les médias sans déplacer les fichiers originaux
- **Idéal pour les collections durables** : mariages, croissance des enfants, voyages, ressources créatives et bien plus peuvent avoir leur propre album

![Screenshot: album](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/album.png?raw=true)

## 10. Notre engagement fort en faveur de la confidentialité

- **La confidentialité avant tout** : Self Photos privilégie le local et la confidentialité. Vos photos, y compris leurs métadonnées, restent toujours en local et ne sont jamais envoyées dans le cloud
- **Garantie de sécurité** : nous ne modifions ni ne supprimons vos photos que si vous le choisissez lors de leur organisation dans l’application. Par défaut, les suppressions déplacent seulement les fichiers vers la corbeille afin de pouvoir récupérer une erreur

# ⬇️ Télécharger

- GitHub (bureau uniquement) : [https://github.com/SelfPhotos/SelfPhotos/releases/latest](https://github.com/SelfPhotos/SelfPhotos/releases/latest)
- Site officiel (application de bureau et Android/iOS) : [https://selfphotos.com/download](https://selfphotos.com/download)
