# Produtos API

API REST de gerenciamento de produtos desenvolvida com Java e Spring Boot.

## 🔧 Tecnologias utilizadas

- Java 21
- Spring Boot
  - Spring Web
  - Spring Data JPA
  - Spring Boot DevTools
- Banco de Dados H2 (em memória)
- Lombok
- Maven

## 📦 Funcionalidades

- ✅ Criar um novo produto
- ✅ Listar todos os produtos
- ✅ Buscar um produto por ID
- ✅ Atualizar um produto
- ✅ Remover um produto

## ▶️ Como rodar o projeto

### Pré-requisitos
- Java 21 instalado
- Maven instalado

### Rodando com Maven
```bash
mvn spring-boot:run
````

Ou pela sua IDE, execute a classe principal:
`com.seupacote.ProdutosApiApplication`

## 🌐 Acessos úteis

* **Console do H2**: `http://localhost:8080/h2-console`

> ⚠️ URL do banco no H2 Console: `jdbc:h2:mem:testdb`

## ✍️ Autor

Feito com 💻 por [Darley Rodrigues](https://github.com/darleyrodrigues)