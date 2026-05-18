# CRM Spring Boot JPA

Sistema CRM desenvolvido com Java e Spring Boot para gerenciamento de clientes, utilizando arquitetura RESTful e persistência de dados com Spring Data JPA.

## 🚀 Tecnologias utilizadas

- Java 25
- Spring Boot 4
- Spring Web
- Spring Data JPA
- Maven
- H2 Database
- Hibernate
- Maven Wrapper
- Git + GitHub

---

## 📁 Estrutura do projeto

```bash
src
 ┣ main
 ┃ ┣ java
 ┃ ┃ ┗ com.gestao.crm
 ┃ ┃   ┣ controller
 ┃ ┃   ┣ service
 ┃ ┃   ┣ repository
 ┃ ┃   ┣ entity
 ┃ ┃   ┗ CrmApplication.java
 ┃ ┗ resources
 ┃   ┗ application.properties
 ┗ test
```

---

## ⚙️ Como executar o projeto

### Pré-requisitos

- Java 21+
- Maven
- Git

---

### Clone o repositório

```bash
git clone git@github.com:Viniciusmop/crm-springboot-jpa.git
```

Entre na pasta:

```bash
cd crm-springboot-jpa
```

---

## ▶️ Executando a aplicação

### Pelo VSCode

Abra o projeto e execute a classe:

```java
CrmApplication.java
```

Clique em:

```text
Run
```

---

### Pelo terminal

Windows:

```powershell
.\mvnw.cmd spring-boot:run
```

Linux/Mac:

```bash
./mvnw spring-boot:run
```

---

## 🧪 Executando os testes

Windows:

```powershell
.\mvnw.cmd test
```

Linux/Mac:

```bash
./mvnw test
```

---

## 🌐 A aplicação será iniciada em

```text
http://localhost:8080
```

Actuator:

```text
http://localhost:8080/actuator
```

---

## 🗄️ Banco de dados

O projeto utiliza H2 Database em memória para desenvolvimento.

Console H2 (caso habilitado):

```text
http://localhost:8080/h2-console
```

---

## 📌 Funcionalidades planejadas

- [ ] Cadastro de clientes
- [ ] Atualização de clientes
- [ ] Exclusão de clientes
- [ ] Busca por ID
- [ ] Busca por nome
- [ ] Integração com banco PostgreSQL
- [ ] Swagger/OpenAPI
- [ ] Spring Security + JWT
- [ ] Docker
- [ ] Deploy em nuvem

---

## 📚 Conceitos aplicados

- REST API
- Injeção de dependência
- Arquitetura em camadas
- ORM com Hibernate
- Persistência com JPA
- Maven Lifecycle
- Versionamento com Git
- Boas práticas de backend

---

## 👨‍💻 Autor

Vinícius Murilo

GitHub:
https://github.com/Viniciusmop

LinkedIn:
(adicione seu LinkedIn aqui)

---

## 📄 Licença

Este projeto está sob a licença MIT.
