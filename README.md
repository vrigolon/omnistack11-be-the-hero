# Be The Hero

A Semana OmniStack é um workshop online produzido pela Rocketseat. Esta é a versão 11, onde desenvolvemos uma aplicação desde o backend até o frontend web e mobile utilizando Javascript, React e React Native. O nome da aplicação desenvolvida é Be The Hero, uma aplicação para cadastro de ONGs e casos cadastrados por elas para que outras pessoas possam ajudar a resolvê-los.



# Instalação

## Pré-Requisitos 

```git e node```

Clone o repositório:
```
git clone https://github.com/vrigolon/omnistack11-be-the-hero.git
```

Iniciar backend:
```
cd backend
npm install
npm start
```

Iniciar frontend:

```
cd frontend
npm install
npm start
```

Abra o endereço http://localhost:3000 no seu browser.


Iniciar Plataforma mobile:

Altere o arquivo mobile/src/services/api.js colocando o endereço IP de sua maquina, e depois execute os comandos:

```
cd mobile
npm install -g expo-cli
npm install
expo start
```
Após os comandos será aberta no seu navegador o endereço http://localhost:19002, baixe o aplicativo *Expo* da Play Store ou App Store no celular e em seguida escaneie o código QR.

# Projeto


![](https://github.com/pushline/Be-the-Hero/blob/master/frontend/77811449-13935d80-7079-11ea-9123-4c8ff90a696b.png)


# Back-End

Api desenvolvida em NodeJS com acesso a banco de dados relacional = SQLite. Esta api faz uso do Knex.

As rotas para acessar a API estão no arquivo [routes.js](https://github.com/pushline/Be-the-Hero/blob/master/backend/src/routes.js). Você pode testar as rotas antes de usar o frontend com o software Insomnia. Você só precisa baixar e instalar o Insomnia na sua máquina, e acessar as rotas da aplicação.

# Front-End (Web e Mobile)

Frontend web, desenvolvido em ReactJS. Nesta parte da aplicação, é possível entender diversos conceitos do React e do desenvolvimento web em geral. 

Além disso, é muito importante entender como a página web normalmente se comunica com a API por meio de requisições http, as quais retornam ao frontend como um objeto json. Neste caso, foi utilizada a lib Axios para realizar a comunicação com a api.


Com isso, a página da aplicação Be The Hero será aberta. Nela, uma ong poderá se cadastrar e cadastrar seus incidentes. A ong também poderá entrar em contato com outras ONGs para poder ajudar nos incidentes delas.


💻Versão Web
 
![](https://github.com/pushline/Be-the-Hero/blob/master/frontend/77805427-9c51cf80-7060-11ea-88a1-ff3014ffe8ce.gif)
  
:iphone:Versão Mobile

![](https://github.com/pushline/Be-the-Hero/blob/master/frontend/77805360-72001200-7060-11ea-9bc3-dd313a195bf8.gif)



# Mobile

Desenvolvido com o framework React Native e com o Expo.
