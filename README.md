<div align="center">
  <img alt="GoStack"
    src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png"
  />
</div>

<h2 align="center">
   Desafio 02: Conceitos do Node.js
</h2>

<h3 align="center">
  <img alt="NodeJS" 
    src="https://arrayoutofindex.files.wordpress.com/2017/06/node.png" width="180px"/>
</h3>

<p align="center">
  <img alt="language version" src="https://img.shields.io/badge/Node-v_13.11.0-339933?logo=node.js">
  <img alt="language version" src="https://img.shields.io/badge/Yarn-v_1.22.4-2C8EBB?logo=Yarn">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/Fred-Reis/challenge_backEnd-01_GoStack-v2">

</p>

<hr/>

<p align="center">
  <a href="#">Sobre o desafio</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#">Funcionalidades</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#">Tecnologias aplicação</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#">Ferramentas aplicação</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#">Bora codar?</a>
</p>


## 💡 Sobre o desafio

Nesse desafio, você deve criar uma aplicação para treinar o que você aprendeu até agora no Node.js!

Essa será uma aplicação para armazenar repositórios do seu portfólio, que irá permitir a criação, listagem, atualização e remoção dos repositórios, e além disso permitir que os repositórios possam receber "likes".



## 🔥 Funcionalidades

Neste projeto, as rotas foram implementadas usando métodos HTTP:
* `GET /repositories` => Listar todos os repositórios.
* `POST /repositories` => Criar um novo repositório.
* `PUT /repositories/:id` => Atualiza parâmetros do repositório referente ao ID recebido por __request params__.
* `DELETE /repositories/:id` => Deleta o repositório referente ao ID recebido por __request params__.
* `POST /repositories/:id/like` => Incrementa +1 ao número de "likes" no repositório referente ao ID recebido por __request params__, sempre que essa rota for chamada.

## ⚙️ Tecnologias

* __NodeJS__
* Express
* Nodemon
* Yarn
* Jest

## ⛏ Ferramentas

* [Insomnia](https://insomnia.rest/download/)


## :rocket: Bora codar?

Clone este repositório:

```bash
$ git clone https://github.com/brendamatias/bootcamp-gostack-desafio-2
```

Mova-se para diretório da aplicação:

```bash
$ cd bootcamp-gostack-desafio-2
```

Para instalar as dependências execute:

```bash
yarn install
```

E para iniciar o servidor:

```bash
yarn dev
```

<br/>

---

<h4 align="center">
  “Não espere para plantar, apenas tenha paciência para colher”!
</h4>

<p align="center">
  <a alt="Brenda" href="https://www.linkedin.com/in/brenda-matias/">
    <img src="https://img.shields.io/badge/LinkedIn-Brenda_Matias-0077B5?logo=linkedin"/>
  </a>
</p>
