# Projeto Intermediário de Angular - Digital Innovation One

Esse projeto foi adaptado de projeto feito para a plataforma [Digital Innovation One](https://digitalinnovation.one/)

Foram incluidos:
* botão voltar na edição de cursos
* logotipos e favicons da Digital Innovation One
* campo de link funcional redirecionando para a url real de cada curso da plataforma
* imagens dos cursos reais
* modificação das cores e layout
* rodapá personalizado

A aplicação consiste em um sistema de cursos online, com a possibilidade de cadastros, edições, listagem e visualização dos cursos.

## Instalação

 Entre no projeto e instale as dependencias `npm install`

## Ambiente Local

Execute `ng serve` para que o projeto suba localmente. Acesse a url `http://localhost:4200/`. O projeto já está com reload automático conforme as alterações que você realizar no código

## Simulando o Back-end

Execute `npm install -g json-server` para instalar globalmente o servidor json. Após a instalação entre na pasta do projeto e execute `json-server --watch db.json`, com isso um servidor será inicializado na url `http://localhost:3000/`, após a inicialização sera possível realizar requisições http.

## Gerando componente

Execute `ng generate component nome-do-componente` para criar um novo componente. Você também pode usuar `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Execute `ng build` para gerar o compilado do projeto. O projeto vai ser criado dentro do diretório `dist/`. Adicionar `--prod` junto comando de build para gerar minificado e pronto para o ambiente de produção.

