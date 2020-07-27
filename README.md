

<h1 align="center">
     💻 <a href="https://github.com/Rocketseat/bootcamp-gostack-desafios/tree/master/desafio-conceitos-react-native" alt="Desafio da Rocketeseat"> Desafio 04: Conceitos do React-Native </a>
</h1>

<h3 align="center">
    Aplicação mobile em React-Native que irá armazenar repositórios de um portfólio, que utiliza o backend separado em Node.js.
</h3>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/georgealan/desafio-04-conceitos-do-react-native?color=%2304D361">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/georgealan/desafio-04-conceitos-do-react-native">
  
  <a href="https://github.com/georgealan/desafio-04-conceitos-do-react-native/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/georgealan/desafio-04-conceitos-do-react-native">
  </a>
    
   <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
   <a href="https://github.com/georgealan/desafio-04-conceitos-do-react-native/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/georgealan/desafio-04-conceitos-do-react-native?style=social">
  </a>

  <a href="https://kodyweb.com.br">
    <img alt="Feito por George Alan Rufo" src="https://img.shields.io/badge/feito%20por-George-%237519C1">
  </a>
  
  <a href="https://medium.com/kodyweb">
    <img alt="Blog Medium KodyWeb" src="https://img.shields.io/badge/Blog-KodyWeb-black?style=flat&logo=Medium">
  </a>
</p>

<h4 align="center">
	🚧   Concluído 🚀 🚧
</h4>

Tabela de conteúdos
=================
<!--ts-->
   * [Sobre o projeto](#-sobre-o-projeto)
   * [Funcionalidades](#user-content-funcionalidades)
   * [Como executar o projeto](#-como-executar-o-projeto)
     * [Pré-requisitos](#pré-requisitos)
     * [Rodando o App pelo emulador AVD Android Studio](#user-content--rodando-o-app-pelo-emulador-avd-android-studio)
   * [Tecnologias](#-tecnologias)
     * [Mobile](#user-content-website--react----typescript)
   * [Autor](#-autor)
   * [Licença](#user-content--licença)
<!--te-->


## 💻 Sobre o projeto

Simples aplicação React-native para testar a integração do mobile com o backent utilizando o Axios, e como demonstração
utilizando os verbos: GET, POST, para manipular os dados da lista que é capturada na aplicação backend em NodeJS.

Projeto desenvolvido durante o **Bootcamp GoStack 11** oferecido pela [Rocketseat](https://rocketseat.com.br/gostack).

---

## ⚙️ Funcionalidades

- [x] Pode exibir repositórios em uma lista com:
  - [x] GET
  - [x] POST

---

## 🚀 Como executar o projeto

Este projeto é divido em duas partes:
1. Backend:
Vá até este <a href="https://github.com/georgealan/desafio-02-conceitos-do-nodejs">repositório</a> e siga as instruções
para clonar e utilizar o projeto backend que faz parte deste desafio.
2. Mobile (este projeto aqui)

💡O Mobile precisa que o backend esteja sendo executado para funcionar.

💡Para rodar os testes desligar o servidor o backend.

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:

- [(Windows, Linux) Android Studio](https://developer.android.com/studio) ou [(iOS) Xcode](https://apps.apple.com/br/app/xcode/id497799835?mt=12)
- [Git](https://git-scm.com)
- [Node.js](https://nodejs.org/en/)
- Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

#### 🎲 Rodando o App pelo emulador AVD Android Studio

```bash

# Clone este repositório
$ git clone git@github.com:georgealan/desafio-04-conceitos-do-react-native.git

# Acesse a pasta do projeto no terminal/cmd
$ cd desafio-04-conceitos-do-react-native

# Execute o comando abaixo para instalar todas as dependências
$ yarn

# Para começar a utilizar a aplicação abra um prompt de comando no diretório do projeto, fora do VSCode e inicie o projeto com o comando
$ npx react-native run-android

# O comando acima vai gerar todo o processo de criação do build do app no emulador do Android Studio

# Execute a aplicação em modo de teste
$ yarn test

```

---

## 🛠 Tecnologias

As seguintes ferramentas estão sendo utilizadas na construção do projeto:

#### **Mobile**  ([React](https://reactjs.org/))

-   **[React Dom](https://www.npmjs.com/package/react-dom)**
-   **[React Scripts](https://www.npmjs.com/package/react-scripts)**
-   **[Axios](https://github.com/axios/axios)**
-   **[Axios Mock Adapter](https://github.com/ctimmerm/axios-mock-adapter)**
-   **[Jest Dom](https://github.com/testing-library/jest-dom)**
-   **[@babel](https://babeljs.io/docs/en/babel-preset-react)**
-   **[Webpack](https://webpack.js.org/)**

> Veja o arquivo  [package.json](https://github.com/georgealan/desafio-04-conceitos-do-react-native/blob/master/package.json)

---

## 🦸 Autor

<a href="https://blog.kodyweb.com.br/author/george/">
 <img style="border-radius: 50%;" src="https://avatars2.githubusercontent.com/u/37253093?s=400&u=4793c91ecbabc6342381bd7c411d323f14e59dce&v=4" width="100px;" alt=""/>
 <br />
 <sub><b>George Alan</b></sub></a> <a href="https://blog.rocketseat.com.br/author/thiago/" title="Rocketseat">🚀</a>
 <br />

[![Medium Badge](https://img.shields.io/badge/-KodyWeb-black?style=flat-square&labelColor=black&logo=medium&logoColor=white&link=https://medium.com/kodyweb)](https://medium.com/kodyweb) [![Linkedin Badge](https://img.shields.io/badge/-George-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/george-alan-fullstack-developer/)](https://www.linkedin.com/in/george-alan-fullstack-developer/) 
[![Gmail Badge](https://img.shields.io/badge/-georgealan@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:georgealan@gmail.com)](mailto:georgealanrufo@gmail.com) [![Instagram Badge](https://img.shields.io/badge/-georgealan-a43b9d?style=flat-square&logo=Instagram&logoColor=white&link=https://www.instagram.com/georgealanrufo/)](https://www.instagram.com/georgealanrufo/)

---

## 📝 Licença

Este projeto esta sobe a licença [MIT](./LICENSE).

Feito com ❤️ por George Alan Rufo 👋🏽 [Entre em contato!](https://www.linkedin.com/in/george-alan-fullstack-developer/)

---
