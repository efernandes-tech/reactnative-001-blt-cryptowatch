<h1 align="center">
    <a href="#" alt="site">My Template Repository</a>
</h1>

<h3 align="center">
    Meu repositório base para projetos
</h3>

<p align="center">
    <a href="https://github.com/efernandes-tech/proj-007-my-template-repository/commits/main">
        <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/efernandes-tech/proj-007-my-template-repository">
    </a>
    <img alt="Repository size" src="https://img.shields.io/github/repo-size/efernandes-tech/proj-007-my-template-repository">
    <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
    <a href="https://edersonfernandes.com.br">
        <img alt="feito por @efernandes.tech" src="https://img.shields.io/badge/Feito%20por-@efernandes.tech-%2360F6AD">
    </a>
</p>

<h4 align="center">
    Status: Concluído
</h4>

<p align="center">
    <a href="#sobre">Sobre</a> •
    <a href="#funcionalidades">Funcionalidades</a> •
    <a href="#layout">Layout</a> •
    <a href="#como-executar">Como executar</a> •
    <a href="#tecnologias">Tecnologias</a> •
    <a href="#contribuidores">Contribuidores</a> •
    <a href="#autor">Autor</a> •
    <a href="#licença">Licença</a>
</p>

## Sobre

My Template Repository - descrição sobre o projeto

---

## Funcionalidades

-   [x] Funcionalidade Um:

    -   [x] descrição da tarefa
    -   [x] descrição da tarefa
    -   [x] descrição da tarefa
    -   [x] descrição da tarefa:
        -   tópico 1
        -   tópico 2
        -   tópico 3

-   [ ] Funcionalidade Dois:

    -   [x] descrição da tarefa
    -   [ ] descrição da tarefa
    -   [ ] descrição da tarefa

---

## Layout

O layout da aplicação está disponível no Figma:

<a href="https://www.figma.com/file/1SxgOMojOB2zYT0Mdk28lB/MyTemplateRepository?node-id=136%3A546">
  <img alt="Feito por @efernandes.tech" src="https://img.shields.io/badge/Acessar%20Layout%20-Figma-%2304D361">
</a>

### Mobile

<p align="center">
  <img alt="MyTemplateRepository" title="#MyTemplateRepository" src="./support/layout-mobile.png" width="200px">
</p>

### Web

<p align="center" style="display: flex; align-items: flex-start; justify-content: center;">
  <img alt="MyTemplateRepository" title="#MyTemplateRepository" src="./support/layout-web.png" width="400px">
</p>

---

## Como executar

Este projeto está dividido em três partes:

1. Backend (pasta server)
2. Frontend (pasta web)
3. Mobile (pasta mobile)

Ambos Frontend e Mobile precisam que o Backend esteja rodando para funcionar.

### Pré-requisitos

Antes de começar, você precisa ter as seguintes ferramentas instaladas no seu computador:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/), [.NET SDK](https://dotnet.microsoft.com/en-us/download).

Além disso, é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

#### Rodar o Backend (Server)

```bash

# Clonar este repositorio
$ git clone git@github.com:efernandes-tech/proj-007-my-template-repository.git

# Acessar a pasta do projeto cmd/terminal
$ cd my-template-repository

# Ir para a pasta server
$ cd server

# Instalar as dependencias
$ dotnet build

# Rodar a aplicação em modo de desenvolvimento
$ dotnet run

# O servidor vai iniciar na porta: 5000 - va para http://localhost:5000

```

<p align="center">
    <a href="https://github.com/efernandes-tech/proj-007-my-template-repository/blob/main/support/Insomnia_MyTemplateRepository.json" target="_blank">
        <img src="https://insomnia.rest/images/run.svg" alt="Executar no Insomnia">
    </a>
</p>

#### Rodar o Frontend (Web)

```bash

# Clonar este repositorio
$ git clone git@github.com:efernandes-tech/proj-007-my-template-repository.git

# Acessar a pasta do projeto cmd/terminal
$ cd my-template-repository

# Ir para a pasta web
$ cd web

# Instalar as dependencias
$ npm install

# Rodar a aplicação em modo de desenvolvimento
$ npm run start

# O servidor vai iniciar na porta: 3000 - va para http://localhost:3000

```

---

## Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

#### **Web** ([React](https://reactjs.org/) + [TypeScript](https://www.typescriptlang.org/))

-   **[React Router Dom](https://github.com/ReactTraining/react-router/tree/master/packages/react-router-dom)**
-   **[React Icons](https://react-icons.github.io/react-icons/)**
-   **[Axios](https://github.com/axios/axios)**
-   **[Leaflet](https://react-leaflet.js.org/en/)**
-   **[React Leaflet](https://react-leaflet.js.org/)**
-   **[React Dropzone](https://github.com/react-dropzone/react-dropzone)**

> Veja o arquivo [package.json](https://github.com/efernandes-tech/proj-007-my-template-repository/blob/main/web/package.json)

#### **Server** ([.NET](https://dotnet.microsoft.com/en-us/download) + [C#](https://learn.microsoft.com/en-us/dotnet/csharp/tour-of-csharp/))

-   **[ASP.NET](https://learn.microsoft.com/en-us/aspnet/core/)**
-   **[SQLite](https://github.com/mapbox/node-sqlite3)**

> Veja o arquivo [api.csproj](https://github.com/efernandes-tech/proj-007-my-template-repository/blob/main/server/api/api.csproj)

#### **Mobile** ([React Native](http://www.reactnative.com/) + [TypeScript](https://www.typescriptlang.org/))

-   **[Expo](https://expo.io/)**
-   **[Expo Google Fonts](https://github.com/expo/google-fonts)**
-   **[React Navigation](https://reactnavigation.org/)**
-   **[React Native Maps](https://github.com/react-native-community/react-native-maps)**
-   **[Expo Constants](https://docs.expo.io/versions/latest/sdk/constants/)**
-   **[React Native SVG](https://github.com/react-native-community/react-native-svg)**
-   **[Axios](https://github.com/axios/axios)**
-   **[Expo Location](https://docs.expo.io/versions/latest/sdk/location/)**
-   **[Expo Mail Composer](https://docs.expo.io/versions/latest/sdk/mail-composer/)**

> Veja o arquivo [package.json](https://github.com/efernandes-tech/proj-007-my-template-repository/blob/main/mobile/package.json)

#### **Utilitários**

-   Protótipo: **[Figma](https://www.figma.com/)** → **[Protótipo (MyTemplateRepository)](https://www.figma.com/file/1SxgOMojOB2zYT0Mdk28lB/MyTemplateRepository)**
-   API: **[IBGE API](https://servicodados.ibge.gov.br/api/docs/localidades?versao=1)** → **[API de UFs](https://servicodados.ibge.gov.br/api/docs/localidades?versao=1#api-UFs-estadosGet)**, **[API de Municípios](https://servicodados.ibge.gov.br/api/docs/localidades?versao=1#api-Municipios-estadosUFMunicipiosGet)**
-   Mapas: **[Leaflet](https://react-leaflet.js.org/en/)**
-   Editor: **[Visual Studio Code](https://code.visualstudio.com/)** → Extensões: **[SQLite](https://marketplace.visualstudio.com/items?itemName=alexcvzz.vscode-sqlite)**
-   Markdown: **[StackEdit](https://stackedit.io/)**, **[Markdown Emoji](https://gist.github.com/rxaviers/7360908)**
-   Commit Conventional: **[Commitlint](https://github.com/conventional-changelog/commitlint)**
-   API Teste: **[Insomnia](https://insomnia.rest/)**
-   Ícones: **[Feather Icons](https://feathericons.com/)**, **[Font Awesome](https://fontawesome.com/)**
-   Fontes: **[Ubuntu](https://fonts.google.com/specimen/Ubuntu)**, **[Roboto](https://fonts.google.com/specimen/Roboto)**

---

## Contribuidores

Um grande agradecimento a este grupo que fez este produto deixar o campo da idéia e entrar nas lojas de aplicativos :)

Vocês são uma equipe incrível! :)

<table>
    <tr>
        <td align="center">
            <a href="https://github.com/efernandes-tech">
                <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/11312749?v=4" width="100px;" alt=""/><br />
                <sub><b>Ederson Fernandes</b></sub>
            </a><br />
            <a href="https://edersonfernandes.com.br" title="site">🌐</a>
        </td>
        <td align="center">
            <a href="https://github.com/efernandes-tech">
                <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/11312749?v=4" width="100px;" alt=""/><br />
                <sub><b>Ederson Fernandes</b></sub>
            </a><br />
            <a href="https://edersonfernandes.com.br" title="site">🌐</a>
        </td>
        <td align="center">
            <a href="https://github.com/efernandes-tech">
                <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/11312749?v=4" width="100px;" alt=""/><br />
                <sub><b>Ederson Fernandes</b></sub>
            </a><br />
            <a href="https://edersonfernandes.com.br" title="site">🌐</a>
        </td>
    </tr>
    <tr>
        <td align="center">
            <a href="https://github.com/efernandes-tech">
                <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/11312749?v=4" width="100px;" alt=""/><br />
                <sub><b>Ederson Fernandes</b></sub>
            </a><br />
            <a href="https://edersonfernandes.com.br" title="site">🌐</a>
        </td>
        <td align="center">
            <a href="https://github.com/efernandes-tech">
                <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/11312749?v=4" width="100px;" alt=""/><br />
                <sub><b>Ederson Fernandes</b></sub>
            </a><br />
            <a href="https://edersonfernandes.com.br" title="site">🌐</a>
        </td>
        <td align="center">
            <a href="https://github.com/efernandes-tech">
                <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/11312749?v=4" width="100px;" alt=""/><br />
                <sub><b>Ederson Fernandes</b></sub>
            </a><br />
            <a href="https://edersonfernandes.com.br" title="site">🌐</a>
        </td>
    </tr>
</table>

## Como contribuir

1. Fork o projeto.
2. Crie uma nova branch com suas mudanças: `git checkout -b my-feature`
3. Salve suas alterações e crie uma mensagem no commit dizendo o que você fez: `git commit -m "feat: my new feature"`
4. Envie suas alterações: `git push origin my-feature`

> Se você tiver alguma dúvida, verifique isso [guia sobre como contribuir](./CONTRIBUTING-pt.md)

---

## Autor

<a href="https://github.com/efernandes-tech">
    <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/11312749?v=4" width="100px;" alt="Ederson Fernandes"/><br />
    <sub><b>Ederson Fernandes</b></sub>
</a><br />
<a href="https://edersonfernandes.com.br" title="site">🌐</a><br />

[![Twitter Badge](https://img.shields.io/badge/-@EFernandesTech-1ca0f1?style=flat-square&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/EFernandesTech)](https://twitter.com/EFernandesTech) [![Linkedin Badge](https://img.shields.io/badge/-Ederson-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/efernandes-tech/)](https://www.linkedin.com/in/efernandes-tech/) [![Gmail Badge](https://img.shields.io/badge/-efernandes.tech@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:efernandes.tech@gmail.com)](mailto:efernandes.tech@gmail.com)

---

## Licença

Este projeto está sob a licença [MIT](./LICENSE).

Feito por Ederson Fernandes 👋🏽 [Entrar em contato!](Https://www.linkedin.com/in/efernandes-tech/)

---

## Versões do README

[English](./README.md) | [Portuguese](./README-pt.md)
