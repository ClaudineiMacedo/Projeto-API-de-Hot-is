# 🏨 API REST de Hotéis — Flask & Python

Este projeto é uma **API REST desenvolvida em Python utilizando Flask e Flask-RESTful**, com operações completas de CRUD para gerenciamento de hotéis.

O objetivo do projeto é **praticar conceitos de backend**, arquitetura REST, organização de código e boas práticas, visando oportunidades de **estágio em desenvolvimento backend**.

---

## 🚀 Tecnologias Utilizadas

- Python 3
- Flask
- Flask-RESTful
- POO (Programação Orientada a Objetos)
- Arquitetura REST

---

## 📌 Funcionalidades

- 📄 Listar todos os hotéis
- 🔍 Buscar hotel por ID
- ➕ Cadastrar novo hotel
- ✏️ Atualizar hotel existente
- ❌ Remover hotel
- ⚠️ Validação básica de dados
- 📦 Uso de Model para organização do código

---

## 📂 Estrutura do Projeto

├── app.py
├── resources
│ └── hotel.py
├── models
│ └── hotel.py
└── README.md

---

## 🔗 Endpoints da API

### 🔹 Listar hotéis
**GET**
/hoteis

### 🔹 Buscar hotel por ID
**GET**
/hoteis/<hotel_id>

### 🔹 Criar hotel
**POST**
/hoteis/<hotel_id>

**Body (JSON):**
```json
{
  "nome": "Hotel Exemplo",
  "estrelas": 4.5,
  "diaria": 350.00,
  "cidade": "São Paulo"
}
🔹 Atualizar hotel
PUT

/hoteis/<hotel_id>
🔹 Deletar hotel
DELETE

/hoteis/<hotel_id>
▶️ Como Executar o Projeto
Clone o repositório:

Instale as dependência

pip install flask flask-restful
Execute a aplicação:

python app.py
Acesse:
http://127.0.0.1:5000/hoteis
