# Projeto Carros Spring + Angular

Projeto desenvolvido para exercitar os conhecimentos na linguagem Java utilizando o Framework Spring, utilizando Spring Data JPA, Spring Validation, Spring Security, Autenticação via Token JWT e Oauth2.

No Front-end, foi construído utilizando Angular, visando principalmente aprender mais sobre esse framework.

## Instruções para Rodar (BACK-END)

- 1°Passo: rodaremos o comando (git clone) no projeto, vamos importar o projeto Back-end, na IDE Java de sua preferência.

- 2°Passo: Iremos agora, entrar no arquivo application.properties, e configurarmos as configurações de banco, eu utilizei o Postgres, se houver a necessidade de trocar, basta alterar o Driver as configurações, e trocar a dependência no POM.xml

- 3°Passo: Iremos nos conectar ao banco configurado, e rodaremos o script DDL para criarmos as tabelas e constraints que iremos utilizar no projeto, que pode ser encontrada no arquivo (create.sql) localizado na raiz do projeto.

- 4°Passo: Depois de seguirmos todos esses passos, podemos subir nossa aplicação já conectada ao nosso BD.

## Instruções para Rodar (FRONT-END)

- 1°Passo: Após rodar o primeiro passo das instruções de back-end, você já vai ter o projeto angular na sua máquina, basta entrarmos na raiz dele e abrirmos um terminal.

- 2°Passo: Imagino que você tenha ou Yarn ou NPM instalado na sua máquina, no meu caso utilizarei o NPM, no terminal que abrimos no primeiro passo, iremos digitar o comando npm install

- 3°Passo: nesse mesmo terminal, iremos rodar o comando ng serve

- 4°Passo: Depois de seguirmos todos esses passos, nossa aplicação angular já estará de pé, devemos agora, subir tanto nosso Back, quanto nosso front, para garantir que a comunicação deles seja feita.
