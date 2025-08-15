# 🛸 UFO Record — Registro de Atividades de OVNIs

![Java](https://img.shields.io/badge/Java_17-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_3.5.4-%236DB33F.svg?style=for-the-badge&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%2300f.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Thymeleaf](https://img.shields.io/badge/Thymeleaf-%23005C0F.svg?style=for-the-badge&logo=thymeleaf&logoColor=white)

## 📌 Sobre o Projeto
O **UFO Record** é um sistema web para **registrar e acompanhar atividades de OVNIs** observadas ao redor do mundo.  
Seja uma luz estranha no céu, um disco voador em formato de pastel ou um alienígena pedindo informações, aqui você pode cadastrar tudo.

Exemplos de registros possíveis:
- 🌌 Luzes piscando em padrões estranhos
- 🛸 Disco voador realizando manobras impossíveis
- 👽 Contato visual com seres alienígenas
- 📡 Sinais de rádio não identificados

---

## ⚙️ Tecnologias Utilizadas
- **Java 17**
- **Spring Boot 3.5.4**
- **Spring Data JPA**
- **Spring Web**
- **Spring Validation**
- **Thymeleaf**
- **Flyway (migração de banco de dados)**
- **PostgreSQL**
- **Lombok**
- **JUnit 5**

---

## 🛠️ Como Executar o Projeto

### 1️⃣ Pré-requisitos
- Java 17+
- Maven ou Gradle
- PostgreSQL instalado e rodando

### 2️⃣ Configuração do Banco de Dados
Crie um banco no PostgreSQL:
```sql
CREATE DATABASE ufo_record;
```

No arquivo `application.properties` (ou `application.yml`), configure:
```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/superpowers
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
spring.jpa.hibernate.ddl-auto=validate
spring.jpa.show-sql=true
```

### 3️⃣ Rodando a aplicação
Via Gradle:
```bash
./gradlew bootRun
```

Ou via Maven:
```bash
./mvnw spring-boot:run
```

## 🚀 Funcionalidades

- 📋 **Listar** registros de atividades de OVNIs  
- ➕ **Adicionar** novos registros   

---

## 🧪 Testes
Para rodar os testes:
```bash
./gradlew test
```

## 📄 Licença
Este projeto é livre para uso e modificação.
⚠️ Apenas evite enviar coordenadas reais de naves alienígenas — não queremos problemas com a Federação Galáctica.

---

> 👽 "Eles estão entre nós... e agora também no banco de dados."
