# 🖥🗣 Hacker-Chat o Bate-Papo via Terminal!

<p align="center">
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-experiencias">Experiências adquiridas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-clonando">Clonar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-licença">Licença</a>
</p>

<p align="center">
  <img alt="Plant-Manager"src="https://imgur.com/a/pO3coik" width="100%" height="auto">
</p>

## 📌 Projeto
O aplicativo foi criado durante a <b>Semana JS Expert 03<br>! Gerenciada pelo [@Erick Wendel](https://github.com/erickwendel).

Seu objetivo é conectar pessoas através do terminal - independente de seu sistema operacional - para colocar o papo em dia.
A conexão é feita através de WebSockets construídos sem usar bibliotecas externas.

## 👩‍💻 Tecnologias
Esse projeto foi desenvolvido utilizando as seguintes tecnologias:

- [blessed](https://www.npmjs.com/package/blessed)
  Para construção da interface do terminal com uma linguagem semelhante ao CSS.

- [uuid](https://www.npmjs.com/package/uuid)
  Para geração de ids únicos na conexão TCP/IP WebSocket.

Só isso. pouco, não? 🤣

## 🆙 Experiências adquiridas
O projeto foi visado em usar a menor quantidade de bibliotecas externas possíveis!
Portanto, foi construído do zero uma aplicação de conexão/troca de informações contantes.
Com isso em mente, foi possível entender à fundo o processo de upgrade de um protocolo HTTP/HTTPS para um protocolo WebSocket através da [Handshake](https://pt.wikipedia.org/wiki/Handshake) entre o servidor e o cliente!
Também foi possível adquirir mais experiência em questão de processo de eventos, como um Event Emitter, presente em bibliotecas de WebSockets famosas, como [socket.io](https://socket.io/).

## 📥 Clonando
Para clonar para seu repositório local use o seguinte comando no seu terminal de preferência:

```shell
    # é necessário ter o git instalado em seu sistema operacional.

    # clonando
    git clone https://github.com/jsGolden/hacker-chat
    cd hacker-chat

    # instalando dependências do cliente/servidor
    cd client && npm i && ..
    cd server && npm i && ..

    # rodando projeto
    cd client

    # rodando a aplicação com o servidor hospedado na Heroku
    node index.js --username Fulano --room Sala01

    # rodando a aplicação com um servidor local
    node index.js --username Fulano --room Sala01 --hostUri http://localhost:9898
```

## 🧾 Licença
Este projeto está sobre a licença MIT.

<p align="center">Desenvolvido com 💜 por Wagner Rodrigues</p>