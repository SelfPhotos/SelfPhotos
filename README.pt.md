<h1 align="center">
  <img src="https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/logo.png?raw=true" height="80" alt="Self Photos Logo" />
  <p>Self Photos</p>
</h1>

<p align="center"><a href="./README.md">English</a> | <a href="./README.zh.md">中文</a> | <a href="./README.de.md">Deutsch</a> | <a href="./README.es.md">Español</a> | <a href="./README.fr.md">Français</a> | <a href="./README.hi.md">हिन्दी</a> | <a href="./README.it.md">Italiano</a> | <a href="./README.ja.md">日本語</a> | Português | <a href="./README.ru.md">Русский</a></p>

**Self Photos** e uma **ferramenta multiplataforma de gestao de fotografias e videos** criada com Rust, disponivel para Windows, macOS, Linux (em breve), Android e iOS.

Pense nele como um Google Photos totalmente local para os seus proprios dispositivos. Ajuda a organizar fotografias e videos do seu computador, discos externos, NAS e telemoveis, mantendo a privacidade e o controlo em primeiro lugar: os seus ficheiros multimidia nao sao enviados para a nuvem e permanecem nos seus dispositivos.

![Screenshot: desktop app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/self-photos-screenshot.png?raw=true)

> 👏 Junte-se ao [Discord](https://discord.gg/VCqXcAz6Js) | Siga-nos no [X(Twitter)](https://x.com/wikkefly)

# ✨ Funcionalidades principais

## 1. Reunir fotografias e videos dispersos

Self Photos analisa fotografias e videos do seu computador, discos externos, unidades ligadas e NAS, e transforma-os numa unica biblioteca local de media.

- **Analise com um clique**: descubra rapidamente fotografias e videos no computador e extraia automaticamente hora de captura, localizacao, tipo de media e outros metadados
- **Fontes de dados flexiveis**: adicione pastas locais, discos externos, localizacoes de rede e mais; a antiga pagina de pastas foi renovada para uma pagina de fontes de dados mais clara com uma vista de lista melhorada
- **Suporte SMB**: analise e indexe fotografias e videos num NAS diretamente por SMB, sem os copiar primeiro para o computador
- **Regras de analise flexiveis**: defina caminhos de analise, exclua pastas, configure regras de caminhos aninhados e filtre icones, imagens de cache e outros ficheiros pequenos irrelevantes por limite de tamanho
- **Monitorizacao de ficheiros e analise manual**: as fontes locais podem ser monitorizadas em tempo real e atualizar o indice dinamicamente; as fontes nao locais podem ser analisadas manualmente quando necessario
- **Detecao de Live Photo**: deteta e associa automaticamente Live Photos entre fontes de dados, mantendo juntas a foto fixa e o clip em movimento

![Screenshot: scan select](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/scan-screenshot.png?raw=true)

## 2. Fazer backup dos albuns moveis para o seu computador

Depois de instalar a app moveil Self Photos, emparelhe-a com a app de escritorio na mesma rede local para fazer backup de fotografias e videos de dispositivos Android e iOS para o seu computador ou para um disco externo.

- **Ligar e fazer backup**: depois de selecionar os albuns moveis, as novas fotografias e videos podem sincronizar-se automaticamente com o computador
- **Backup manual**: escolha fotografias e videos especificos quando precisar de os guardar
- **Backup por intervalo de datas**: guarde apenas fotografias e videos recentes, util para organizar rapidamente novo conteudo
- **Qualidade original**: conserve as fotografias e videos originais sem compressao nem perda de qualidade
- **Gestao independente de varios dispositivos**: defina pastas de backup separadas para telefones diferentes, com regras para subpastas e nomes de ficheiros, por exemplo `E:/Backup/iPhone 16 Pro Max/2025/2025-12/2025.12.01_IMG_1234.jpg`
- **Transferencia por rede local**: os backups nao usam dados moveis; a velocidade depende da sua rede local e do desempenho do disco

![Screenshot: mobile app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/screenshot-mobile.png?raw=true)

## 3. Revisitando memorias pela linha temporal

Self Photos organiza a sua biblioteca pela hora real de captura das fotografias e dos videos, para que possa voltar a um dia, mes ou ano especifico como se estivesse a folhear um diario.

- **Arquivo automatico por data de captura**: fotografias e videos sao organizados pela altura em que foram tirados, e nao apenas pela data de criacao do ficheiro
- **Salto rapido por data**: avance rapidamente para um ano ou mes especifico atraves da linha temporal e da navegacao por data
- **Navegacao fluida em bibliotecas grandes**: experiencia de escritorio otimizada que se mantem rapida mesmo com centenas de milhares de fotografias
- **Pre-visualizacao ao passar o rato**: passe o rato para ver rapidamente fotografias e videos, tornando a navegacao e o filtro muito mais rapidos
- **Leitor de video incorporado**: reproduza videos diretamente na app, com suporte de formato dependente dos codecs do sistema
- **Varias formas de explorar**: use a linha temporal, a estrutura original de pastas, favoritos, a app predefinida do sistema ou revele os ficheiros no gestor de ficheiros do sistema

![Screenshot: timeline](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/timeline.png?raw=true)

## 4. Organizar momentos importantes com albuns

Para alem da organizacao automatica por tempo e estrutura de pastas, o Self Photos inclui albuns para reunir de forma ativa media de viagens, familia, projetos, ferias ou temas.

- **Criar albuns tematicos**: junte fotografias e videos de diferentes fontes e datas num unico album
- **Manter os ficheiros originais no lugar**: os albuns organizam e mostram os media sem mover os ficheiros originais
- **Feito para colecoes duradouras**: casamentos, crescimento dos filhos, viagens, materiais criativos e outras colecoes importantes podem ter o seu proprio album

![Screenshot: album](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/album.png?raw=true)

## 5. Limpar, gerir e desfrutar de uma nova experiencia de escritorio

Self Photos nao serve apenas para ver. Tambem ajuda a gerir a sua biblioteca de media de forma mais eficiente.

- **Detecao de duplicados**: encontre fotografias e videos duplicados de forma inteligente, veja-os em antevisao e apague-os em lote para limpar a biblioteca
- **Novo sistema de design**: uma interface e experiencia de escritorio mais modernas para gerir a longo prazo grandes bibliotecas de fotografias e videos
- **Favoritos e comparacao**: marque rapidamente medias importantes como favoritas e compare fotografias lado a lado na pagina de antevisao
- **Armazenamento e velocidade ilimitados**: a capacidade depende apenas dos seus discos, e a velocidade de transferencia apenas da rede local e do desempenho dos dispositivos
- **Privado e seguro**: a app funciona offline; fotografias e videos nao saem dos seus dispositivos, e o backup movel apenas requer que os dispositivos estejam na mesma rede local

![Screenshot: duplicate detection](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/duplicate.png?raw=true)

# ⬇️ Transferir

Descarregue o mais recente **instalador de escritorio** e a **app movel** no site oficial: [https://selfphotos.com/download](https://selfphotos.com/download)
