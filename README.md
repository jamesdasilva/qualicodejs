# Qualicode Boilerplate JS

Conjunto de ferramentas reunidas e já configuradas para a produção de código JavaScript com alta qualidade.

## Getting Started

Essas instruções irão ajudá-lo a começar ultilizar o Qualicode Boilerplate JS para desenvolver projetos JavaScript.

### Pré-requisitos

Você deverá instalar previamente:

* [Node.js](https://nodejs.org/) - A JavaScript runtime built on Chrome's V8 JavaScript engine.
* [npm](https://www.npmjs.com/) - The package manager for JavaScript and the world’s largest software registry. Discover packages of reusable code — and assemble them in powerful new ways.
* [Git](https://git-scm.com/) - A free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.


### Fazendo a instalação

É necessário clonar o repositório:
```
git clone https://github.com/jamesodas/qualicode-bp-js.git meu-projeto
```
Entrar no diretório do projeto:
```
cd meu-projeto
```
E executar o comando:
```
npm run newdev
```
Pronto! Agora você já pode começar a desenvolver seu código, garantindo alta qualidade.


### Executando os testes

Executar um teste:
```
npm run test
```
Ativar testes automáticos:
```
npm run test:tdd
```
Verificar a cobertura dos testes:
```
npm run test:coverage
```

### Verificando estilo de codificação

Você pode verificar o estilo de codificação com o comando:
```
npm run lint
```

### Hooks do Git

Os comandos git commit e git push só são aceitos se todos os testes até então definidos passarem e se os códigos desenvolvidos estiverem siguindo o guia de estilo da AirBnb.

## Ferramentas utilizadas

* [Webpack](https://webpack.js.org) - A static module bundler for modern JavaScript applications.
* [Babel](https://babeljs.io/) - The compiler for writing next generation JavaScript.
* [Mocha](https://mochajs.org/) - The fun, simple, flexible JavaScript test framework.
* [Chai](http://chaijs.com/) - A BDD / TDD assertion library for node and the browser that can be delightfully paired with any javascript testing framework.
* [Nyc](https://github.com/istanbuljs/nyc) - The Istanbul command line interface.
* [ESLint](https://eslint.org/) - Pluggable JavaScript linter.
* [Husky](https://github.com/typicode/husky) - Git hooks made easy.


## Autores

* **James Oliveira da Silva** - *Initial work* - [jamesodas](https://github.com/jamesodas)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details


## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.


