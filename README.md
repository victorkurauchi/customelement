# trampos.co Custom Element

x-trampos é uma adaptação de um widget existente, utilizando [Polymer](http://polymer-project.org) e o conceito de [web components](http://customelements.io/)

> Implementado por [@victorkurauchi](https://twitter.com/victorkurauchi). Fork: [x-instagram](https://github.com/addyosmani/x-instagram), por [addyosmani](https://github.com/addyosmani)

## Utilização

1. Web Components' polyfill:

```html
<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.1.4/platform.js"></script>
```

2. Custom Element:

```html
<link rel="import" href="src/x-trampos.html">
```

3. Inicialização

```html
<x-trampos><x-trampos>
```

## Setup

In order to run it locally you'll need a basic server setup.

1. Install [Node.js](http://nodejs.org/download/)
2. Install [Grunt](http://gruntjs.com/):

```sh
$ npm install -g grunt-cli
```

3. Install local dependencies:

```sh
$ npm install
```

4. Run a local server and open `http://localhost:8000`.

```sh
$ grunt connect
```

## Options

Atributo  | Opção                   | Padrão             | Descrição
---        | ---                       | ---                 | ---
`itensPerRow`      | *int*       | `5`               | Quantidade de itens exibidos na listagem
`url`   | *string*                     | -               | Url para buscar registros 

## License

[MIT License](http://opensource.org/licenses/MIT)
