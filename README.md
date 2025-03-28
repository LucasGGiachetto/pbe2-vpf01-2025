# 🍕 API Pizzaria Ginno e Silva

<div align="center">
  <img src="https://img.shields.io/badge/Node.js-18+-339933?style=for-the-badge&logo=node.js&logoColor=white">
  <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white">
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
</div>

## 📋 Sobre o Projeto

API RESTful para sistema de gerenciamento de pizzaria desenvolvida como projeto acadêmico, contemplando:

- Cadastro de clientes
- Gerenciamento de cardápio
- Controle de pedidos
- Gestão de itens dos pedidos

## 🛠 Tecnologias Utilizadas

- **Node.js** - Ambiente de execução JavaScript
- **Express** - Framework para construção da API
- **Prisma** - ORM para acesso ao banco de dados
- **MySQL** - Sistema de banco de dados relacional
- **Insomnia** - Cliente REST para testes da API

## 🚀 Começando

### Pré-requisitos

- Node.js 18+
- MySQL 8.0+ (ou XAMPP)
- Insomnia (opcional para testes)
- Git (opcional para clonar o repositório)

### ⚙️ Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/pbe2-vpf01-2025.git
cd pbe2-vpf01-2025/api
```
2. Instale as dependências:
```bash
npm i express dotenv routes
```
```bash
npm install prisma @prisma/client
```

3. Configure o banco de dados:
```bash
npx prisma migrate dev --name init
npx prisma generate
```
- Configure as credenciais no arquivo .env (use .env.example como base)

### 🔧 Configuração
## Variáveis de Ambiente (.env
```bash
DATABASE_URL="mysql://usuario:senha@localhost:3306/pizzaria"
PORT=3000
```

### Estrutura de Diretórios
```bash
/api
  /controllers
  /routes
  /models
  /prisma
    schema.prisma
  .env
  index.js
```

### Inicie o servidor:
```bash
nodemon
```
ou

```bash
node server.js
```
