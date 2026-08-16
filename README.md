# 🐍 Curso de Python 3 — Do Básico ao Avançado

Repositório pessoal de estudos e projetos práticos cobrindo toda a trilha de aprendizado de **Python 3**, desde os fundamentos de sintaxe até tópicos avançados como Programação Orientada a Objetos (POO), Interfaces Gráficas (GUI) com PySide6, Bancos de Dados (SQLite e MySQL), Automação / Web Scraping e Desenvolvimento Web com Django.

---

## 📌 Visão Geral do Conteúdo

Este repositório está organizado em scripts sequenciais de aulas (`aula1.py` até `aula207`) e projetos modulares:

```
curso_python/
├── aula1.py ... aula140.py       # Fundamentos, Estruturas de Dados e Programação Funcional
├── aula141/ ... aula160.py       # Programação Orientada a Objetos (POO) & Dataclasses
├── aula161.py ... aula194.py     # Módulos Padrão, Automação, Web Scraping & Manipulação de Arquivos
├── aula195.ipynb ...             # Jupyter Notebooks e análise exploratória
├── aula202-calculadora/          # Projeto GUI: Calculadora completa em PySide6 / Qt6
├── aula203-qtdesigner/           # Interfaces com Qt Designer e compilação de .ui para .py
├── aula204/                      # QThread, processamento assíncrono e UI responsiva
├── aula205/                      # Banco de dados SQLite3 com Python
├── aula206/                      # Banco de dados MySQL / MariaDB via PyMySQL e Docker Compose
├── aula207_ola_django/           # Introdução ao framework web Django (MVT, rotas, templates)
└── requirements.txt              # Dependências completas do ambiente de estudos
```

---

## 📚 Trilha de Aprendizado

### 1. Fundamentos & Estruturas de Dados (Aulas 1 a 100)
- **Tipos de dados**: `str`, `int`, `float`, `bool`, coerção e interpolação de strings (`f-strings`, `.format()`).
- **Controle de Fluxo**: Condicionais (`if`, `elif`, `else`), operadores lógicos e de comparação.
- **Estruturas de Repetição**: `while` e `for` com `range`, `enumerate` e `zip`.
- **Coleções**: Listas (`list`), Tuplas (`tuple`), Dicionários (`dict`) e Conjuntos (`set`).
- **Comprehensions**: List / Dict / Set Comprehensions.
- **Funções**: Argumentos posicionais, nomeados, `*args`, `**kwargs`, closures, funções de primeira classe e funções lambda.
- **Tratamento de Erros**: Blocos `try`, `except`, `else`, `finally` e `raise`.

### 2. Programação Funcional & Módulos Avançados (Aulas 101 a 140)
- Decoradores (`@decorador`) e sintaxe com parâmetros.
- Geradores (`yield`), Iteradores e `itertools` (`groupby`, `combinations`, `permutations`, `product`).
- Manipulação de arquivos com contexto `with` (`open`, modo `w`, `r`, `a+`, `json`, `csv`).
- Modularização (`import`, `from ... import`, criação de packages e `__init__.py`).

### 3. Programação Orientada a Objetos (Aulas 141 a 160)
- Classes, atributos de classe e de instância.
- Métodos de instância, `@classmethod` (factory methods) e `@staticmethod`.
- Encapsulamento, `@property`, getters e setters.
- Relações entre classes: Associação, Agregação e Composição.
- Herança simples e múltipla, `super()`, Mixins e Polimorfismo.
- Métodos especiais / Dunder methods (`__init__`, `__str__`, `__repr__`, `__call__`, etc.).
- Gerenciamento de contexto customizado (`__enter__` e `__exit__`).
- `dataclasses` e `namedtuple` para estruturas de dados enxutas.

### 4. Módulos Nativos, Automação & Utilidades (Aulas 161 a 194)
- **Data e Hora**: `datetime`, `timezone`, `locale`, `calendar`.
- **Sistema e Arquivos**: `os`, `shutil`, `pathlib`, compactação e descompactação de arquivos `.zip`.
- **Formatos de Dados**: Serialização e desserialização com `json` e `csv`.
- **Templates e Envio de E-mails**: `string.Template` e integração com `smtplib` (HTML emails).
- **Variáveis de Ambiente**: Leitura com `os.environ` e `python-dotenv` (`.env`).
- **Web Scraping & Automação**:
  - Requisições HTTP com `requests` e parsing de HTML com `BeautifulSoup4`.
  - Automação de navegadores e bots com `Selenium WebDriver`.
- **Manipulação de Mídia e Documentos**:
  - Imagens com `Pillow` (redimensionamento e otimização).
  - PDFs com `PyPDF2` (mesclagem, divisão e rotação).
  - Planilhas Excel com `openpyxl`.
- **Processamento Concorrente**: `threading` e execução de processos com `subprocess`.

### 5. Interfaces Gráficas Desktop com PySide6 / Qt6 (Aulas 202 a 204)
- Criação de widgets, layouts e janelas principais (`QMainWindow`, `QWidget`, `QVBoxLayout`, `QGridLayout`).
- Gerenciamento de eventos, Signals & Slots.
- **Projeto Calculadora**: Arquitetura modular, display interativo, suporte a atalhos de teclado e personalização de tema visual (`qdarktheme`).
- Integração com **Qt Designer** e integração de threads com `QThread` / `Worker` para operações assíncronas em segundo plano sem congelar a interface.

### 6. Bancos de Dados com Python (Aulas 205 a 206)
- **SQLite3**: Operações completas de CRUD, cursores, transações (`commit`/`rollback`) e queries parametrizadas para prevenção de SQL Injection.
- **MySQL / MariaDB**:
  - Conexão e manipulação via biblioteca `PyMySQL` com cursores de dicionário (`DictCursor`).
  - Ambiente conteinerizado com `docker-compose.yml` para banco de dados local.

### 7. Desenvolvimento Web com Django (Aula 207)
- Estrutura de projeto Django (`manage.py`, `settings.py`, `urls.py`).
- Criação de aplicações (`apps`), mapeamento de URLs, views e templates dinâmicos.
- Arquitetura MVT (Model-View-Template).

---

## 🛠️ Como Configurar o Ambiente Local

### Pré-requisitos
- **Python 3.10+** instalado no sistema.
- **Git** instalado.

### 1. Clonar o repositório
```bash
git clone https://github.com/nilknarfsam/curso_python.git
cd curso_python
```

### 2. Criar e ativar o ambiente virtual (venv)
- **Windows (PowerShell)**:
  ```powershell
  python -m venv venv
  .\venv\Scripts\Activate.ps1
  ```
- **Linux / macOS**:
  ```bash
  python3 -m venv venv
  source venv/bin/activate
  ```

### 3. Instalar as dependências
```bash
pip install --upgrade pip
pip install -r requirements.txt
```

---

## 🚀 Como Executar as Aulas e Projetos

### Executar uma aula específica:
```bash
python aula1.py
```

### Executar o projeto da Calculadora PySide6:
```bash
python aula202-calculadora/main.py
```

### Subir o container de banco de dados MySQL (Aula 206):
```bash
cd aula206
docker compose up -d
python main.py
```

### Iniciar o servidor de desenvolvimento Django (Aula 207):
```bash
cd aula207_ola_django
python manage.py runserver
```

---

## 👤 Autor e Créditos

- **Estudante / Mantenedor**: [nilknarfsam](https://github.com/nilknarfsam)
- **Material de Referência**: Curso de Python 3 por Luiz Otávio Miranda (Udemy).
