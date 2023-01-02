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
    "produtos": [
        {
        "id": 1,
        "nome": "mouse microsoft",
        "Valor": 15.89,
        "promocao": false,
        "valorPromo": 0,
        "imagem": "mouse.jpg"
        },
        {
        "id": 2,
        "nome": "Teclado microsoft",
        "Valor": 30.00,
        "promocao": false,
        "valorPromo": 0,
        "imagem": "teclado.jpg"
        },
        {
        "id": 3,
        "nome": "Monitor Samsung",
        "Valor": 250.00,
        "promocao": false,
        "valorPromo": 0,
        "imagem": "monitor.jpg"
        },
        {
        "id": 4,
        "nome": "Laptop Samsung",
        "Valor": 3000.00,
        "promocao": true,
        "valorPromo": 999.99,
        "imagem": "laptop.jpg"
        },
        {
        "id": 5,
        "nome": "Headset microsoft",
        "Valor": 178.50,
        "promocao": false,
        "valorPromo": 0,
        "imagem": "headset.jpg"
        },
        {
        "id": 6,
        "nome": "Webcam Logitech",
        "Valor": 90.00,
        "promocao": true,
        "valorPromo": 49.99,
        "imagem": "webcam.jpg" 
        },
        {
        "id": 7,
        "nome": "Galaxy S10+",
        "Valor": 3000.00,
        "promocao": false,
        "valorPromo": 0,
        "imagem": "celular.jpg"
        },
        {
        "id": 8,
        "nome": "Mousepad Microsoft",
        "Valor": 35.50,
        "promocao": false,
        "valorPromo": 0,
        "imagem": "mousepad.jpg"
        },
        {
        "id": 9,
        "nome": "Go Pro 8",
        "Valor": 300.00,
        "promocao": false,
        "valorPromo": 0,
        "imagem": "gopro.jpg"
        }  
    ]
}

Start JSON Server

json-server --watch db.json

