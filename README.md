<p align="center">
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
</p>

<p align="center">
 <img src="https://img.shields.io/static/v1?label=PRs&message=welcome&color=49AA26&labelColor=000000" alt="PRs welcome!" />

  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=49AA26&labelColor=000000">
</p>


# 💻 Projeto:
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.0.1.

<img src="./img/Angular.jpg" Alt="Img">
<img src="./img/Angular1.jpg" Alt="Img">
<img src="./img/Angular2.jpg" Alt="Img">

## 🚀 Tecnologias:

Esse projeto foi desenvolvido usando as seguintes tecnologias:

- HTML
- CSS
- JAVASCRIT
- Angular

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Getting started
Install JSON Server

npm install -g json-server
Create a produtos.json file with some data

{
    "produtos": 
    [
        { "id": 1, "nome": "mouse microsoft", "Valor": 15.89, "promocao": false, "valorPromo": 0, "imagem": "mouse.jpg" },
        
        { "id": 2, "nome": "Teclado microsoft", "Valor": 30.00, "promocao": false, "valorPromo": 0, "imagem": "teclado.jpg" }
    ]}

Start JSON Server

json-server --watch db.json

