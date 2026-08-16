# 🌐 Módulo 08: Desenvolvimento Web com Django

**Django** é o framework web mais popular, robusto e completo do ecossistema Python. Neste módulo introdutório você conhecerá a estrutura de projetos Django, o padrão **MVT (Model-View-Template)**, criação de rotas, views e templates HTML dinâmicos.

---

## 🎯 Objetivos de Aprendizagem

- Entender o fluxo de requisição e resposta HTTP no Django.
- Compreender o padrão **MVT** (Model, View, Template).
- Operar o utilitário CLI `manage.py` (`runserver`, `makemigrations`, `migrate`, `createsuperuser`).
- Estruturar projetos modulares divididos em aplicações (`apps` como `home` e `blog`).
- Configurar rotas (`urls.py`) globais e específicas de cada app com `include()`.
- Criar views baseadas em funções e renderizar templates HTML (`render()`).
- Utilizar a linguagem de templates do Django (DTL) com herança de layout (`{% extends %}`, `{% block %}`, `{% include %}`).
- Servir arquivos estáticos (CSS, imagens, JavaScript).

---

## 🗺️ Estrutura da Aplicação [aula207_ola_django/](file:///d:/PROJETOS/curso_python/08_desenvolvimento_web_django/aula207_ola_django)

```
aula207_ola_django/
├── project/                # Configurações globais do projeto (settings.py, urls.py, wsgi.py)
├── home/                   # App da página inicial (views, urls, templates/home/)
├── blog/                   # App de blog com rotas dinâmicas e listagem de posts
├── base/                   # Templates base globais (base.html, partials) e arquivos estáticos (CSS)
└── manage.py               # Utilitário de linha de comando do Django
```

---

## 🚀 Como Executar

Abra o terminal e execute os comandos:

```bash
# 1. Navegar até a pasta do projeto Django
cd 08_desenvolvimento_web_django/aula207_ola_django

# 2. Executar as migrações iniciais do banco SQLite embutido
python manage.py migrate

# 3. Iniciar o servidor de desenvolvimento
python manage.py runserver
```

Após iniciar o servidor, acesse no seu navegador:
- 🏠 **Home**: `http://127.0.0.1:8000/`
- 📰 **Blog**: `http://127.0.0.1:8000/blog/`
- 📑 **Exemplo de Post**: `http://127.0.0.1:8000/blog/exemplo/`
