# Webchat
[![Build Status](https://travis-ci.org/rogrs/webchat.svg?branch=master)](https://travis-ci.org/rogrs/webchat)
[![codecov](https://codecov.io/gh/rogrs/webchat/branch/master/graph/badge.svg)](https://codecov.io/gh/rogrs/webchat) 
[![License](http://img.shields.io/:license-apache-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)
> Projeto exemplo  de webchat

## Deploy Heroku

Este é um pequeno aplicativo de demonstração para mostrar como executar um [Spring Boot](http://projects.spring.io/spring-boot/)
aplicação em [Heroku](http://heroku.com). Para obter mais informações, consulte o artigo do Dev Center sobre
[Deploying Spring Boot Applications to Heroku](https://devcenter.heroku.com/articles/deploying-spring-boot-apps-to-heroku).

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)


## Requisitos
   Git
   Maven
   Java 8

## Development

Para baixar o codigo fonte execute este comando no terminal:

    git clone https://github.com/rogrs/webchat.git

Execute este comando  no terminal para baixar as dependências da aplicação:

    mvn clean install

Execute este comando no terminal para iniciar a aplicação:

    mvn spring-boot:run

No seu navegado acesse a seguinte url:

    http://localhost:8080/

## License

Code is under the [Apache Licence v2](https://www.apache.org/licenses/LICENSE-2.0.txt).
