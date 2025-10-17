# lab-springboot-fiasco

Projeto criado durante a prática do curso **"Spring Boot em 1 Hora"**, do canal [**Fiasco**](https://www.youtube.com/@fiascodev) no YouTube.  
Implementa conceitos fundamentais do **Spring Boot** para a construção de uma **API REST**.

---

## 🚀 Tecnologias Utilizadas

- **Java 17**  
- **Spring Boot 3**  
- **Maven**  
- **Spring Web**  
- **Spring Data JPA**  
- **H2 Database**

---

## 🧩 Funcionalidades

- Criação de endpoints REST.  
- Persistência de dados em banco H2 em memória.  
- Utilização de repositórios com **Spring Data JPA**.  
- Teste de endpoints via **Postman** ou **Insomnia**.  

---

## ⚙️ Como Executar o Projeto

### 1️⃣ Clonar o repositório

```bash
git clone https://github.com/seu-usuario/lab-springboot-fiasco.git
cd lab-springboot-fiasco
```

### 2️⃣ Compilar e executar

Se estiver usando **Maven**:

```bash
mvn spring-boot:run
```

Ou, se preferir, importe o projeto em uma IDE como **IntelliJ** ou **Eclipse** e execute a classe principal `LabSpringbootFiascoApplication`.

### 3️⃣ Acessar a aplicação

A API estará disponível em:

```
http://localhost:8080
```

---

### 🗄️ Banco de Dados H2

O projeto utiliza banco H2 em memória:

Console H2: http://localhost:8080/h2-console

JDBC URL: jdbc:h2:mem:testdb

Usuário: sa

Senha: (vazia)


---

## 🧠 Conceitos Estudados

- Estrutura básica de um projeto Spring Boot  
- Injeção de dependências  
- Controllers, Services e Repositories  
- Configuração de banco H2  
- Testes de API com dados persistidos  

---

## 🗂 Estrutura do Projeto

```
src/
 ├── main/
 │   ├── java/com/exemplo/labspringbootfiasco/
 │   │   ├── controller/
 │   │   ├── model/
 │   │   ├── repository/
 │   │   └── service/
 │   └── resources/
 │       ├── application.properties
 │       └── data.sql
 └── test/
     └── ...
```

---

## 🧑‍💻 Autor

**Éder Luís Britto Garcia**  
📚 Projeto educacional desenvolvido com base no curso *Spring Boot em 1 Hora* — Canal **Fiasco**.  

---

## 📝 Licença

Este projeto é de uso livre para fins educacionais.  
Sinta-se à vontade para modificar e compartilhar.
