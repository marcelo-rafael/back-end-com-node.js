<h1 align="center">
Backend com Node.jss
</h1>


<hr>


## Aulas

## Criando projeto Node<br />

Na nossa primeira aula prática vamos começar criando nosso primeiro projeto node. Veremos como iniciar um projeto, instalar o ExpressJS, instanciar nosso primeiro servidor na porta 3333, realizar uma requisição GET e retornar nossa primeira resposta em JSON.

## Configurando Nodemon<br />

Como vimos na aula anterior, é muito ruim ter que ficar reiniciando o servidor manualmente a cada alteração no código. Por isso, veremos como instalar e configurar o Nodemon para que ele aplique essas alterações automaticamente e assim ajude na nossa produtividade no ambiente de desenvolvimento.

## Métodos HTTP<br />

Nessa aula nós vamos falar novamente sobre métodos HTTP, mas dessa vez na prática. Apresentaremos novamente sobre as peculiaridades de cada um enquanto criamos as rotas com os 4 principais métodos (GET, POST, PUT e DELETE). Deixaremos o código preparado para que possamos realizar os testes com o Insomnia na próxima aula.


 * GET: Buscar informações do back-end
 * POST: Criar uma informação no back-end
 * PUT/PATCH: Alterar uma informação no back-end
 * DELETE: Deletar uma informação no back-end

 ## Utilizando Insomnia<br />

 Nessa aula iremos começar instalando o Insomnia que é uma ferramenta incrível para nos auxiliar a debugar APIs. Também apresentaremos softwares alternativos caso você prefira e o passo a passo para instalar o tema Dracula. Com o aplicativo instalado, vamos aprender a criar sub environments, montar as requisições para testar as rotas com os 4 métodos HTTP e executá-las para visualizar o retorno em JSON de cada uma delas.
 
 ## Tipos de Parâmetros<br />

 Nessa aula nós vamos aplicar na prática os três tipos de parâmetros: Query Params, Route Params e Request Body. Veremos principalmente como enviá-los pelo Insomnia, como configurar o servidor para recebê-los, como utilizá-los no código e quais parâmetros devem ser utilizados em cada rota.

 ## Aplicação Funcional<br />

 Agora chegou a hora de utilizar os conhecimentos obtidos nas aulas anteriores para montar uma aplicação funcional onde iremos listar, cadastrar, atualizar e deletar projetos. Serão aplicados os 4 métodos HTTP (GET, POST, PUT e DELETE) e os 3 tipos de parâmetros (Query, Route e Body). Também iremos gerenciar os projetos diretamente na memória do servidor utilizando arrays, utilizar o uuid como identificador único de cada projeto e retornar manualmente um HTTP Status Code que melhor condiz com a resposta do servidor.

## Middlewares<br />

 Para finalizar esse módulo, iremos falar sobre middlewares e sua importância nas aplicações que iremos utilizar durante o restante do bootcamp. Serão apresentados o formato do middleware, os seus parâmetros, formas de aplicá-los no código e como utilizá-lo para alterar o fluxo das requisições. Tudo isso utilizando exemplos práticos como o log de todas as requisições feitas para o servidor e a verificação se o id do projeto é um uuid.


## Techs

- [x] node.js
- [x] Insomnia
- [x] Métodos HTTP
- [x] Middlewares
- [x] API REST
- [x] Nodemon

## Starting Dev Environment

```bash
# Clone this repository
$ git clone https://github.com/marcelo-rafael/back-end-com-node.js/
```

1. Run `npm install` or `yarn install`.<br />
2. Run `yarn start` and access `http://localhost:3333`.<br />

## Author

<img  border-radius="50px" src="https://avatars0.githubusercontent.com/u/29902777?s=460&u=61d43667f33a45eb000a2af216e4abeb2d4a6717&v=4" width="100px" alt="Author"/>

Made with: by Marcelo Rafael Gonçalves

<p>
  <a
    href="https://web.whatsapp.com/send?phone=+5511950330322" 
    alt="WhatsApp"
    target="blank"
  >
    <img src="https://img.shields.io/badge/-WhatsApp-4CA143?style=flat&logo=WhatsApp&logoColor=white" />
  </a>
  <a
    href="mailto:marcelo.rafael.goncalves@gmail.com" 
    alt="Gmail"
    target="blank"
  >
    <img src="https://img.shields.io/badge/-Gmail-red?style=flat&logo=Gmaill&logoColor=white" />
    
  </a>
  <a
    href="https://www.linkedin.com/in/marcelo-rafael-gonçalves/" 
    alt="LinkedIn"
    target="blank"
  >
    <img src="https://img.shields.io/badge/-LinkedIn-blue?style=flat&logo=Linkedin&logoColor=white" />
  </a>
</p>
