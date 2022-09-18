<h1 align="center">Find Your Duo Mobile - NLW eSports</h1>
<p align="center">
  <img width="350" src="https://user-images.githubusercontent.com/44277956/190904595-7a9577c0-fad4-461f-8269-2f8b3f1fd440.svg" />
</p>  
<p align="center">
  <img src="https://img.shields.io/badge/ReactJs-18.2.0-61DAFB?style=for-the-badge&logo=React" />
  <img src="https://img.shields.io/badge/Expo-6.0.5-000020?style=for-the-badge&logo=Expo" />
  <img src="https://img.shields.io/badge/NodeJs-16.15.1-339933?style=for-the-badge&logo=Node.js" />
</p>
<h4 align="center">Projeto desenvolvido durante a Next Level Week</h4>


<div align="center" display="flex-row" row-gap="90" justify-content="space-evenly">
<img width="250" height="480" src="https://user-images.githubusercontent.com/44277956/190915844-50cc3162-9e9b-4600-8187-833ad7bf53c4.jpg" />
<img width="250" height="480" src="https://user-images.githubusercontent.com/44277956/190915850-664fdf31-9c90-4033-81d0-54d78a01611f.jpg" />
</div>

Projeto de uma aplicação completa, web client, mobile e backend, com o intuito de criar uma plataforma de integração social dos usuários para jogar em Hub em uma sala do discord previamente escolhida.


## Objetivo

Dentro de uma semana foi possível aprender como criar interfaces simples em ReactJs integrado com TailwindCSS e Radix para formulário, e também interfaces em React Native. Também foi mostrado como funciona o consumo de API com o Front-end Web e com o mobile utilizando o useEffect e fetch. 

## Features

- [x] Home page com a listagem de jogos para iniciar duo
- [x] Listagem de anúncios por jogo
- [x] Conectar-se com usuário através do anúncio por jogo

## Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/) na versão *16.15.1*, [NPM](https://www.npmjs.com/) na versão *8.5.5* e o [EXPO](https://expo.dev/). É possível instalar as ferramentas utilizando os gerenciadores de pacote [Chocolatey](https://chocolatey.org/) em máquinas windows e o [Homebrew](https://brew.sh/index_pt-br) em máquinas MacOS. Já o Expo é possível instalar utilizando o **npm**.
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

### 🎲 Rodando o projeto localmente

```bash
# Clone este repositório
$ git clone https://github.com/Welber33/find_your_duo_mobile.git

# Acesse a pasta do projeto via terminal/cmd
$ cd pasta_destino_do_do_projeto_clonado

# Abra o projeto no vscode via terminal/cmd
$ code .

# Instale as dependências
$ npm install

# Caso não tenha o Expo instalado na sua máquina, execute o comando:
$ npm install -g expo-cli

# Baixe o app Expo Go na appstore para IOS e/ou Expo na google playstore para android

# Com a aplicação aberta no VsCode e com as dependências instaladas, execute o comando: 
$ expo start

# Abra o app da expo e leia o QRCode que aparecerá no terminal e seu aplicativo irá inicializar.
```
Obs: Certifique-se de que você tem o server do projeto clonado na sua máquina e rodando! Para mais info/ acesse → [NLW eSport Server](https://github.com/Welber33/find_your_duo_server.git) 
  
## Tecnologias 

Foram utilizadas neste projeto as seguintes tecnologias: 
- [React](https://pt-br.reactjs.org/)
- [React Native](https://reactnative.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [NPM](https://www.npmjs.com/)
- [Expo](https://expo.dev/)
- [React Navigation](https://reactnavigation.org/)

## :memo: License

This project is under the MIT license. See the [LICENSE](LICENSE) for details.
