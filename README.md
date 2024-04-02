# Explorando Padrões de Projetos na Prática com Java

Este repositório contém as implementações dos padrões de projeto explorados no Lab "*Explorando Padrões de Projetos na Prática com Java*", realizado na plataforma da Digital Innovation One (DIO). Aqui, você encontrará um `projeto Java` que demonstra a aplicação de padrões de projeto utilizando o  `Spring Framework`..

## Objetivo

O objetivo deste repositório é proporcionar um exemplo prático do uso de padrões de projeto em um ambiente de desenvolvimento Java, utilizando ferramentas e conceitos modernos como Spring Boot, JPA (Java Persistence API) com Hibernate e a integração com serviços externos através do Spring Cloud OpenFeign.

## Padrões de Projeto Implementados

Os padrões de projeto implementados neste projeto incluem:

- **Singleton**: Garantia de que uma classe tenha apenas uma instância e forneça um ponto de acesso global a essa instância.
  
- **Repository**: Abstração para acesso a dados, fornecendo métodos para interagir com a camada de persistência.
  
- **Facade**: Provê uma interface unificada para um conjunto de interfaces em um subsistema, simplificando sua utilização.

## Estrutura do Projeto

O projeto está estruturado em camadas distintas, seguindo boas práticas de desenvolvimento:

- **Model**: Contém as classes de modelo, como `Cliente` e `Endereco`.
  
- **Repository**: Responsável pela interação com o banco de dados, utilizando o Spring Data JPA.
  
- **Service**: Implementa a lógica de negócios da aplicação, incluindo a integração com o serviço ViaCEP.
  
- **Controller**: Fornece endpoints REST para acessar e manipular os recursos da aplicação.

## Começando

Para executar o projeto localmente, siga estas etapas:

1. Clone este repositório para o seu ambiente de desenvolvimento.
2. Certifique-se de ter o Apache Maven instalado em sua máquina.
3. Importe o projeto em sua IDE Java de preferência.
4. Configure as dependências do projeto utilizando o Maven.
5. Execute a classe `Application.java` para iniciar a aplicação.

## Referências e Documentação

Para mais informações sobre as tecnologias utilizadas e conceitos abordados neste projeto, consulte a documentação oficial e os guias de referência fornecidos abaixo:

- [Documentação Oficial do Apache Maven](https://maven.apache.org/guides/index.html)
  
- [Documentação do Spring Boot](https://docs.spring.io/spring-boot/docs/3.2.4/reference/htmlsingle/)
  
- [Spring Data JPA](https://docs.spring.io/spring-boot/docs/3.2.4/reference/htmlsingle/#data.sql.jpa-and-spring-data)
  
- [Spring Web](https://docs.spring.io/spring-boot/docs/3.2.4/reference/htmlsingle/#web)
  
- [OpenFeign](https://docs.spring.io/spring-cloud-openfeign/docs/current/reference/html/)

## Observações

Este projeto é parte de um desafio proposto pela Digital Innovation One e visa explorar e aplicar os conceitos aprendidos durante o Lab "Explorando Padrões de Projetos na Prática com Java". Sinta-se à vontade para contribuir com melhorias, sugestões ou correções de bugs. Se precisar de ajuda ou orientação adicional, entre em contato!

Aproveite este projeto para aprimorar seus conhecimentos em padrões de projeto na prática com Java!
