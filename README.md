<h1 align="center">
    <a href="#" alt="site">My Template Repository</a>
</h1>

<h3 align="center">
    My base repository for projects
</h3>

<p align="center">
    <a href="https://github.com/efernandes-tech/proj-007-my-template-repository/commits/main">
        <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/efernandes-tech/proj-007-my-template-repository">
    </a>
    <img alt="Repository size" src="https://img.shields.io/github/repo-size/efernandes-tech/proj-007-my-template-repository">
    <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
    <a href="https://edersonfernandes.com.br">
        <img alt="made by @efernandes.tech" src="https://img.shields.io/badge/Made%20by-@efernandes.tech-%2360F6AD">
    </a>
</p>

<h4 align="center">
    Status: Finished
</h4>

<p align="center">
    <a href="#about">About</a> •
    <a href="#features">Features</a> •
    <a href="#layout">Layout</a> •
    <a href="#how-it-works">How it works</a> •
    <a href="#tech-stack">Tech Stack</a> •
    <a href="#contributors">Contributors</a> •
    <a href="#author">Author</a> •
    <a href="#license">License</a>
</p>

## About

My Template Repository - description about the project

---

## Features

-   [x] Feature One:

    -   [x] description of task
    -   [x] description of task
    -   [x] description of task
    -   [x] description of task:
        -   topic 1
        -   topic 2
        -   topic 3

-   [ ] Feature Two:

    -   [x] description of task
    -   [ ] description of task
    -   [ ] description of task

---

## Layout

The application layout is available on Figma:

<a href="https://www.figma.com/file/1SxgOMojOB2zYT0Mdk28lB/MyTemplateRepository?node-id=136%3A546">
  <img alt="Made by @efernandes.tech" src="https://img.shields.io/badge/Access%20Layout%20-Figma-%2304D361">
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

## How it works

This project is divided into three parts:

1. Backend (server folder)
2. Frontend (web folder)
3. Mobile (mobile folder)

Both Frontend and Mobile need the Backend to be running to work.

### Pre-requisites

Before you begin, you will need to have the following tools installed on your machine:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/), [.NET SDK](https://dotnet.microsoft.com/en-us/download).

In addition, it is good to have an editor to work with the code like [VSCode](https://code.visualstudio.com/)

#### Running the Backend (Server)

```bash

# Clone this repository
$ git clone git@github.com:efernandes-tech/proj-007-my-template-repository.git

# Access the project folder cmd/terminal
$ cd my-template-repository

# go to the server folder
$ cd server

# install the dependencies
$ dotnet build

# Run the application in development mode
$ dotnet run

# The server will start at port: 5000 - go to http://localhost:5000

```

<p align="center">
    <a href="https://github.com/efernandes-tech/proj-007-my-template-repository/blob/main/support/Insomnia_MyTemplateRepository.json" target="_blank">
        <img src="https://insomnia.rest/images/run.svg" alt="Run in Insomnia">
    </a>
</p>

#### Running the Frontend (Web)

```bash

# Clone this repository
$ git clone git@github.com:efernandes-tech/proj-007-my-template-repository.git

# Access the project folder in your terminal
$ cd my-template-repository

# Go to the Front End application folder
$ cd web

# Install the dependencies
$ npm install

# Run the application in development mode
$ npm run start

# The application will open on the port: 3000 - go to http://localhost:3000

```

---

## Tech Stack

The following tools were used in the construction of the project:

#### **Web** ([React](https://reactjs.org/) + [TypeScript](https://www.typescriptlang.org/))

-   **[React Router Dom](https://github.com/ReactTraining/react-router/tree/master/packages/react-router-dom)**
-   **[React Icons](https://react-icons.github.io/react-icons/)**
-   **[Axios](https://github.com/axios/axios)**
-   **[Leaflet](https://react-leaflet.js.org/en/)**
-   **[React Leaflet](https://react-leaflet.js.org/)**
-   **[React Dropzone](https://github.com/react-dropzone/react-dropzone)**

> See the file [package.json](https://github.com/efernandes-tech/proj-007-my-template-repository/blob/main/web/package.json)

#### **Server** ([.NET](https://dotnet.microsoft.com/en-us/download) + [C#](https://learn.microsoft.com/en-us/dotnet/csharp/tour-of-csharp/))

-   **[ASP.NET](https://learn.microsoft.com/en-us/aspnet/core/)**
-   **[SQLite](https://github.com/mapbox/node-sqlite3)**

> See the file [api.csproj](https://github.com/efernandes-tech/proj-007-my-template-repository/blob/main/server/api/api.csproj)

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

> See the file [package.json](https://github.com/efernandes-tech/proj-007-my-template-repository/blob/main/mobile/package.json)

#### **Utilities**

-   Prototype: **[Figma](https://www.figma.com/)** → **[Prototype (MyTemplateRepository)](https://www.figma.com/file/1SxgOMojOB2zYT0Mdk28lB/MyTemplateRepository)**
-   API: **[IBGE API](https://servicodados.ibge.gov.br/api/docs/localidades?versao=1)** → **[API States](https://servicodados.ibge.gov.br/api/docs/localidades?versao=1#api-UFs-estadosGet)**, **[API Counties](https://servicodados.ibge.gov.br/api/docs/localidades?versao=1#api-Municipios-estadosUFMunicipiosGet)**
-   Maps: **[Leaflet](https://react-leaflet.js.org/en/)**
-   Editor: **[Visual Studio Code](https://code.visualstudio.com/)** → Extensions: **[SQLite](https://marketplace.visualstudio.com/items?itemName=alexcvzz.vscode-sqlite)**
-   Markdown: **[StackEdit](https://stackedit.io/)**, **[Markdown Emoji](https://gist.github.com/rxaviers/7360908)**
-   Commit Conventional: **[Commitlint](https://github.com/conventional-changelog/commitlint)**
-   API Test: **[Insomnia](https://insomnia.rest/)**
-   Icons: **[Feather Icons](https://feathericons.com/)**, **[Font Awesome](https://fontawesome.com/)**
-   Fonts: **[Ubuntu](https://fonts.google.com/specimen/Ubuntu)**, **[Roboto](https://fonts.google.com/specimen/Roboto)**

---

## Contributors

A big thanks to this group that made this product leave the field of idea and enter the app stores :)

You are an awesome team! :)

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

## How to contribute

1. Fork the project.
2. Create a new branch with your changes: `git checkout -b my-feature`
3. Save your changes and create a commit message telling you what you did: `git commit -m "feat: my new feature"`
4. Submit your changes: `git push origin my-feature`

> If you have any questions check this [guide on how to contribute](./CONTRIBUTING.md)

---

## Author

<a href="https://github.com/efernandes-tech">
    <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/11312749?v=4" width="100px;" alt="Ederson Fernandes"/><br />
    <sub><b>Ederson Fernandes</b></sub>
</a><br />
<a href="https://edersonfernandes.com.br" title="site">🌐</a><br />

[![Twitter Badge](https://img.shields.io/badge/-@EFernandesTech-1ca0f1?style=flat-square&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/EFernandesTech)](https://twitter.com/EFernandesTech) [![Linkedin Badge](https://img.shields.io/badge/-Ederson-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/efernandes-tech/)](https://www.linkedin.com/in/efernandes-tech/) [![Gmail Badge](https://img.shields.io/badge/-efernandes.tech@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:efernandes.tech@gmail.com)](mailto:efernandes.tech@gmail.com)

---

## License

This project is under the license [MIT](./LICENSE).

Made with love by Ederson Fernandes 👋🏽 [Get in Touch!](Https://www.linkedin.com/in/efernandes-tech/)

---

## Versions of README

[English](./README.md) | [Portuguese](./README-pt.md)
