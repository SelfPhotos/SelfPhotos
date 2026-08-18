<h1 align="center">
  <img src="https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/logo.png?raw=true" height="80" alt="Self Photos Logo" />
  <p>Self Photos</p>
</h1>

<p align="center"><a href="./README.md">English</a> | <a href="./README.zh.md">中文</a> | <a href="./README.de.md">Deutsch</a> | <a href="./README.es.md">Español</a> | <a href="./README.fr.md">Français</a> | <a href="./README.hi.md">हिन्दी</a> | <a href="./README.it.md">Italiano</a> | <a href="./README.ja.md">日本語</a> | Português | <a href="./README.ru.md">Русский</a></p>

**Self Photos** é uma **aplicação de ambiente de trabalho multiplataforma para gestão de fotografias e vídeos**, desenvolvida em Rust. Suporta Windows, macOS e Linux (em breve) e disponibiliza aplicações para Android e iOS para fazer cópias de segurança dos álbuns do telemóvel no computador. As principais funcionalidades incluem:

## ✨ Funcionalidades principais

- 💽 **Biblioteca multimédia unificada**: analise fotografias e vídeos do computador, de discos externos e do NAS e reúna-os numa biblioteca local.
- 📱 **Cópia de segurança automática do telemóvel**: associe a aplicação móvel à aplicação de ambiente de trabalho para guardar automaticamente no computador as fotografias e vídeos originais do Android e iOS.
- 🗓️ **Navegação pela linha temporal**: organize automaticamente por hora de captura, salte rapidamente para datas e navegue com fluidez por bibliotecas grandes.
- 😀 **Reconhecimento facial**: agrupe automaticamente a mesma pessoa, com funcionalidades para nomear, pesquisar e encontrar fotografias de grupo com várias pessoas.
- 🔍 **Pesquisa de imagens com IA**: descreva o conteúdo em linguagem natural para encontrar fotografias e vídeos com precisão.
- 🧹 **Limpeza de duplicados**: detete ficheiros duplicados entre discos locais e NAS e mova-os para a reciclagem com um clique.
- 📁 **Preservação da estrutura de pastas**: mostre os ficheiros pela estrutura de pastas local e mova, copie, elimine e renomeie ficheiros diretamente.
- 🗺️ **Memórias no mapa**: reveja fotografias no mapa por localização; a informação de localização permanece apenas localmente.
- 📚 **Álbuns temáticos**: reúna fotografias de diferentes fontes em álbuns sem mover os ficheiros originais.
- 🔒 **Compromisso com a privacidade**: as fotografias permanecem sempre localmente e nunca são enviadas para a nuvem.

![Screenshot: desktop app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/self-photos-screenshot.png?raw=true)

> 👏 Junte-se ao [Discord](https://discord.gg/VCqXcAz6Js) | Siga-nos no [X(Twitter)](https://x.com/wikkefly)

## 1. Analisar discos de PC, Mac, Linux e fotografias do NAS e reuni-los num só lugar

O Self Photos pode analisar fotografias e vídeos do computador, de discos externos e do NAS e indexar memórias dispersas numa biblioteca multimédia local.

- **Criar uma biblioteca local unificada**: extrair automaticamente a hora de captura, a localização e outras informações dos metadados EXIF e apresentá-las nas páginas da linha temporal e do mapa
- **Analisar multimédia no NAS**: analisar e indexar fotografias e vídeos no NAS diretamente através de SMB, sem os copiar primeiro para o computador
- **Regras de análise flexíveis**: especifique caminhos, exclua pastas e configure regras para caminhos aninhados; defina um limite de tamanho para filtrar ícones, imagens de cache e outros ficheiros pequenos
- **Monitorização de ficheiros e análise manual**: monitorize em tempo real as alterações nos discos locais (adicionados, eliminados ou movidos) e atualize automaticamente a biblioteca; atualize fontes não locais, como o NAS, com uma análise de um clique
- **Deteção de Live Photo**: quando uma fotografia e um vídeo com o mesmo nome são encontrados na mesma pasta, associe-os automaticamente como Live Photo

![Screenshot: scan select](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/scan-screenshot.png?raw=true)

## 2. Fazer cópias de segurança dos álbuns móveis no computador

Instale a aplicação móvel Self Photos e associe-a à aplicação de ambiente de trabalho na mesma rede local para guardar fotografias e vídeos de dispositivos Android e iOS no computador ou num disco externo.

- **Cópia automática**: depois de selecionar os álbuns móveis, as fotografias e vídeos novos são sincronizados automaticamente com o computador
- **Cópia por intervalo de datas**: guarde apenas fotografias e vídeos de um período recente ou escolha o intervalo completo
- **Cópia por tipo**: escolha guardar apenas fotografias, apenas vídeos ou ambos por predefinição
- **Qualidade original**: guarde fotografias e vídeos originais sem compressão nem perda de qualidade
- **Gestão independente de vários dispositivos**: defina pastas de cópia separadas para telefones diferentes, com regras para subpastas e nomes de ficheiros, como `E:/Backup/iPhone 16 Pro Max/2025/2025-12/2025.12.01_IMG_1234.jpg`
- **Transferência pela rede local**: as cópias não utilizam dados móveis; a velocidade depende da rede local e do desempenho do disco

![Screenshot: mobile app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/screenshot-mobile.png?raw=true)

## 3. Rever memórias através da linha temporal

O Self Photos organiza automaticamente a biblioteca pela hora real de captura das fotografias e vídeos e analisa os metadados EXIF para extrair horas de captura precisas.

- **Acesso rápido a datas**: salte rapidamente para um determinado ano, mês ou dia através da linha temporal e da navegação por datas
- **Navegação fluida em bibliotecas grandes**: uma experiência de ambiente de trabalho otimizada que permanece fluida mesmo com milhões de fotografias
- **Pré-visualização ao passar o cursor**: pré-visualize rapidamente fotografias e vídeos ao passar o cursor, tornando a navegação e a filtragem muito mais rápidas
- **Leitor de vídeo integrado**: reproduza vídeos diretamente na aplicação; o suporte de formatos depende dos codecs do sistema

![Screenshot: timeline](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/timeline.png?raw=true)

## 4. Reconhecimento facial

O Self Photos reconhece inteligentemente rostos em fotografias e vídeos, agrupa automaticamente a mesma pessoa numa pessoa gerível e disponibiliza-a na linha temporal, nas pastas e noutras páginas.

- **Agrupamento automático de rostos**: reconheça rostos e combine vários rostos da mesma pessoa numa só pessoa para uma apresentação centralizada
- **Dar nome e fixar pessoas**: dê nomes às pessoas reconhecidas e fixe-as para encontrar rapidamente as mais importantes
- **Pesquisar por pessoa**: pesquise fotografias e vídeos por pessoa em qualquer lista de fotografias
- **Encontrar fotografias de grupo**: selecione várias pessoas em simultâneo para encontrar rapidamente fotografias que incluam todas elas
- **Ocultar pessoas indesejadas**: oculte uma pessoa com um clique se não quiser que apareça durante a navegação
- **Capa personalizada da pessoa**: altere a capa de cada pessoa e escolha a mais representativa

![Screenshot: face recognition](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/face-recognition.png?raw=true)

## 5. Reconhecimento de imagens com IA e pesquisa por texto

O Self Photos inclui modelos de IA integrados que compreendem o conteúdo de fotografias e vídeos e permitem pesquisar diretamente na biblioteca utilizando linguagem natural.

- **Reconhecimento de conteúdo com IA**: reconheça inteligentemente motivos, cenas e detalhes em fotografias e vídeos para alimentar a pesquisa por texto
- **Pesquisa em linguagem natural**: introduza linguagem natural para pesquisar fotografias e vídeos correspondentes, sem etiquetas manuais
- **Consultas longas e precisas**: pesquise frases longas, como «uma criança brinca com um balão azul enquanto os pais se beijam ao fundo»; a IA encontrará a fotografia pretendida e colocá-la-á em primeiro lugar
- **Categorias inteligentes**: os temas comuns são categorizados por predefinição e os resultados ficam disponíveis assim que os abre

![Screenshot: AI search](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/vision-search.png?raw=true)

## 6. Deteção de duplicados e limpeza com um clique

- **Deteção de duplicados**: identifique inteligentemente fotografias e vídeos duplicados, incluindo duplicados entre discos locais e NAS
- **Agrupar por diretório**: agregue automaticamente os duplicados pelo nome do diretório onde se encontram, para os rever e limpar diretório a diretório; isto corresponde aos padrões reais de duplicação em diretórios semelhantes
- **Seleção manual ou automática**: em cada grupo de duplicados, escolha manualmente o que eliminar ou ordene por nome, caminho, tamanho ou quantidade de duplicados e conserve o primeiro, o último ou os ficheiros do diretório atual
- **Limpeza com um clique**: depois da seleção em lote, mova os ficheiros selecionados para a reciclagem. Para ficheiros SMB, que não têm reciclagem, a aplicação pede confirmação antes da eliminação permanente

![Screenshot: duplicate detection](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/duplicate.png?raw=true)

## 7. Navegar e gerir pela estrutura de pastas local

Serviços como o Google Photos e o Immich dão menos importância à estrutura de pastas. Como gestor de fotografias local, o Self Photos respeita a estrutura que já possui, pois ela pode preservar a sua organização anterior, como agrupamentos de pastas e nomes de ficheiros.

- **Navegar por pastas nas fontes de dados**: a página de fontes de dados mostra os ficheiros numa hierarquia de pastas por predefinição, apresentando claramente a sua localização
- **Gerir como no Explorador de Ficheiros ou Finder**: mova, copie, elimine e renomeie ficheiros diretamente na aplicação, sem mudar para o Explorador ou Finder
- **Os futuros agentes compreenderão a hierarquia**: o futuro agente de gestão de fotografias utilizará a hierarquia das pastas como contexto para reconhecer melhor as fotografias e ajudar na organização

![Screenshot: folder view](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/folder.png?raw=true)

## 8. Rever memórias num mapa

Se as suas fotografias incluírem informações de localização, o Self Photos pode apresentá-las num mapa.

- **Rever fotografias por local**: encontre rapidamente no mapa fotografias e vídeos captados numa determinada localização
- **Privacidade em primeiro lugar**: a informação de localização é utilizada apenas localmente para indexação e apresentação e nunca é enviada para a nuvem

![Screenshot: map](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/map-screenshot.png?raw=true)

## 9. Álbuns

Além da organização automática por tempo, localização e pasta, o Self Photos inclui álbuns para reunir ativamente multimédia de viagens, família, projetos, férias ou temas.

- **Criar álbuns temáticos**: reúna fotografias e vídeos de diferentes fontes e datas num único álbum
- **Manter os ficheiros originais no lugar**: os álbuns organizam e apresentam os ficheiros sem mover os originais
- **Ótimo para coleções duradouras**: casamentos, crescimento dos filhos, coleções de viagens, recursos criativos e muito mais podem ter o seu próprio álbum

![Screenshot: album](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/album.png?raw=true)

## 10. O nosso forte compromisso com a privacidade

- **Privacidade em primeiro lugar**: o Self Photos privilegia o uso local e a privacidade. As suas fotografias, incluindo os metadados, permanecem sempre localmente e nunca são enviadas para a nuvem
- **Garantia de segurança**: nunca modificamos nem eliminamos as suas fotografias, exceto quando escolhe fazê-lo ao organizá-las na aplicação. Por predefinição, as eliminações apenas movem os ficheiros para a reciclagem, permitindo recuperar eventuais enganos

# ⬇️ Transferir

- GitHub (apenas ambiente de trabalho): [https://github.com/SelfPhotos/SelfPhotos/releases/latest](https://github.com/SelfPhotos/SelfPhotos/releases/latest)
- Site oficial (aplicação de ambiente de trabalho e Android/iOS): [https://selfphotos.com/download](https://selfphotos.com/download)
