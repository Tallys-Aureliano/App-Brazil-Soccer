<div align="center">
<h1>Aplicativo Brasileirão Max</h1>
 <div>
  <img src="https://img.shields.io/badge/dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white"/>
 <img src="https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white"/>
</div>
</div>

## Informações Gerais

* Universidade Federal do Rio Grande do Norte.
* Disciplina: Programação Orientada a Objetos 1
* Curso: Sistemas de Informações
* Período: Terceiro.
* Prof: Fabricio Vale
* Colaboradores do projeto: Tallys Aureliano, Italo Mauricio, Gabriel Wallace.

## Introdução ao Projeto

Bem-vindo(a) ao Brasileirão Max projeto desenvolvido em Flutter/Dart! Este aplicativo foi criado com o objetivo de fornecer informações sobre o campeonato brasileiro de futebol e a copa do Brasil de futebol, como partidas e classificação, por meio da integração com uma [API](https://api-futebol.com.br/) de futebol.

O aplicativo para Android, IOS e Web, desenvolvido em Flutter e utilizando toda a potencialidade da ferramenta com o objetivo de mostrar como o Flutter lida com requisições de APIs e como o framework é robusto no desenvolvimento mobile multi-plataforma e Web.

## Como executar:

* Passo 1: Baixe o projeto
      
      git clone git@github.com:italo-mauricio/App-Brasileirao.git
    
* Passo 2: Entre na pasta do projeto utilizando do projeto
      
      cd brasileirao.
      
* Passo 3: Baixe as dependências
 
      flutter pub get
      
* Passo 4: Rode a aplicação

      flutter run -d (seu navegador de preferência) --web-renderer html

## Estrutura do projeto
```
App-Brasileirao
├─ brasileirao
│  ├─ lib
│  │  ├─ assets
│  │  │  ├─ Fontes.dart
│  │  │  ├─ fundo.jpeg
│  │  │  ├─ fundo1.jpg
│  │  │  ├─ Images.dart
│  │  │  ├─ logo.png
│  │  │  ├─ logo1.png
│  │  │  ├─ logo_campeonato.png
│  │  │  └─ logo_vintage.png
│  │  ├─ components
│  │  │  └─ Drawer.dart
│  │  ├─ controllers
│  │  │  └─ BrasileiraoController.dart
│  │  ├─ home
│  │  │  └─ HomePage.dart
│  │  ├─ login
│  │  │  └─ LoginPage.dart
│  │  ├─ main.dart
│  │  ├─ routes
│  │  │  └─ InitialApp.dart
│  │  ├─ sections
│  │  │  ├─ ChaviamentoCopa.dart
│  │  │  ├─ DataTable.dart
│  │  │  ├─ DescriptionsMatches.dart
│  │  │  ├─ Matches.dart
│  │  │  └─ Table.dart
│  │  └─ utils
│  │     └─ keysAuth.dart
```
## Bibliotecas Dart Utilizadas:

:ballot_box_with_check: [Material](https://api.flutter.dev/flutter/material/MaterialApp-class.html): Essa biblioteca contém widgets e recursos específicos para o design de interface do usuário no estilo Material Design, como AppBar, botões, caixas de texto e navegação entre telas.

:ballot_box_with_check: [Cupertino](https://api.flutter.dev/flutter/cupertino/cupertino-library.html): Essa biblioteca contém widgets e recursos específicos para o design de interface do usuário no estilo iOS, como botões, caixas de diálogo e guias de navegação.

:ballot_box_with_check: [Http](https://pub.dev/packages/http): Essa biblioteca permite fazer solicitações HTTP para se comunicar com serviços web e APIs. Ela fornece classes e métodos para realizar solicitações GET, POST, PUT, DELETE, entre outras, e também para lidar com a resposta HTTP.

:ballot_box_with_check: [Convert](https://api.dart.dev/stable/3.0.3/dart-convert/dart-convert-library.html): Essa biblioteca fornece funções para codificar e decodificar dados em formatos como JSON. Ela oferece métodos para converter objetos Dart em strings codificadas e vice-versa, facilitando a comunicação com APIs que utilizam JSON como formato de dados. 

