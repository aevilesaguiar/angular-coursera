# ConFusion

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.1.3.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.


## Gerando e Servindo um Projeto Angular usando Angular-CLI

Isso deve criar uma nova pasta chamada conFusion dentro de sua pasta Angular e criar o aplicativo Angular nessa pasta.

ng new ConFusion

Isso compilará o projeto e abrirá uma guia em seu navegador padrão no endereço http://localhost:4200 .

ng serve --open

## Visão geral da arquitetura de aplicativos com Angular

Os aplicativos em angular são construídos como uma combinaçãode HTML e TypeScript ou JavaScript.
Usaremos o TypeScript como a linguagem de escolha para construir nosso aplicativo Angular.O próprio Angular consiste em várias bibliotecas,algumas delas chamadas bibliotecas e outras são bibliotecas opcionais.Dependendo do tipo de aplicativo Angular que você está tentando construir,você incluirá alguns deles em seu aplicativo.Como já aprendemos, Angular é um framework JavaScript e vamos aproveitar isso para construir nosso aplicativo.

Para resumir a aplicação Angular é modular em sua natureza e consistirá em vários componentes, juntamente com seus templates, que compóem a aplicação. Os componentes , e outras partes do aplicativo Angular, como  os serviços , serão organizados  em módulos. Esses Módulos por sua vez serão utilizados por módulos de nível superior.

Então um aplicativo Angular pode ser visto como tendo uma arquitetura modular, com um módulo raiz no topo, que conta com a ajuda de outros módulos organizados em sua hierrquia de modulos. 

![image](https://user-images.githubusercontent.com/52088444/186511694-9186f51c-c6d1-4ec4-b367-f7507137642f.png)


O módulo raiz padrão do angular é chamado de app.module.


## Angular material instalação CLI

ng add @angular/material

## Flex layout

Getting Started
Start by installing the Angular Layout library from npm

npm i -s @angular/flex-layout @angular/cdk

Next, you'll need to import the Layout module in your app's module.

app.module.ts

import { FlexLayoutModule } from '@angular/flex-layout';
...

@NgModule({
    ...
    imports: [ FlexLayoutModule ],
    ...
});
After that is configured, you can use the Angular Layout attributes in your HTML tags for flex layout:

<div fxLayout="row" fxLayoutAlign="space-between">
</div>
Check out all of the available options for using Angular Layout in your application.

## Instalando hammer js

npm install --save angular-hammer


## Inversão de controle

Na engenharia de software , a inversão de controle ( IoC ) é um princípio de programação. IoC inverte o fluxo de controle em comparação com o fluxo de controle tradicional. Em IoC, partes personalizadas de um programa de computador recebem o fluxo de controle de uma estrutura genérica . Uma arquitetura de software com esse design inverte o controle em relação à programação procedural tradicional : na programação tradicional, o código personalizado que expressa o objetivo do programa chamaem bibliotecas reutilizáveis ​​para cuidar de tarefas genéricas, mas com a inversão de controle, é a estrutura que chama o código personalizado ou específico da tarefa.
A inversão de controle é usada para aumentar a modularidade do programa e torná-lo extensível , [1] e tem aplicações em programação orientada a objetos e outros paradigmas de programação . 


## Referencias

- https://github.com/angular/flex-layout
- https://angular.io/
- https://angular.io/cli
- https://material.angular.io/
- https://material.angular.io/components/toolbar/overview
- https://github.com/angular/flex-layout
- https://github.com/angular/flex-layout/wiki/API-Documentation
- https://www.netguru.com/blog/imperative-vs-declarative
- https://hackernoon.com/5-best-javascript-frameworks-in-2017-7a63b3870282#.tt1k09l1d
- http://codenugget.co/2015/03/05/declarative-vs-imperative-programming-web.html





