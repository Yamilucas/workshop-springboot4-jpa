# Projeto API REST com Spring Boot, JPA e Hibernate

Projeto desenvolvido durante o curso **Java COMPLETO: Programação Orientada a Objetos + Projetos**, ministrado por **Nelio Alves**.

A aplicação consiste em uma **API REST desenvolvida com Spring Boot**, tendo como objetivo consolidar os principais conceitos relacionados à construção de serviços web em Java, utilizando **Spring Data JPA**, **Hibernate** e bancos de dados relacionais.

O projeto foi estruturado seguindo a arquitetura em camadas, promovendo organização, desacoplamento e facilidade de manutenção do código. Foram implementadas as camadas de:

* **Resource:** Responsáveis pela exposição dos **endpoints REST**
* **Service:** Contendo as regras de negócio da aplicação
* **Repository:** Responsável pelo acesso e persistência dos dados utilizando **Spring Data JPA**

## Funcionalidades implementadas

* Implementação do modelo de domínio completo
* Mapeamento objeto-relacional com **JPA** e **Hibernate**
* Relacionamentos entre entidades`One-to-One`, `One-to-Many` e `Many-to-Many`
* Persistência de dados com **Spring Data JPA**
* Configuração de banco de dados em memória utilizando **H2** para testes
* Povoamento automático do banco de dados
* Operações **CRUD**
* Tratamento personalizado de exceções
* Injeção de dependências com **Spring**
* Utilização de perfis de execução para diferentes ambientes

## Modelo de domínio

A **API** simula um sistema de pedidos desenvolvido para fins educacionais, contemplando um conjunto de entidades e relacionamentos frequentemente encontrados em aplicações corporativas.

### Estrutura do domínio

O diagrama abaixo apresenta o modelo de domínio da aplicação, evidenciando as entidades e os relacionamentos mapeados com **JPA/Hibernate**.

![image alt](https://github.com/Yamilucas/workshop-springboot4-jpa/blob/main/Modelo_dominio_entidades.jpg?raw=true)

### Exemplo de instâncias do domínio

O diagrama a seguir ilustra um exemplo de objetos instanciados e suas associações durante a execução da aplicação, demonstrando como os dados são organizados e persistidos no sistema.

![image alt](https://github.com/Yamilucas/workshop-springboot4-jpa/blob/main/Instancia%C3%A7%C3%A3o_dominios.jpg?raw=true)

## Tecnologias utilizadas
* Java
* Spring Boot
* Spring Web
* Spring Data JPA
* Hibernate
* Maven
* H2 Database
