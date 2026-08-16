# 🏛️ Módulo 03: Programação Orientada a Objetos (POO)

A Programação Orientada a Objetos é um dos pilares do desenvolvimento profissional em Python. Neste módulo você aprenderá a modelar o mundo real em código utilizando **Classes**, **Herança**, **Polimorfismo**, **Encapsulamento**, **Dunder Methods** e **Dataclasses**.

---

## 🎯 Objetivos de Aprendizagem

- Compreender a diferença entre Classe (molde) e Objeto/Instância.
- Utilizar o inicializador `__init__` e a palavra-chave `self`.
- Distinguir métodos de instância, métodos de classe (`@classmethod`) e métodos estáticos (`@staticmethod`).
- Aplicar encapsulamento com `@property`, getters, setters e atributos protegidos (`_`) e privados (`__`).
- Modelar relações entre classes: **Associação**, **Agregação** e **Composição**.
- Implementar **Herança Simples**, **Herança Múltipla**, `super()` e classes **Mixins**.
- Sobrescrever métodos mágicos / Dunder methods (`__str__`, `__repr__`, `__call__`, `__len__`, `__add__`).
- Criar Gerenciadores de Contexto personalizados (`__enter__` e `__exit__`).
- Simplificar modelos de dados com `@dataclass` e `namedtuple`.

---

## 🗺️ Mapa de Conteúdo e Aulas

| Faixa de Aulas | Tópicos Principais | Conceitos Chave |
| :--- | :--- | :--- |
| **Aulas 120 a 129** | Classes básicas, instâncias e escopo | `class`, `self`, `__init__`, atributos de classe vs de instância, `__dict__`, `vars()`, serialização de classes em JSON (`aula127_a.py` e `aula127_b.py`) |
| **Aulas 130 a 135** | Métodos especiais e Encapsulamento | `@classmethod`, `@staticmethod`, `@property`, setters, deleters, convenção de atributos privados |
| **Aulas 136 a 140** | Relações entre objetos | Associação (um usa outro), Agregação (um precisa do outro para existir), Composição (um é dono do ciclo de vida do outro) |
| **Aulas 141 a 148** | Herança, Polimorfismo e Mixins | Herança simples e múltipla, MRO (Method Resolution Order), classes abstratas (`abc.ABC`, `@abstractmethod`), polimorfismo |
| **Aulas 149 a 155** | Dunder Methods e Context Managers | `__enter__`, `__exit__`, `contextlib.contextmanager`, `__new__`, `__call__`, tratamento de exceções customizadas |
| **Aulas 156 a 160** | Documentação, Dataclasses & Exemplo Bancário | Docstrings (`aula156/`), sistema bancário completo (`aula158/`), `@dataclass`, `field`, `asdict`, `astuple`, `namedtuple` |

---

## 🏗️ Projetos e Exemplos Práticos Inclusos

- 📝 **[aula141/](file:///d:/PROJETOS/curso_python/03_programacao_orientada_a_objetos/aula141)**: Sistema de log em arquivo e terminal com arquitetura de Mixins e Herança.
- 📚 **[aula156/](file:///d:/PROJETOS/curso_python/03_programacao_orientada_a_objetos/aula156)**: Boas práticas de documentação (docstrings de módulo, classes e funções).
- 🏦 **[aula158/](file:///d:/PROJETOS/curso_python/03_programacao_orientada_a_objetos/aula158)**: Sistema bancário completo com Contas (Corrente/Poupança), Clientes e Banco aplicando todos os pilares da POO.

---

## 🚀 Como Executar

```bash
# Executar a aula de introdução a classes
python 03_programacao_orientada_a_objetos/aula120.py

# Executar o projeto prático do Sistema Bancário
python 03_programacao_orientada_a_objetos/aula158/main.py
```
