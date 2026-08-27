# 🚀 APIs Styles

Repositório dedicado ao estudo e à prática de **APIs (Application Programming Interfaces)**, com foco em entender desde os fundamentos do protocolo HTTP até o desenvolvimento, consumo, autenticação, testes e documentação de APIs REST.

A ideia é combinar **teoria + exercícios + projetos práticos**, construindo uma base sólida para desenvolvimento Backend.

---

## 🎯 Objetivos

- Entender o que são APIs e como elas funcionam
- Dominar os fundamentos do protocolo HTTP
- Aprender a consumir APIs externas
- Entender o conceito de API REST
- Criar APIs do zero
- Trabalhar com JSON
- Implementar CRUD
- Integrar APIs com bancos de dados
- Implementar autenticação e autorização
- Aprender a testar APIs
- Documentar APIs
- Desenvolver projetos completos

---

## 🧠 Roadmap de Estudos

### 1. Fundamentos

- [ ] O que é uma API?
- [ ] Client x Server
- [ ] Request x Response
- [ ] Protocolo HTTP
- [ ] Métodos HTTP
  - [ ] `GET`
  - [ ] `POST`
  - [ ] `PUT`
  - [ ] `PATCH`
  - [ ] `DELETE`
- [ ] Status Codes
  - [ ] `2xx`
  - [ ] `3xx`
  - [ ] `4xx`
  - [ ] `5xx`
- [ ] Headers
- [ ] Body
- [ ] Query Parameters
- [ ] Path Parameters
- [ ] Cookies

---

### 2. JSON

- [ ] Estrutura JSON
- [ ] Objetos
- [ ] Arrays
- [ ] Tipos de dados
- [ ] Serialização
- [ ] Desserialização
- [ ] JSON em requests
- [ ] JSON em responses

---

### 3. REST APIs

- [ ] O que é REST?
- [ ] Recursos
- [ ] Endpoints
- [ ] REST x RESTful
- [ ] Stateless
- [ ] CRUD
- [ ] Boas práticas para endpoints
- [ ] Versionamento de APIs
- [ ] Paginação
- [ ] Filtros
- [ ] Ordenação

Exemplo:

```text
GET    /users
GET    /users/10
POST   /users
PUT    /users/10
PATCH  /users/10
DELETE /users/10
```

---

### 4. Consumindo APIs

- [ ] Fazer requests HTTP
- [ ] Utilizar `curl`
- [ ] Utilizar Postman
- [ ] Utilizar APIs públicas
- [ ] Interpretar responses
- [ ] Enviar headers
- [ ] Enviar parâmetros
- [ ] Enviar JSON
- [ ] Tratar erros

Exemplo:

```bash
curl https://api.example.com/users
```

---

### 5. Desenvolvimento de APIs

Foco principal: **Golang**

- [ ] Criar servidor HTTP
- [ ] Criar rotas
- [ ] Criar handlers
- [ ] Receber requests
- [ ] Retornar responses
- [ ] Trabalhar com JSON
- [ ] Middleware
- [ ] Tratamento de erros
- [ ] Validação de dados
- [ ] Organização de projetos

---

### 6. Banco de Dados

- [ ] Conectar API a um banco
- [ ] PostgreSQL
- [ ] CRUD com banco de dados
- [ ] Queries
- [ ] Transactions
- [ ] Migrations
- [ ] Relacionamentos
- [ ] ORM / Query Builders

---

### 7. Autenticação e Segurança

- [ ] Authentication x Authorization
- [ ] Sessions
- [ ] Cookies
- [ ] JWT
- [ ] Access Token
- [ ] Refresh Token
- [ ] Hash de senhas
- [ ] CORS
- [ ] Rate Limiting
- [ ] HTTPS
- [ ] Variáveis de ambiente
- [ ] Boas práticas de segurança

---

### 8. Testes

- [ ] Testes unitários
- [ ] Testes de integração
- [ ] Testes de endpoints
- [ ] Testes de erros
- [ ] Mocking
- [ ] Testes automatizados

---

### 9. Documentação

- [ ] Documentar endpoints
- [ ] Request examples
- [ ] Response examples
- [ ] OpenAPI
- [ ] Swagger
- [ ] Gerar documentação automaticamente

---

### 10. Projeto Final

Construir uma API completa aplicando os conceitos estudados.

**Exemplo: API de gerenciamento de tarefas**

Funcionalidades:

- [ ] Cadastro de usuários
- [ ] Login
- [ ] Autenticação
- [ ] CRUD de tarefas
- [ ] Filtros
- [ ] Paginação
- [ ] PostgreSQL
- [ ] Validação
- [ ] Tratamento de erros
- [ ] Testes
- [ ] Documentação
- [ ] Docker

---

## 📂 Estrutura do Repositório

```text
api-learning/
│
├── README.md
│
├── notes/
│   ├── http.md
│   ├── rest.md
│   ├── json.md
│   ├── authentication.md
│   └── security.md
│
├── exercises/
│   ├── 01-http/
│   ├── 02-json/
│   ├── 03-rest/
│   ├── 04-consuming-apis/
│   ├── 05-building-apis/
│   ├── 06-authentication/
│   └── 07-testing/
│
├── projects/
│   ├── 01-first-api/
│   ├── 02-crud-api/
│   └── 03-final-project/
│
└── api/
    └── ...
```

---

## 🛠️ Ferramentas

| Ferramenta        | Utilização              |
| ----------------- | ----------------------- |
| Go                | Desenvolvimento Backend |
| HTTP              | Comunicação             |
| JSON              | Formato de dados        |
| PostgreSQL        | Banco de dados          |
| Postman           | Testes e requisições    |
| cURL              | Requisições HTTP        |
| Swagger / OpenAPI | Documentação            |
| Docker            | Containerização         |
| Git               | Versionamento           |

---

## 📚 Metodologia

Cada tópico será estudado seguindo o ciclo:

```text
Teoria
  ↓
Exemplo
  ↓
Exercício
  ↓
Implementação
  ↓
Projeto
```

O objetivo não é apenas memorizar conceitos, mas **entender como uma API funciona internamente e conseguir construir uma do zero**.

---

## 📈 Progresso

| Etapa                   | Status |
| ----------------------- | ------ |
| HTTP                    | ⬜      |
| JSON                    | ⬜      |
| REST                    | ⬜      |
| Consumo de APIs         | ⬜      |
| Desenvolvimento de APIs | ⬜      |
| Banco de Dados          | ⬜      |
| Autenticação            | ⬜      |
| Segurança               | ⬜      |
| Testes                  | ⬜      |
| Documentação