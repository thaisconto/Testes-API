# Testes-API
Projeto de automação com Postman e Report com Newman

## Instalação
    npm install -g newman
    npm install -g newman-reporter-htmlextra
    
## Execução com report html extra
    newman run signup.json -e env-automacao.json -g env-global.json
