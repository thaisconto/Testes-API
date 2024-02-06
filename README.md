# Testes-API
Projeto de automação com Postman e Report com Newman

## Instalação

Abrir o projeto no VS-Code, e no terminal realizar as seguintes instalações: 

    npm install -g newman
    npm install -g newman-reporter-htmlextra
    
## Execução com report html extra

Após instalação, inserir o comando abaixo para rodar os testes:

    newman run automa-api-academy-t10.json -e env-automacao.json -g env-global.json -r cli,htmlextra

## Abrir relatório

Após a execução, irá gerar um relatório automaticamente, conforme indicado abaixo:

<img src = print1.png>
