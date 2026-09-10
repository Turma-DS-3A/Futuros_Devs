# Back End Semana 15 - Servidores Web, APIs e Segurança das Aplicações

# 🌐 Servidores Web, HTTP e APIs com Python

Este repositório contém estudos e práticas relacionados ao funcionamento de aplicações **Web**, comunicação entre **Cliente e Servidor**, protocolo **HTTP**, desenvolvimento de **APIs** e utilização de **frameworks Python**.

---

# 📚 Conteúdos estudados

Neste projeto são abordados os seguintes conceitos:

- 🌐 Servidores Web
- 📡 Protocolo HTTP
- 📥 Request (Requisição)
- 📤 Response (Resposta)
- 🔎 GET
- ➕ POST
- ✏️ PUT
- 🗑️ DELETE
- 🔌 APIs
- 🐍 Frameworks Python
- 🌶️ Flask

---

# 🌐 Servidores Web

Um **Servidor Web** é responsável por receber solicitações feitas por clientes, processá-las e enviar uma resposta.

A comunicação acontece entre duas partes principais:

```text
CLIENTE  →  SERVIDOR
```

O cliente pode ser:

- Navegador
- Aplicativo Mobile
- Sistema Front-end
- Outra aplicação

O servidor recebe as solicitações e responde de acordo com a necessidade da aplicação.

---

# 📡 HTTP

O **HTTP (HyperText Transfer Protocol)** é um protocolo utilizado para permitir a comunicação entre o **Cliente** e o **Servidor**.

Essa comunicação acontece através de:

```text
CLIENTE
   ↓
REQUEST
   ↓
SERVIDOR
   ↓
RESPONSE
   ↓
CLIENTE
```

---

# 📥 Request

**Request** significa **Requisição**.

É a solicitação enviada pelo cliente para o servidor.

Por exemplo, quando um usuário acessa uma página, envia dados em um formulário ou solicita informações de uma API, uma requisição é realizada.

---

# 📤 Response

**Response** significa **Resposta**.

Após receber uma requisição, o servidor processa a solicitação e envia uma resposta para o cliente.

Essa resposta pode conter:

- Informações
- Dados
- Mensagens
- Arquivos
- Códigos de status HTTP

---

# 🔄 Métodos HTTP

Os métodos HTTP indicam qual tipo de ação será realizada durante a comunicação entre o cliente e o servidor.

| Método | Ação |
|---|---|
| GET | Consultar informações |
| POST | Criar informações |
| PUT | Atualizar informações |
| DELETE | Remover informações |

---

# 🔎 GET

O método **GET** é utilizado para solicitar ou consultar informações.

Exemplo:

```text
GET /usuarios
```

---

# ➕ POST

O método **POST** é utilizado para enviar informações para o servidor, geralmente para criar novos dados.

Exemplo:

```text
POST /usuarios
```

---

# ✏️ PUT

O método **PUT** é utilizado para atualizar informações existentes.

Exemplo:

```text
PUT /usuarios
```

---

# 🗑️ DELETE

O método **DELETE** é utilizado para remover informações.

Exemplo:

```text
DELETE /usuarios
```

---

# 🔄 CRUD

Os métodos HTTP estão relacionados ao conceito de **CRUD**.

CRUD representa as quatro operações básicas realizadas em sistemas:

| CRUD | Significado | Método HTTP |
|---|---|---|
| Create | Criar | POST |
| Read | Consultar | GET |
| Update | Atualizar | PUT |
| Delete | Remover | DELETE |

---

# 🔌 API

**API** significa:

> Application Programming Interface

Ou:

> Interface de Programação de Aplicações.

Uma API permite a comunicação entre diferentes sistemas e aplicações.

Por exemplo:

```text
FRONT-END
    ↓
   API
    ↓
BACK-END
    ↓
BANCO DE DADOS
```

Uma API pode ser utilizada por diferentes aplicações:

```text
SITE ────────┐
             ↓
APLICATIVO → API → SERVIDOR
             ↑
OUTRO SISTEMA┘
```

---

# 🐍 Frameworks Python

Um **framework** fornece ferramentas e estruturas que auxiliam no desenvolvimento de aplicações.

No Python existem diversos frameworks utilizados para desenvolvimento Web e criação de APIs.

Alguns exemplos são:

### 🌶️ Flask

Framework leve e simples, muito utilizado para desenvolvimento de aplicações Web e APIs.

### 🎸 Django

Framework mais completo, utilizado para o desenvolvimento de aplicações Web maiores e mais estruturadas.

### ⚡ FastAPI

Framework moderno voltado principalmente para o desenvolvimento de APIs, conhecido pela performance e documentação automática.

---

# 🌶️ Flask

Neste projeto, o framework **Flask** é utilizado para compreender o desenvolvimento de aplicações Web e APIs utilizando Python.

O Flask permite trabalhar com conceitos como:

- Rotas
- Endpoints
- Request
- Response
- Métodos HTTP
- Dados em JSON
- APIs

---

# 🔗 Relação entre os conceitos

A estrutura dos conteúdos estudados pode ser representada da seguinte forma:

```text
                    DESENVOLVIMENTO WEB
                           │
                           ▼
                    SERVIDOR WEB
                           │
                           ▼
                         HTTP
                           │
              ┌────────────┴────────────┐
              ▼                         ▼
           REQUEST                   RESPONSE
              │
              ▼
        MÉTODOS HTTP
              │
     ┌────────┼────────┬────────┐
     ▼        ▼        ▼        ▼
    GET      POST      PUT    DELETE
     │        │        │        │
     └────────┴────────┴────────┘
              │
              ▼
             API
              │
              ▼
      FRAMEWORK PYTHON
              │
      ┌───────┼────────┐
      ▼       ▼        ▼
    Flask   Django   FastAPI
```

---

# 🛠️ Tecnologias utilizadas

- 🐍 Python
- 🌶️ Flask
- 📡 HTTP
- 🔌 APIs
- 🧪 Thunder
- 🐙 Git
- 🐱 GitHub

---

# 🎯 Objetivo

O objetivo deste repositório é registrar e praticar conhecimentos fundamentais relacionados ao **Desenvolvimento Web e Back-end**, compreendendo como acontece a comunicação entre aplicações através de servidores, protocolos HTTP e APIs.

---

# 👨‍💻 Autor

**Alunos Protagonistas **

📚 Projeto desenvolvido para fins de estudo e aprendizado em **Python, Desenvolvimento Web e APIs**.


