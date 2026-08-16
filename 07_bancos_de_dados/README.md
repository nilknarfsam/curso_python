# 🗄️ Módulo 07: Bancos de Dados com Python (SQLite3 & MySQL)

A persistência relacional de dados é fundamental para qualquer aplicação profissional. Neste módulo você aprenderá a conectar, consultar, inserir, atualizar e deletar dados em **SQLite3** e **MySQL / MariaDB**, utilizando boas práticas contra **SQL Injection**, controle de transações e ambientes conteinerizados com **Docker**.

---

## 🎯 Objetivos de Aprendizagem

- Compreender a linguagem SQL (DDL e DML): `CREATE TABLE`, `INSERT`, `SELECT`, `UPDATE`, `DELETE`.
- Conectar ao banco embutido **SQLite3** nativo do Python (`sqlite3`).
- Utilizar cursores, `cursor.execute()`, `cursor.executemany()`, `cursor.fetchone()` e `cursor.fetchall()`.
- Prevenir vulnerabilidades de SQL Injection utilizando bindings/placeholders (`:param` ou `%s`).
- Gerenciar transações com integridade (`commit` e `rollback`).
- Subir um banco de dados **MySQL** local usando **Docker Compose**.
- Conectar ao MySQL via biblioteca **PyMySQL** com cursores de dicionário (`pymysql.cursors.DictCursor`).

---

## 🗺️ Projetos e Pastas Inclusas

### 1. 🪶 [aula205/](file:///d:/PROJETOS/curso_python/07_bancos_de_dados/aula205) — SQLite3 com Python
- `main.py`: Criação de tabela `customers`, inserção de múltiplos registros com dicionários, atualização (`UPDATE`), exclusão segura com `WHERE` e consultas (`SELECT`).
- `select.py`: Consulta refinada de registros com limite e ordenação.

### 2. 🐬 [aula206/](file:///d:/PROJETOS/curso_python/07_bancos_de_dados/aula206) — MySQL / MariaDB com PyMySQL & Docker
- `docker-compose.yml`: Configuração do container MySQL 8.0 / MariaDB com porta exposta `3306` e volume persistente.
- `.env-example`: Modelo de variáveis de ambiente para host, usuário, senha e nome do banco.
- `main.py`: Conexão com pooling, gerenciamento de contexto `with connection:`, execução de operações CRUD completas e cursores retornando dicionários.

---

## 🚀 Como Executar

### 1. Testando o SQLite3 (Sem necessidade de instalar servidores):
```bash
python 07_bancos_de_dados/aula205/main.py
python 07_bancos_de_dados/aula205/select.py
```

### 2. Testando o MySQL com Docker:
```bash
cd 07_bancos_de_dados/aula206

# Copiar o arquivo de variáveis de ambiente
cp .env-example .env

# Iniciar o container MySQL em background
docker compose up -d

# Executar as queries no banco MySQL
python main.py
```
