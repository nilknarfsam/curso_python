# 🐍 Curso de Python 3 — Do Básico ao Avançado

Repositório estruturado de estudos e projetos práticos cobrindo toda a trilha de aprendizado de **Python 3**, desde os fundamentos de sintaxe até tópicos avançados como Programação Orientada a Objetos (POO), Interfaces Gráficas (GUI) com PySide6, Bancos de Dados (SQLite e MySQL), Automação / Web Scraping e Desenvolvimento Web com Django.

---

## 📁 Estrutura Modular do Projeto

Todo o repositório está organizado em **8 módulos temáticos** sequenciais:

```
curso_python/
│
├── 01_fundamentos_de_python/             # Aulas 1 a 64
│   └── Tipos primitivos, if/else, while, for, listas, tuplas, f-strings
│
├── 02_programacao_procedural_e_funcoes/  # Aulas 65 a 119 + dados + aula99_package
│   └── Funções (*args, **kwargs), Dicionários, Sets, Comprehensions, Decorators, Generators, Arquivos txt/json
│
├── 03_programacao_orientada_a_objetos/   # Aulas 120 a 160 + aula141, aula156, aula158
│   └── Classes, Herança, Polimorfismo, Dunder Methods, Dataclasses, Namedtuples, Context Managers
│
├── 04_modulos_e_automacao/               # Aulas 161 a 194 + aula186_*, aula190_site, aula193
│   └── Datetime, Pathlib, CSV, JSON, E-mails SMTP, Web Scraping (BeautifulSoup4) e Automação (Selenium)
│
├── 05_arquivos_midia_e_analise/          # Aulas 195 a 201 + aula197 (PDF), aula199 (Excel), aula200 (Pillow), aula201 (Threads)
│   └── Jupyter Notebooks (.ipynb), manipulação de planilhas Excel, PDFs, imagens e programação concorrente
│
├── 06_interfaces_graficas_pyside6/       # Aulas 202 a 204
│   ├── aula202-calculadora/              # Aplicação completa de Calculadora com PySide6 e tema Dark
│   ├── aula203-qtdesigner/               # Integração e compilação de layouts do Qt Designer
│   └── aula204/                          # Processamento em segundo plano com QThread / Worker
│
├── 07_bancos_de_dados/                   # Aulas 205 e 206
│   ├── aula205/                          # SQLite3 com Python: CRUD completo, transações e segurança
│   └── aula206/                          # MySQL / MariaDB via PyMySQL e ambiente Docker Compose
│
├── 08_desenvolvimento_web_django/        # Aula 207
│   └── aula207_ola_django/               # Projeto Web Django: MVT, mapeamento de rotas e templates
│
├── .vscode/                              # Configurações padronizadas do ambiente de desenvolvimento
├── .gitignore                            # Arquivos e pastas ignorados no controle de versão
├── requirements.txt                      # Dependências completas do ecossistema
└── README.md                             # Documentação do repositório
```

---

## 📚 Trilha Detalhada de Aprendizado

### 1. 📂 `01_fundamentos_de_python/` (Aulas 1 a 64)
- **Tipos de dados**: `str`, `int`, `float`, `bool`, coerção de tipos e formatação de strings (`f-strings`, `.format()`).
- **Controle de Fluxo**: Condicionais (`if`, `elif`, `else`), operadores lógicos e de comparação.
- **Estruturas de Repetição**: `while` e `for` com `range`, `enumerate` e `zip`.
- **Coleções Básicas**: Listas (`list`), Tuplas (`tuple`), fatiamento e métodos utilitários.

### 2. 📂 `02_programacao_procedural_e_funcoes/` (Aulas 65 a 119)
- **Funções**: Argumentos posicionais e nomeados, `*args`, `**kwargs`, closures, funções de primeira classe e funções lambda.
- **Estruturas de Dados Avançadas**: Dicionários (`dict`) e Conjuntos (`set`).
- **Comprehensions**: List Comprehension, Dict Comprehension e Set Comprehension.
- **Funções Avançadas**: Decoradores (`@decorador`), funções geradoras (`yield`), iteradores e módulo `itertools` (`groupby`, `combinations`, `permutations`, `product`).
- **Persistência Básica**: Manipulação de arquivos com contexto `with` (formatos `.txt` e `.json`).
- **Modularização**: `import`, `from ... import`, criação de packages e `__init__.py`.

### 3. 📂 `03_programacao_orientada_a_objetos/` (Aulas 120 a 160)
- **POO Essencial**: Classes, atributos de classe e de instância, métodos de instância, `@classmethod` (factory methods) e `@staticmethod`.
- **Encapsulamento**: `@property`, getters e setters.
- **Relações entre Classes**: Associação, Agregação e Composição.
- **Herança**: Herança simples e múltipla, `super()`, Mixins e Polimorfismo.
- **Dunder Methods**: Métodos mágicos (`__init__`, `__str__`, `__repr__`, `__call__`, etc.).
- **Context Managers**: Criação com classes (`__enter__` e `__exit__`) e com `@contextmanager`.
- **Estruturas Modernas**: `dataclasses` e `namedtuple` para modelos de dados.

### 4. 📂 `04_modulos_e_automacao/` (Aulas 161 a 194)
- **Datas e Horários**: Módulos `datetime`, `timezone`, `locale` e `calendar`.
- **Sistema Operacional & Arquivos**: `os`, `shutil`, `pathlib`, compactação e descompactação de arquivos `.zip`.
- **Formatos de Dados**: Serialização e leitura de `.json` e `.csv`.
- **Comunicação**: Envio de e-mails formatados em HTML com `smtplib` e `string.Template`.
- **Configurações**: Variáveis de ambiente com `os.environ` e `python-dotenv` (`.env`).
- **Web Scraping**: Requisições HTTP com `requests` e parsing de HTML com `BeautifulSoup4`.
- **Automação Web**: Bots e navegação automatizada com `Selenium WebDriver`.
- **Processos**: Execução de comandos do sistema com `subprocess`.

### 5. 📂 `05_arquivos_midia_e_analise/` (Aulas 195 a 201)
- **Notebooks Interativos**: Jupyter Notebooks (`.ipynb`) para exploração de dados.
- **Manipulação de PDFs**: Leitura, divisão, mesclagem e rotação com `PyPDF2`.
- **Planilhas Excel**: Criação, estilização e leitura de planilhas `.xlsx` com `openpyxl`.
- **Processamento de Imagens**: Otimização e redimensionamento com `Pillow` (PIL).
- **Concorrência**: Threads com o módulo `threading`.

### 6. 📂 `06_interfaces_graficas_pyside6/` (Aulas 202 a 204)
- **Widgets e Janelas**: `QMainWindow`, `QWidget`, `QVBoxLayout`, `QGridLayout`.
- **Signals & Slots**: Comunicação reativa entre componentes visuais.
- **Projeto Calculadora**: Calculadora completa modular, suporte a atalhos de teclado e tema dark.
- **Qt Designer**: Criação visual de interfaces e compilação de arquivos `.ui` para código Python (`.py`).
- **Tarefas Assíncronas**: Uso de `QThread` / `Worker` para processamentos pesados em background.

### 7. 📂 `07_bancos_de_dados/` (Aulas 205 e 206)
- **SQLite3**: Criação de tabelas, CRUD completo, cursores, transações e segurança com queries parametrizadas.
- **MySQL / MariaDB**: Conexão com `PyMySQL`, cursores em dicionário (`DictCursor`) e provisionamento do banco via `docker-compose.yml`.

### 8. 📂 `08_desenvolvimento_web_django/` (Aula 207)
- **Arquitetura Django**: Estrutura com padrão MVT (Model-View-Template), `manage.py` e `settings.py`.
- **Rotas e Views**: Mapeamento de rotas de URLs e renderização de templates dinâmicos.

---

## 🛠️ Como Configurar o Ambiente Local

### Pré-requisitos
- **Python 3.10+** instalado.
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

## 🚀 Exemplos de Execução

### Executar uma aula de fundamentos:
```bash
python 01_fundamentos_de_python/aula1.py
```

### Executar uma aula de POO:
```bash
python 03_programacao_orientada_a_objetos/aula120.py
```

### Executar o projeto da Calculadora (PySide6):
```bash
python 06_interfaces_graficas_pyside6/aula202-calculadora/main.py
```

### Subir o container MySQL e executar o script de banco (Aula 206):
```bash
cd 07_bancos_de_dados/aula206
docker compose up -d
python main.py
```

### Iniciar o servidor de desenvolvimento Django (Aula 207):
```bash
cd 08_desenvolvimento_web_django/aula207_ola_django
python manage.py runserver
```

---

## 👤 Autor e Créditos

- **Estudante / Mantenedor**: [nilknarfsam](https://github.com/nilknarfsam)
- **Material de Referência**: Curso de Python 3 por Luiz Otávio Miranda (Udemy).
