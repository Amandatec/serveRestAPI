# Bootcamp #01 Qualiters Club
Testes de API Rest de manual a CI/CD 

## O que é

Este repositório foi criado para o Bootcamp de Teste de API Rest.

## Tecnologias utilizadas

- Postman web version

- node v16.18.0

- newman v6.0.0

- newman reporter-html

## Documentação

- Doc da API: [Consulte Swagger](https://serverest.dev/)

## Como instalar o ambiente

- Primeiro: instale o node em seu computador [baixe aqui](https://nodejs.org/en/download)

- Segundo: realize a instalação do newman de forma global [baixe aqui a dependência](https://www.npmjs.com/package/newman)

```
$ npm install -g newman
```

- Terceiro: realize a instalação da dependência dos relatórios (opcional) 
 [](https://www.npmjs.com/package/newman_reporter-html)

 ```
npm install -g newman-reporter-html
```
## Como rodar os testes

### Pelo Postman web ou desktop
- Importe a collection e o environment
- Execute a seguinte linha de comando para rodar os testes
 ```
    newman run serveRest.postman_collection.json -e serveRest.postman_environment.json -r cli
  ```

- Execute os testes com relatório
```
  newman run serveRest.postman_collection.json -e serveRest.postman_environment.json -r cli,htmlextra
```
### Report

Se você optou por rodar os testes com o report htmlextra, você gerou um arquivo html com o resultado dos teses e para verificar as validações você pode abrir a pasta **newman** que foi criada no local em que os arquivos de collection e environment se encontram.

## Entre em contato

 <a href="https://www.linkedin.com/in/amandaoliveira--/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" style="margin-right: 2vw" target="_blank"></a>
<a href="http://discordapp.com/users/Amandatec#4699" target="_blank"><img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white" target="_blank"></a>
  <a href="https://www.instagram.com/amanda_almajor/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a href = "mailto:amandatec.oliveira@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>

 Made by [**Amandatec**](https://www.linkedin.com/in/amandaoliveira--/))
