# trampos.co Custom Element

x-trampos é uma adaptação de um widget existente, utilizando [Polymer](http://polymer-project.org) e o conceito de [web components](http://customelements.io/)

> Implementado por [@victorkurauchi](https://twitter.com/victorkurauchi).
> Forked from [x-instagram](https://github.com/addyosmani/x-instagram), by [addyosmani](https://github.com/addyosmani)

## Instalação

Using [Bower](http://bower.io), run:

```bash
$ bower install --save x-instagram
```

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

Atributo  | Opção                   | Default             | Descrição
---        | ---                       | ---                 | ---
`itensPerRow`      | *integer*       | `10`               | Quantidade de itens exibidos na listagem
`url`   | *string*                     | See source               | Url de onde os registros virão

## License

[MIT License](http://opensource.org/licenses/MIT)
