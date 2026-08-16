# ⚙️ Módulo 02: Programação Procedural, Funções & Estruturas Avançadas

Neste módulo você avança para o nível intermediário de Python, dominando **funções**, estruturas de dados associativas (**dicionários** e **sets**), programação funcional, **comprehensions**, **decoradores**, **geradores** e **manipulação de arquivos**.

---

## 🎯 Objetivos de Aprendizagem

- Criar funções robustas utilizando parâmetros posicionais, nomeados, valores padrão, `*args` e `**kwargs`.
- Compreender escopo de variáveis, closures e funções de primeira classe.
- Manipular estruturas de dados complexas: Dicionários (`dict`) e Conjuntos (`set`).
- Escrever código idiomático e expressivo com List, Dictionary e Set Comprehensions.
- Criar Decoradores de funções para reutilização e injeção de comportamento.
- Dominar Geradores (`yield`), Iteradores e o módulo `itertools`.
- Manipular arquivos de texto (`.txt`) e formato estruturado (`.json`) de forma segura com Context Managers (`with`).

---

## 🗺️ Mapa de Conteúdo e Aulas

| Faixa de Aulas | Tópicos Principais | Conceitos Chave |
| :--- | :--- | :--- |
| **Aulas 65 a 76** | Definição de funções e argumentos | `def`, retorno (`return`), `*args`, `**kwargs`, escopo global e local, funções como argumentos |
| **Aulas 77 a 83** | Dicionários e Manipulação de Chaves | Criação de `dict`, métodos `get()`, `keys()`, `values()`, `items()`, `update()`, cópia rasa vs profunda (`deepcopy`) |
| **Aulas 84 a 89** | Conjuntos (Sets) e Funções Lambda | Operações de conjuntos (união `\|`, interseção `&`, diferença `-`), lambdas, ordenação |
| **Aulas 90 a 96** | Comprehensions e Tratamento de Erros | List Comprehension com filtros, Dictionary Comprehension, `isinstance`, `try / except / finally / raise` |
| **Aulas 97 a 100** | Módulos, Packages e Recarregamento | `import`, `aula97_m.py`, `aula98_m.py`, `importlib.reload`, pacotes com `__init__.py`, módulo `dados/` |
| **Aulas 101 a 115** | Decorators, Generators e `itertools` | Closures, `@decorador`, geradores (`yield`), `combinations`, `permutations`, `product`, `groupby`, `map`, `filter`, `reduce` |
| **Aulas 116 a 119** | Persistência de Arquivos e JSON | `open()`, modos `w`, `r`, `a+`, `encoding='utf8'`, `json.dump()`, `json.load()`, projeto de lista de tarefas |

---

## 📝 Passo a Passo Recomendado para Estudos

1. **Passo 1 — Funções e Escopo**:
   Estude `aula65.py` até `aula76.py` para entender como dividir problemas em funções pequenas e reutilizáveis.
2. **Passo 2 — Dicionários e Sets**:
   Pratique os métodos de manipulação de dicionários e operações de conjuntos (`aula77.py` a `aula89.py`).
3. **Passo 3 — Comprehensions e Python Moderno**:
   Aprenda a transformar loops tradicionais em list e dict comprehensions elegantes (`aula90.py` a `aula96.py`).
4. **Passo 4 — Decoradores e Geradores**:
   Entenda o funcionamento de closures e decoradores (`aula101.py` a `aula115.py`), fundamentais para frameworks como Flask, FastAPI e Django.
5. **Passo 5 — Manipulação de Arquivos e JSON**:
   Veja como ler, salvar e manipular arquivos no disco (`aula116.py` a `aula119.py`).

---

## 🚀 Como Executar

```bash
# Executar a aula sobre Decoradores
python 02_programacao_procedural_e_funcoes/aula104.py

# Executar a aula sobre JSON e persistência
python 02_programacao_procedural_e_funcoes/aula117.py
```
