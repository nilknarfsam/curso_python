# 🐍 Curso de Python 3 — Do Básico ao Avançado

Repositório pessoal de estudos e projetos práticos cobrindo toda a trilha de aprendizado de **Python 3**, desde os fundamentos de sintaxe até tópicos avançados como Programação Orientada a Objetos (POO), Interfaces Gráficas (GUI) com PySide6, Bancos de Dados (SQLite e MySQL), Automação / Web Scraping e Desenvolvimento Web com Django.

---

## 📁 Estrutura Modular do Repositório

O projeto está organizado em **8 módulos temáticos** sequenciais. Cada módulo possui o seu próprio guia de estudo detalhado:

| Módulo | Pasta & Guia | Conteúdo e Foco de Estudo |
| :---: | :--- | :--- |
| **01** | [📖 `01_fundamentos_de_python/`](file:///d:/PROJETOS/curso_python/01_fundamentos_de_python/README.md) | Sintaxe básica, tipos primitivos (`str`, `int`, `float`, `bool`), condicionais `if/else`, loops `while`/`for`, listas e tuplas. |
| **02** | [📖 `02_programacao_procedural_e_funcoes/`](file:///d:/PROJETOS/curso_python/02_programacao_procedural_e_funcoes/README.md) | Funções (`*args`, `**kwargs`), Dicionários, Sets, Comprehensions, Decorators, Generators e manipulação de arquivos com `with`. |
| **03** | [📖 `03_programacao_orientada_a_objetos/`](file:///d:/PROJETOS/curso_python/03_programacao_orientada_a_objetos/README.md) | Classes, Herança, Polimorfismo, Encapsulamento, Dunder Methods, Dataclasses, Namedtuples e Context Managers. |
| **04** | [📖 `04_modulos_e_automacao/`](file:///d:/PROJETOS/curso_python/04_modulos_e_automacao/README.md) | Módulos `datetime`, `pathlib`, CSV, JSON, envio de e-mails SMTP, Web Scraping (BeautifulSoup4) e Automação (Selenium). |
| **05** | [📖 `05_arquivos_midia_e_analise/`](file:///d:/PROJETOS/curso_python/05_arquivos_midia_e_analise/README.md) | Jupyter Notebooks (.ipynb), manipulação de PDFs (`PyPDF2`), planilhas Excel (`openpyxl`), imagens (`Pillow`) e Threads. |
| **06** | [📖 `06_interfaces_graficas_pyside6/`](file:///d:/PROJETOS/curso_python/06_interfaces_graficas_pyside6/README.md) | Interfaces desktop com PySide6 / Qt6, projeto da Calculadora completa, Qt Designer e processamento com `QThread`. |
| **07** | [📖 `07_bancos_de_dados/`](file:///d:/PROJETOS/curso_python/07_bancos_de_dados/README.md) | Bancos de dados relacionais com Python: SQLite3 nativo e MySQL/MariaDB com `PyMySQL` e Docker Compose. |
| **08** | [📖 `08_desenvolvimento_web_django/`](file:///d:/PROJETOS/curso_python/08_desenvolvimento_web_django/README.md) | Introdução ao framework Django: padrão MVT (Model-View-Template), roteamento de URLs, views e templates dinâmicos. |

---

## 🛠️ Como Configurar o Ambiente de Desenvolvimento

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

## 🚀 Como Executar os Projetos e Aulas

### Executar uma aula de Fundamentos:
```bash
python 01_fundamentos_de_python/aula1.py
```

### Executar o Sistema Bancário em POO:
```bash
python 03_programacao_orientada_a_objetos/aula158/main.py
```

### Executar a Calculadora Desktop (PySide6):
```bash
python 06_interfaces_graficas_pyside6/aula202-calculadora/main.py
```

### Subir o container MySQL e executar scripts de banco:
```bash
cd 07_bancos_de_dados/aula206
docker compose up -d
python main.py
```

### Iniciar o servidor de desenvolvimento Django:
```bash
cd 08_desenvolvimento_web_django/aula207_ola_django
python manage.py migrate
python manage.py runserver
```

---

## 📜 Créditos e Referências

Este repositório foi criado e é mantido para fins de **estudo pessoal, prática e portfólio**. Todo o conteúdo e código-base foram desenvolvidos acompanhando o consagrado curso:

- 🎓 **Curso Oficial na Udemy**: [Curso de Python 3 do Básico ao Avançado - com projetos reais](https://www.udemy.com/course/python-3-do-zero-ao-avancado/)
- 👨‍🏫 **Instrutor / Autor**: **Luiz Otávio Miranda**
- 🐙 **GitHub do Instrutor**: [@luizomf](https://github.com/luizomf)
- 📦 **Repositório Original do Curso**: [luizomf/cursopython2023](https://github.com/luizomf/cursopython2023)
- 👤 **Estudante / Mantenedor deste fork**: [nilknarfsam](https://github.com/nilknarfsam)

> [!NOTE]
> Todos os direitos autorais e propriedade intelectual do material didático pertencem ao professor **Luiz Otávio Miranda**.
