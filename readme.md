# NLW Heat WEB ( ReactJS )

Front-end Web do projeto produzido durante a Next Level Week Heat (NLW Heat) da **Rocketseat**

Este projeto faz a criação do projeto ReactJs utilizando o Vite, exercita o uso de Typescript, CSS Modules e o conceito de real-time com o Socket.io, além de fazer autenticação usando o GitHub com nosso back-end [NLW-Heat]([https://link](https://github.com/gregory-bonassina/nlw-heat)) feito em Node.js

## Tecnologias

- Vite
- Typescript
- Socket.io
- CSS Modules

## Executando o projeto

Configure o arquivo .env da aplicação conforme o .env.sample, para isso siga as instruções abaixo

Configure uma aplição em seu GitHub: Settings > Developer Settings > OAuth Apps: Adicione uma aplicação e configure o arquivo .env com a informação do **ClientId** gerado.

Na parte do **Authorization callback URL** adicione **http://localhost:3000** para redirecionamento do callback de volta para a aplicação após realizado o login.


## yarn
yarn dev

O projeto estará escutando a porta **3000**