# 💻 Sobre o projeto

<h1 align="center">
    <img alt="WeTalk" title="#Logo" src="https://github.com/whateverlcs/we-talk/blob/main/assets/logo.png" width="200px" />
</h1>

<p align="center">
  <a href="https://github.com/whateverlcs/we-talk/blob/main/LICENSE"><img alt="License" src="https://img.shields.io/npm/l/react?color=%237964af" /></a>
  
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/whateverlcs/we-talk?color=%237964af">
  
  <img alt="GitHub Size Repository" src="https://img.shields.io/github/repo-size/whateverlcs/we-talk?color=%237964af">
    
  <img alt="GitHub Last Commit" src="https://img.shields.io/github/last-commit/whateverlcs/we-talk?color=%237964af">
  
  <img alt="GitHub Stars Repository" src="https://img.shields.io/github/stars/whateverlcs/we-talk?style=social">
</p>

🦸‍♂️ We-talk é uma aplicação back-end construída durante a Next Level Week #05, evento organizado pela [Rocketseat](https://rocketseat.com.br/ "Site da Rocketseat").

A aplicação foi criada utilizando principalmente o Socket.io que fornece essa conexão para se enviar mensagens. O projeto consiste em possibilitar a conexão de chat entre duas pessoas, no caso, o cliente e admin. O cliente ao enviar uma mensagem, automaticamente a página de admin é atualizada com o nome, email e a opção de atendê-lo.

## 🖥 Layout web
<p align="center">
  <img alt="Main" title="Main" src="https://github.com/whateverlcs/we-talk/blob/main/assets/main.png" width="200px">
  
  <img alt="Client-chat" title="Client-chat" src="https://github.com/whateverlcs/we-talk/blob/main/assets/client-chat.png" width="200px">

  <img alt="Client-chat-2" title="Client-chat-2" src="https://github.com/whateverlcs/we-talk/blob/main/assets/client-chat-2.png" width="200px" height="393px">
</p>

<p align="center">
  <img alt="Admin-chat" title="Admin-chat" src="https://github.com/whateverlcs/we-talk/blob/main/assets/admin-chat.png">
</p>

![Admin-chat-2](https://github.com/whateverlcs/we-talk/blob/main/assets/admin-chat-2.png)

<p align="center">
  <img alt="Response-admin-client" title="Response-admin-client" src="https://github.com/whateverlcs/we-talk/blob/main/assets/response-admin-client.png" width="200px">
</p>

# ⚒ Tecnologias utilizadas
## 👨‍💻 Back-end
- NodeJS
- TypeORM
- Ejs
- Socket.io
- UUID
- Express
- Typescript
- Sqlite
## 🎨 Front-end
- HTML / CSS / JS

# 👨‍🔧 Como executar o projeto

## 👨‍💻 Back-end
Pré-requisitos: NodeJS

```bash
# clonar repositório
git clone https://github.com/whateverlcs/we-talk

# entrar na pasta do projeto
cd we-talk

# instale as dependências
npm install

#Execute as migrations presentes para criação do bd
typeorm migration:run

# executar o projeto
yarn start
```

## 🤝 Como contribuir para o projeto

1. Faça um **fork** do projeto.
2. Crie uma nova branch com as suas alterações: `git checkout -b my-feature`
3. Salve as alterações e crie uma mensagem de commit contando o que você fez: `git commit -m "feature: My new feature"`
4. Envie as suas alterações: `git push origin my-feature`
> Caso tenha alguma dúvida confira este [guia de como contribuir no GitHub](https://github.com/firstcontributions/first-contributions)

# 🤵 Autor

Lucas Batistão

https://www.linkedin.com/in/lucas-batist%C3%A3o-099693111/

