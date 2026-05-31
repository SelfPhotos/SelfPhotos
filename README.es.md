<h1 align="center">
  <img src="https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/logo.png?raw=true" height="80" alt="Self Photos Logo" />
  <p>Self Photos</p>
</h1>

<p align="center"><a href="./README.md">English</a> | <a href="./README.zh.md">中文</a> | <a href="./README.de.md">Deutsch</a> | Español | <a href="./README.fr.md">Français</a> | <a href="./README.hi.md">हिन्दी</a> | <a href="./README.it.md">Italiano</a> | <a href="./README.ja.md">日本語</a> | <a href="./README.pt.md">Português</a> | <a href="./README.ru.md">Русский</a></p>

**Self Photos** es una **herramienta multiplataforma para gestionar fotos y videos** creada con Rust, disponible para Windows, macOS, Linux (pronto), Android e iOS.

Piensalo como un Google Photos totalmente local para tus propios dispositivos. Te ayuda a organizar fotos y videos de tu ordenador, discos externos, NAS y telefonos, poniendo la privacidad y el control en primer plano: tus medios no se suben a la nube y permanecen en tus propios dispositivos.

![Screenshot: desktop app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/self-photos-screenshot.png?raw=true)

> 👏 Unete a [Discord](https://discord.gg/VCqXcAz6Js) | Siguenos en [X(Twitter)](https://x.com/wikkefly)

# ✨ Funciones principales

## 1. Reunir fotos y videos dispersos

Self Photos analiza fotos y videos de tu ordenador, discos externos, unidades conectadas y NAS, y los convierte en una sola biblioteca local de medios.

- **Analisis con un clic**: descubre rapidamente fotos y videos en tu ordenador y extrae automaticamente hora de captura, ubicacion, tipo de medio y otros metadatos
- **Fuentes de datos flexibles**: agrega carpetas locales, discos externos, ubicaciones de red y mas; la antigua pagina de carpetas se ha transformado en una pagina de fuentes de datos mas clara con una mejor vista de lista
- **Compatibilidad SMB**: analiza e indexa fotos y videos en un NAS directamente por SMB sin copiarlos primero al ordenador
- **Reglas de analisis flexibles**: define rutas de analisis, excluye carpetas, configura reglas de rutas anidadas y filtra iconos, imagenes de cache y otros archivos pequenos irrelevantes por tamano
- **Supervision de archivos y analisis manual**: las fuentes locales pueden supervisarse en tiempo real y actualizar el indice dinamicamente; las fuentes no locales pueden analizarse manualmente cuando haga falta
- **Deteccion de Live Photo**: detecta y vincula automaticamente Live Photos entre fuentes de datos, manteniendo juntas la foto fija y el clip en movimiento

![Screenshot: scan select](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/scan-screenshot.png?raw=true)

## 2. Hacer copia de seguridad de los albumes del movil en tu ordenador

Despues de instalar la app movil de Self Photos, emparejala con la aplicacion de escritorio en la misma red local para respaldar fotos y videos de dispositivos Android e iOS en tu ordenador o en un disco externo.

- **Conectar y respaldar**: tras seleccionar los albumes del movil, las fotos y videos nuevos pueden sincronizarse automaticamente con tu ordenador
- **Copia manual**: elige fotos y videos concretos cuando necesites respaldarlos
- **Respaldo por rango de fechas**: guarda solo fotos y videos recientes, util para ordenar rapidamente contenido nuevo
- **Calidad original**: guarda fotos y videos originales sin compresion ni perdida de calidad
- **Gestion independiente de varios dispositivos**: define carpetas de respaldo separadas para distintos telefonos, con reglas para subcarpetas y nombres, por ejemplo `E:/Backup/iPhone 16 Pro Max/2025/2025-12/2025.12.01_IMG_1234.jpg`
- **Transferencia por red local**: los respaldos no usan datos moviles; la velocidad depende de tu red local y del rendimiento del disco

![Screenshot: mobile app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/screenshot-mobile.png?raw=true)

## 3. Revisitar recuerdos por linea de tiempo

Self Photos organiza tu biblioteca segun la hora real de captura de fotos y videos, para que puedas volver a un dia, mes o ano concreto como si pasaras las paginas de un diario.

- **Archivo automatico por fecha de captura**: las fotos y videos se ordenan por cuando fueron tomados, no solo por la fecha de creacion del archivo
- **Salto rapido por fecha**: navega rapidamente a un ano o mes concreto con la linea de tiempo y la navegacion por fechas
- **Navegacion fluida en bibliotecas grandes**: experiencia de escritorio optimizada que sigue siendo rapida incluso con cientos de miles de fotos
- **Vista previa al pasar el cursor**: pasa el raton por encima para previsualizar fotos y videos, acelerando mucho la exploracion y el filtrado
- **Reproductor de video integrado**: reproduce videos directamente en la app, con soporte de formato segun los codecs de tu sistema
- **Varias formas de explorar**: usa la linea de tiempo, la estructura original de carpetas, favoritos, la aplicacion predeterminada del sistema o abre la ubicacion en el gestor de archivos

![Screenshot: timeline](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/timeline.png?raw=true)

## 4. Organizar momentos importantes con albumes

Ademas de la organizacion automatica por tiempo y estructura de carpetas, Self Photos incluye albumes para reunir de forma activa medios de viajes, familia, proyectos, vacaciones o temas concretos.

- **Crear albumes tematicos**: agrupa fotos y videos de distintas fuentes y fechas en un solo album
- **Mantener los archivos originales en su lugar**: los albumes organizan y muestran los medios sin mover los archivos originales
- **Pensado para colecciones duraderas**: bodas, crecimiento de los hijos, viajes, recursos creativos y otras colecciones importantes pueden tener su propio album

![Screenshot: album](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/album.png?raw=true)

## 5. Limpiar, gestionar y disfrutar de una nueva experiencia de escritorio

Self Photos no es solo para ver. Tambien te ayuda a gestionar tu biblioteca de medios con mas eficiencia.

- **Deteccion de duplicados**: encuentra de forma inteligente fotos y videos duplicados, previsualizalos y borralos por lotes para limpiar tu biblioteca
- **Nuevo sistema de diseno**: una interfaz y experiencia de escritorio mas moderna para gestionar durante mucho tiempo bibliotecas grandes de fotos y videos
- **Favoritos y comparacion**: marca rapidamente medios importantes como favoritos y compara fotos lado a lado en la vista previa
- **Almacenamiento y velocidad ilimitados**: la capacidad solo esta limitada por tus discos, y la velocidad de transferencia solo por tu red local y el rendimiento de los dispositivos
- **Privado y seguro**: la app funciona sin conexion; las fotos y videos no salen de tus dispositivos, y la copia movil solo requiere que los dispositivos esten en la misma red local

![Screenshot: duplicate detection](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/duplicate.png?raw=true)

# ⬇️ Descargar

Descarga el ultimo **instalador de escritorio** y la **app movil** desde la web oficial: [https://selfphotos.com/download](https://selfphotos.com/download)
