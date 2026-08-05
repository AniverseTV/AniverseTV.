<p align="center">
  <img src="screenshots/app-icon.png" width="104" alt="Ícone do AniVerseTV" />
</p>

<p align="center">
  <a href="README.md">English</a> ·
  <strong>Português</strong>
</p>

<h1 align="center">AniVerseTV</h1>

<p align="center">
  <strong>Seu universo de animes, direto no seu Android.</strong><br />
  Catálogo atualizado, player nativo, listas personalizadas e sincronização com AniList.
</p>

<p align="center">
  <a href="https://github.com/AniverseTV/AniverseTV./releases/download/v0.1.0/AniVerseTV.apk">
    <img src="https://img.shields.io/badge/Baixar_APK-8979F2?style=for-the-badge&logo=android&logoColor=white" alt="Baixar o APK do AniVerseTV" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/AniverseTV/AniverseTV./releases/latest"><img src="https://img.shields.io/github/v/release/AniverseTV/AniverseTV.?style=flat-square&label=versão&color=8979F2" alt="Última versão" /></a>
  <img src="https://img.shields.io/badge/Android-8.0%2B-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Android 8.0 ou superior" />
  <img src="https://img.shields.io/badge/Kotlin-Jetpack_Compose-7F52FF?style=flat-square&logo=kotlin&logoColor=white" alt="Feito com Kotlin e Jetpack Compose" />
  <img src="https://img.shields.io/badge/Idioma-Português-blue?style=flat-square" alt="Idioma atual: Português" />
</p>

<p align="center">
  <a href="#instalação">Instalar</a> ·
  <a href="#recursos">Recursos</a> ·
  <a href="#capturas-de-tela">Capturas de tela</a> ·
  <a href="#tecnologias">Tecnologias</a> ·
  <a href="#roadmap">Roadmap</a>
</p>

---

## Sobre o projeto

O **AniVerseTV** é um app nativo em Kotlin/Jetpack Compose para descobrir, acompanhar e assistir
animes no Android. Ele reúne um catálogo integrado ao **AniList**, listas pessoais de marcados e
assistidos, busca inteligente e um player com controles pensados para maratonar sem fricção.

Este repositório é apenas a vitrine do projeto: aqui você encontra informações, novidades e o
link para baixar o APK. 

## Recursos

- **Catálogo em destaque:** seção "Destaque do dia", Top 10 da semana, "Em alta" e "Populares
  agora", com dados sincronizados a partir do catálogo AniList.
- **Busca inteligente:** sugestões instantâneas enquanto você digita, com pôster, ano, formato
  (TV/Movie) e gêneros de cada título.
- **Minha lista:** separação entre títulos **Marcados** (quero assistir) e **Assistidos**, com
  acompanhamento de progresso por episódio.
- **Ficha de detalhes completa:** sinopse, nota, gêneros, classificação indicativa, ano, status
  de lançamento e número de fãs, além de atalhos para trailer, compartilhamento e "Minha lista".
- **Player nativo:** avançar/retroceder 5–15s, lista de episódios lateral, indicador de idioma de
  áudio por episódio (ex. JA-JP), tela cheia, legendas e ajuste de volume.
- **Idioma e região configuráveis:** idioma das legendas, áudio preferido, formato de exibição
  dos títulos (localizado ou original) e idioma das descrições.
- **Tela inicial personalizável:** ligue/desligue seções como Em alta, Populares, Recomendações,
  Lançamentos, Lançamentos Donghua e escolha até 6 categorias favoritas.
- **Múltiplas fontes:** resolução de episódios a partir de diferentes provedores (como KickAss e
  outros compatíveis), com fallback automático quando uma fonte está indisponível.

## Instalação

1. Baixe o APK mais recente pelo botão abaixo ou na aba [Releases](https://github.com/AniverseTV/AniverseTV./releases/latest).
2. Abra o arquivo `AniVerseTV.apk` e, se o Android pedir, permita a instalação de apps de fontes
   desconhecidas para o app usado no download (navegador ou gerenciador de arquivos).
3. Abra o AniVerseTV e comece a explorar — não é necessário criar conta para usar o app.

<p align="center">
  <a href="https://github.com/AniverseTV/AniverseTV./releases/download/v0.1.0/AniVerseTV.apk">
    <img src="https://img.shields.io/badge/Baixar_AniVerseTV.apk-8979F2?style=for-the-badge&logo=android&logoColor=white" alt="Baixar AniVerseTV.apk" />
  </a>
</p>

**Compatibilidade:** Android 8.0 (API 26) ou superior.

## Capturas de tela

<table>
  <tr>
    <th width="33%">Início</th>
    <th width="33%">Destaque do dia</th>
    <th width="33%">Em alta</th>
  </tr>
  <tr>
    <td><a href="screenshots/5.jpg"><img src="screenshots/5.jpg" width="100%" alt="Tela inicial do AniVerseTV com Top 10 da semana" /></a></td>
    <td><a href="screenshots/14.jpg"><img src="screenshots/14.jpg" width="100%" alt="Destaque do dia no AniVerseTV" /></a></td>
    <td><a href="screenshots/15.jpg"><img src="screenshots/15.jpg" width="100%" alt="Seção Em alta do AniVerseTV" /></a></td>
  </tr>
</table>

<table>
  <tr>
    <th width="33%">Busca</th>
    <th width="33%">Minha lista</th>
    <th width="33%">Detalhes do título</th>
  </tr>
  <tr>
    <td><a href="screenshots/7.jpg"><img src="screenshots/7.jpg" width="100%" alt="Busca de animes no AniVerseTV" /></a></td>
    <td><a href="screenshots/8.jpg"><img src="screenshots/8.jpg" width="100%" alt="Lista de assistidos no AniVerseTV" /></a></td>
    <td><a href="screenshots/10.jpg"><img src="screenshots/10.jpg" width="100%" alt="Ficha de detalhes de um anime no AniVerseTV" /></a></td>
  </tr>
</table>

<p align="center">
  <strong>Player nativo com lista de episódios, controles de avanço e tela cheia</strong><br /><br />
  <a href="screenshots/3.jpg"><img src="screenshots/3.jpg" width="80%" alt="Player de vídeo do AniVerseTV" /></a>
</p>

<table>
  <tr>
    <th width="50%">Idioma, áudio e legendas</th>
    <th width="50%">Personalização da tela inicial</th>
  </tr>
  <tr>
    <td><a href="screenshots/1.jpg"><img src="screenshots/1.jpg" width="100%" alt="Configurações de idioma e região do AniVerseTV" /></a></td>
    <td><a href="screenshots/16.jpg"><img src="screenshots/16.jpg" width="100%" alt="Configurações da tela inicial do AniVerseTV" /></a></td>
  </tr>
</table>

## Tecnologias

- **Kotlin** com **Jetpack Compose** para toda a interface.
- **Navigation Compose** para a navegação entre telas.
- **Compose for TV** (`tv-foundation` / `tv-material`) já integrado ao projeto, preparando o
  terreno para a versão de TV.
- Arquitetura organizada em camadas de **presentation**, **domain** e **data**, facilitando a
  evolução do catálogo, do player e da integração com fontes externas.

## Servidores e fontes de conteúdo

O AniVerseTV não hospeda nenhum vídeo. Os episódios são resolvidos em tempo real a partir de
provedores de terceiros (como KickAss e outras fontes compatíveis), com seleção automática do
melhor servidor disponível para cada episódio. A disponibilidade pode variar por título, idioma,
região e status do provedor.

O catálogo de informações (sinopses, notas, gêneros, imagens e status de lançamento) é
sincronizado a partir do **AniList**.

## Roadmap

- [ ] Suporte ao **idioma inglês** na interface do app.
- [ ] Lançamento da **versão para TV** (Android TV / Fire TV), já com a base em Compose for TV.
- [x] Versão para dispositivos móveis (disponível para download nesta página).

## Comunidade e suporte

Encontrou um problema ou tem uma sugestão? Abra uma [issue no GitHub](https://github.com/AniverseTV/AniverseTV./issues/new)
descrevendo o comportamento esperado, o que aconteceu e, se possível, o modelo do seu
aparelho e a versão do Android.

## Aviso

O AniVerseTV é um projeto pessoal e educacional. Não possui vínculo com o AniList, MyAnimeList
ou qualquer provedor de streaming. O app não hospeda nenhum conteúdo de vídeo; os streams são
resolvidos a partir de provedores de terceiros no momento da reprodução. A disponibilidade e a
legalidade podem variar conforme a região, e o uso é de responsabilidade de cada usuário perante
as leis e termos aplicáveis.
