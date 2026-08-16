# 🖥️ Módulo 06: Interfaces Gráficas Desktop com PySide6 (Qt6)

Neste módulo você aprenderá a construir aplicações visuais desktop modernas e profissionais para Windows, Linux e macOS utilizando **PySide6** (o binding oficial do framework **Qt6** para Python).

---

## 🎯 Objetivos de Aprendizagem

- Compreender a arquitetura de aplicações Qt (`QApplication`, `QMainWindow`, `QWidget`).
- Construir layouts responsivos com `QVBoxLayout`, `QHBoxLayout` e `QGridLayout`.
- Dominar o padrão **Signals and Slots** para reagir a cliques, teclas e eventos do usuário.
- Estilizar interfaces com folhas de estilo personalizadas (QSS) e temas modernos (`pyqtdarktheme`).
- Integrar interfaces desenhadas visualmente no **Qt Designer** convertendo arquivos `.ui` para Python (`pyside6-uic`).
- Executar processamento assíncrono e tarefas pesadas em segundo plano sem congelar a interface usando **`QThread`** e objetos **`Worker`**.

---

## 🗺️ Projetos e Pastas Inclusas

### 1. 🧮 [aula202-calculadora/](file:///d:/PROJETOS/curso_python/06_interfaces_graficas_pyside6/aula202-calculadora)
Projeto completo de uma calculadora moderna:
- `main.py`: Ponto de entrada da aplicação e inicialização da janela.
- `main_window.py`: Configuração da `QMainWindow` e layout principal.
- `display.py`: Display numérico customizado com captura de teclas e foco.
- `info.py`: Label de histórico/expressão matemática superior.
- `buttons.py`: Grade de botões, lógica de operadores, tratamento de divisões por zero e cálculos com `eval`.
- `styles.py` & `variables.py`: Cores, fontes e aplicação de tema escuro (`qdarktheme`).

### 2. 🎨 [aula203-qtdesigner/](file:///d:/PROJETOS/curso_python/06_interfaces_graficas_pyside6/aula203-qtdesigner)
- `ui/window.ui`: Arquivo XML de layout criado no Qt Designer.
- `ui/ui_window.py`: Arquivo Python gerado pelo compilador `pyside6-uic`.
- `src/main_window.py` & `src/window.py`: Herança e conexão de sinais na classe principal.

### 3. 🧵 [aula204/](file:///d:/PROJETOS/curso_python/06_interfaces_graficas_pyside6/aula204)
- Demonstração de uso de `QThread`, `Signal` e `Slot` para manter a UI 100% responsiva durante tarefas demoradas.

---

## 🚀 Como Executar

```bash
# Executar a Calculadora PySide6
python 06_interfaces_graficas_pyside6/aula202-calculadora/main.py

# Executar o projeto com Qt Designer
python 06_interfaces_graficas_pyside6/aula203-qtdesigner/src/main_window.py

# Executar a aplicação com QThread
python 06_interfaces_graficas_pyside6/aula204/main.py
```
