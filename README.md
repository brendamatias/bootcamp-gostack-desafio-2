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
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/brendamatias/bootcamp-gostack-desafio-2">

</p>

<hr/>

<p align="center">
  <a href="#rocket-sobre-o-desafio">Sobre o desafio</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#🔥-funcionalidades">Funcionalidades</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#⚙️-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#⛏-ferramentas">Ferramentas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#computer-execute-o-projeto">Execute o projeto</a>
</p>

## :rocket: Sobre o desafio

Nesse desafio, você deve criar uma aplicação para treinar o que você aprendeu até agora no Node.js!

Essa será uma aplicação para armazenar repositórios do seu portfólio, que irá permitir a criação, listagem, atualização e remoção dos repositórios, e além disso permitir que os repositórios possam receber "likes".



## 🔥 Funcionalidades

Neste projeto, as rotas foram implementadas usando métodos HTTP:
- **`POST /repositories`**: A rota deve receber `title`, `url` e `techs` dentro do corpo da requisição, sendo a URL o link para o github desse repositório. Ao cadastrar um novo projeto, ele deve ser armazenado dentro de um objeto no seguinte formato: `{ id: "uuid", title: 'Desafio Node.js', url: 'http://github.com/...', techs: ["Node.js", "..."], likes: 0 }`; Certifique-se que o ID seja um UUID, e de sempre iniciar os likes como 0.

- **`GET /repositories`**: Rota que lista todos os repositórios;

- **`PUT /repositories/:id`**: A rota deve alterar apenas o `title`, a `url` e as `techs` do repositório que possua o `id` igual ao `id` presente nos parâmetros da rota;

- **`DELETE /repositories/:id`**: A rota deve deletar o repositório com o `id` presente nos parâmetros da rota;

- **`POST /repositories/:id/like`**: A rota deve aumentar o número de likes do repositório específico escolhido através do `id` presente nos parâmetros da rota, a cada chamada dessa rota, o número de likes deve ser aumentado em 1;

## ⚙️ Tecnologias

* __NodeJS__
* Express
* Nodemon
* Yarn
* Jest

## ⛏ Ferramentas

* [Insomnia](https://insomnia.rest/download/)


## :computer: Execute o projeto

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
