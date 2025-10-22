🛒 Sistema de Produtos

Node.js + MySQL + Sequelize


⚡ Instalação
bashnpm install express sequelize mysql2 ejs dotenv body-parser
sqlCREATE DATABASE produtos_db;
envDB_HOST=localhost
DB_USER=root
DB_PASS=sua_senha
DB_NAME=produtos_db
bashnpm start
```

---

## 📊 Tabela Produtos

| Campo | Tipo | Descrição |
|-------|------|-----------|
| id | INTEGER | PK, Auto Increment |
| descricao | VARCHAR(255) | Nome do produto |
| quantidade | INTEGER | Estoque |
| valor | DECIMAL(10,2) | Preço |
| data | DATE | Data cadastro |

---

🛣️ Rotas

GET /produtos → Lista produtos
GET /produtos/novo → Formulário
POST /produtos → Cadastra e redireciona


✨ Features
✅ Listar produtos
✅ Cadastrar produto
✅ Layout responsivo
✅ Redirecionamento automático

🔧 Stack
Node.js • Express • MySQL • Sequelize • EJS • Bootstrap

📚 Projeto Educacional
