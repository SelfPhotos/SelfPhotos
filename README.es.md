<h1 align="center">
  <img src="https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/logo.png?raw=true" height="80" alt="Self Photos Logo" />
  <p>Self Photos</p>
</h1>

<p align="center"><a href="./README.md">English</a> | <a href="./README.zh.md">中文</a> | <a href="./README.de.md">Deutsch</a> | Español | <a href="./README.fr.md">Français</a> | <a href="./README.hi.md">हिन्दी</a> | <a href="./README.it.md">Italiano</a> | <a href="./README.ja.md">日本語</a> | <a href="./README.pt.md">Português</a> | <a href="./README.ru.md">Русский</a></p>

**Self Photos** es una **aplicación de escritorio multiplataforma para gestionar fotos y vídeos**, creada con Rust. Es compatible con Windows, macOS y Linux (próximamente), y cuenta con aplicaciones para Android e iOS que permiten hacer copias de seguridad de los álbumes del móvil en el ordenador. Sus funciones principales son:

## ✨ Funciones principales

- 💽 **Biblioteca multimedia unificada**: escanea fotos y vídeos del ordenador, discos externos y NAS, y los reúne en una biblioteca local.
- 📱 **Copia de seguridad automática del móvil**: vincula la aplicación móvil con la de escritorio para guardar automáticamente las fotos y vídeos originales de Android e iOS en el ordenador.
- 🗓️ **Navegación por línea de tiempo**: organiza automáticamente por fecha de captura, permite saltar rápidamente a cualquier fecha y navegar con fluidez por bibliotecas grandes.
- 😀 **Reconocimiento facial**: agrupa automáticamente a la misma persona, con opciones para nombrarla, buscarla y encontrar fotos de grupo con varias personas.
- 🔍 **Búsqueda de imágenes con IA**: describe el contenido en lenguaje natural para encontrar fotos y vídeos con precisión.
- 🧹 **Limpieza de duplicados**: detecta archivos duplicados entre discos locales y NAS y los mueve a la papelera con un clic.
- 📁 **Conservación de la estructura de carpetas**: muestra los archivos según la estructura de carpetas local y permite moverlos, copiarlos, eliminarlos y cambiarles el nombre directamente.
- 🗺️ **Recuerdos en el mapa**: revisa las fotos en un mapa por ubicación; la información de ubicación permanece solo en local.
- 📚 **Álbumes temáticos**: reúne fotos de distintas fuentes en álbumes sin mover los archivos originales.
- 🔒 **Compromiso con la privacidad**: las fotos permanecen siempre en local y nunca se suben a la nube.

![Screenshot: desktop app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/self-photos-screenshot.png?raw=true)

> 👏 Únete a [Discord](https://discord.gg/VCqXcAz6Js) | Síguenos en [X(Twitter)](https://x.com/wikkefly)

## 1. Escanear discos de PC, Mac, Linux y NAS y reunir las fotos

Self Photos puede escanear fotos y vídeos del ordenador, discos externos y NAS, e indexar los recuerdos dispersos en una única biblioteca multimedia local.

- **Crear una biblioteca local unificada**: extrae automáticamente de los metadatos EXIF la fecha de captura, la ubicación y otra información, y la muestra en las páginas de línea de tiempo y mapa
- **Escanear contenido del NAS**: escanea e indexa fotos y vídeos del NAS directamente mediante SMB, sin copiarlos antes al ordenador
- **Reglas de escaneo flexibles**: especifica rutas, excluye carpetas y configura reglas para rutas anidadas; establece un umbral de tamaño para filtrar iconos, imágenes de caché y otros archivos pequeños
- **Supervisión de archivos y escaneo manual**: supervisa en tiempo real los cambios de los discos locales (archivos añadidos, eliminados o movidos) y actualiza la biblioteca automáticamente; actualiza fuentes no locales como NAS con un clic
- **Detección de Live Photo**: cuando encuentra una foto y un vídeo con el mismo nombre en la misma carpeta, los asocia automáticamente como Live Photo

![Screenshot: scan select](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/scan-screenshot.png?raw=true)

## 2. Hacer copias de seguridad de los álbumes móviles en el ordenador

Instala la aplicación móvil Self Photos y vincúlala con la aplicación de escritorio en la misma red local para guardar fotos y vídeos de dispositivos Android e iOS en el ordenador o en un disco externo.

- **Copia automática**: después de seleccionar los álbumes móviles, las fotos y vídeos nuevos se sincronizan automáticamente con el ordenador
- **Copia por intervalo de fechas**: guarda solo fotos y vídeos de un periodo reciente o selecciona todo el intervalo de tiempo
- **Copia por tipo**: elige guardar solo fotos, solo vídeos o ambos de forma predeterminada
- **Calidad original**: conserva las fotos y vídeos originales sin compresión ni pérdida de calidad
- **Gestión independiente de varios dispositivos**: configura carpetas de copia separadas para cada teléfono y reglas para subcarpetas y nombres de archivo, como `E:/Backup/iPhone 16 Pro Max/2025/2025-12/2025.12.01_IMG_1234.jpg`
- **Transferencia por red local**: las copias no consumen datos móviles; la velocidad depende de la red local y del rendimiento del disco

![Screenshot: mobile app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/screenshot-mobile.png?raw=true)

## 3. Revivir recuerdos con la línea de tiempo

Self Photos organiza automáticamente la biblioteca según la fecha real de captura de las fotos y vídeos y analiza sus metadatos EXIF para obtener fechas precisas.

- **Saltar rápidamente a una fecha**: ve rápidamente a un año, mes o día concretos mediante la línea de tiempo y la navegación por fechas
- **Navegación fluida en bibliotecas grandes**: experiencia de escritorio optimizada que sigue siendo fluida incluso con millones de fotos
- **Vista previa al pasar el cursor**: previsualiza fotos y vídeos rápidamente al pasar el cursor para navegar y filtrar mucho más rápido
- **Reproductor de vídeo integrado**: reproduce vídeos directamente en la aplicación; la compatibilidad de formatos depende de los códecs del sistema

![Screenshot: timeline](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/timeline.png?raw=true)

## 4. Reconocimiento facial

Self Photos reconoce de forma inteligente los rostros de fotos y vídeos, agrupa automáticamente a la misma persona como una persona gestionable y la hace disponible en la línea de tiempo, las carpetas y otras páginas.

- **Agrupación automática de rostros**: reconoce rostros de forma inteligente y fusiona varias caras de la misma persona en una sola para mostrarlas juntas
- **Nombrar y fijar personas**: pon nombre a las personas reconocidas y fíjalas para encontrar rápidamente a las importantes
- **Buscar por persona**: busca fotos y vídeos por persona desde cualquier lista de fotos
- **Encontrar fotos de grupo**: selecciona varias personas a la vez para encontrar rápidamente fotos que incluyan a todas
- **Ocultar personas**: oculta con un clic a cualquier persona que no quieras ver mientras navegas
- **Portada personalizada**: cambia la portada de cada persona y elige la imagen más representativa

![Screenshot: face recognition](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/face-recognition.png?raw=true)

## 5. Reconocimiento de imágenes con IA y búsqueda por texto

Self Photos incluye modelos de IA integrados que entienden el contenido de fotos y vídeos y permiten buscar directamente en la biblioteca mediante lenguaje natural.

- **Reconocimiento del contenido con IA**: reconoce de forma inteligente sujetos, escenas y detalles de fotos y vídeos para hacer posible la búsqueda por texto
- **Búsqueda en lenguaje natural**: introduce una descripción natural para encontrar fotos y vídeos coincidentes, sin etiquetado manual
- **Consultas largas y precisas**: busca frases largas como «un niño juega con un globo azul mientras sus padres se besan al fondo»; la IA encontrará la foto correcta y la colocará en primer lugar
- **Categorías inteligentes**: los temas habituales se clasifican de forma predeterminada y muestran resultados nada más abrirlos

![Screenshot: AI search](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/vision-search.png?raw=true)

## 6. Detección de duplicados y limpieza con un clic

- **Detección de duplicados**: identifica fotos y vídeos duplicados, incluidos los duplicados entre discos locales y NAS
- **Agrupar por directorio**: agrupa automáticamente los duplicados por el nombre del directorio en el que están para revisarlos y limpiarlos directorio por directorio; así se ajusta a los patrones habituales de duplicación entre carpetas similares
- **Selección manual o automática**: elige manualmente qué archivos eliminar en cada grupo o clasifícalos por nombre, ruta, tamaño o cantidad de duplicados y conserva el primero, el último o los archivos del directorio actual
- **Limpieza con un clic**: tras la selección por lotes, mueve los archivos elegidos a la papelera. En archivos SMB, que no tienen papelera, la aplicación pedirá confirmación antes de eliminarlos definitivamente

![Screenshot: duplicate detection](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/duplicate.png?raw=true)

## 7. Explorar y gestionar mediante la estructura de carpetas local

Servicios como Google Photos e Immich restan importancia a la estructura de carpetas. Como gestor de fotos local, Self Photos respeta la estructura que ya tienes, porque puede conservar tu forma histórica de organización, como la agrupación de carpetas y los nombres de archivo.

- **Explorar por carpetas en las fuentes de datos**: la página de fuentes de datos muestra los archivos por defecto en una jerarquía de carpetas y deja claro dónde se encuentran
- **Gestionar como en un explorador de archivos o Finder**: mueve, copia, elimina y cambia el nombre de los archivos directamente en la aplicación, sin cambiar al Explorador o Finder
- **Los futuros agentes entenderán la jerarquía**: cuando llegue el futuro agente de gestión fotográfica, usará la jerarquía de carpetas como contexto para reconocer mejor las fotos y ayudarte a organizarlas

![Screenshot: folder view](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/folder.png?raw=true)

## 8. Revivir recuerdos en un mapa

Si tus fotos incluyen información de ubicación, Self Photos puede mostrarlas en un mapa.

- **Revisar fotos por lugar**: encuentra rápidamente en el mapa fotos y vídeos tomados en una ubicación
- **Privacidad ante todo**: la información de ubicación se usa solo localmente para indexar y mostrar contenido, y nunca se sube a la nube

![Screenshot: map](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/map-screenshot.png?raw=true)

## 9. Álbumes

Además de la organización automática por fecha, ubicación y carpeta, Self Photos incluye álbumes para reunir activamente contenido de viajes, familia, proyectos, vacaciones o cualquier tema.

- **Crear álbumes temáticos**: reúne fotos y vídeos de distintas fuentes y fechas en un solo álbum
- **Conservar los archivos originales en su sitio**: los álbumes organizan y muestran el contenido sin mover los archivos originales
- **Ideales para colecciones a largo plazo**: bodas, crecimiento de los hijos, colecciones de viajes, recursos creativos y mucho más pueden tener su propio álbum

![Screenshot: album](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/album.png?raw=true)

## 10. Nuestro firme compromiso con la privacidad

- **Privacidad ante todo**: Self Photos prioriza el uso local y la privacidad. Tus fotos permanecen siempre en local, incluidos sus metadatos, y nunca se suben a la nube
- **Garantía de seguridad**: nunca modificamos ni eliminamos tus fotos salvo que tú lo elijas al organizarlas en la aplicación. Por defecto, las eliminaciones solo mueven los archivos a la papelera para que puedas recuperarlos si te equivocas

# ⬇️ Descargar

- GitHub (solo escritorio): [https://github.com/SelfPhotos/SelfPhotos/releases/latest](https://github.com/SelfPhotos/SelfPhotos/releases/latest)
- Sitio web oficial (aplicación de escritorio y Android/iOS): [https://selfphotos.com/download](https://selfphotos.com/download)
