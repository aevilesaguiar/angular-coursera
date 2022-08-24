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


