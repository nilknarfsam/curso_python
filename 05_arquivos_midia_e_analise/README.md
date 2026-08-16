# 📊 Módulo 05: Arquivos, Mídia, Análise de Dados & Concorrência

Neste módulo você aprenderá a trabalhar com formatos multimídia e ferramentas analíticas do ecossistema Python: **Jupyter Notebooks**, manipulação de arquivos **PDF** (`PyPDF2`), automação de **planilhas Excel** (`openpyxl`), processamento e redimensionamento de **imagens** (`Pillow`) e **programação concorrente com Threads** (`threading`).

---

## 🎯 Objetivos de Aprendizagem

- Utilizar **Jupyter Notebooks** (`.ipynb`) para experimentação interativa de código e visualização.
- Ler, extrair texto, mesclar, girar e dividir páginas de documentos **PDF**.
- Criar, formatar, preencher células e estilizar planilhas **Excel** (`.xlsx`) via código.
- Abrir, redimensionar mantendo proporção, converter formatos e otimizar imagens com **Pillow (PIL)**.
- Implementar **Threads** para executar múltiplas tarefas simultâneas em Python e gerenciar bloqueios (`Lock`).

---

## 🗺️ Mapa de Conteúdo e Aulas

| Arquivo / Pasta | Tema Principal | Descrição das Atividades |
| :--- | :--- | :--- |
| **`aula195.ipynb` & `aula195-2.ipynb`** | Jupyter Notebooks | Primeiros passos, atalhos, células de markdown e execução interativa |
| **`aula196.py`** | Análise e dados adicionais | Exemplos práticos complementares |
| **[aula197/](file:///d:/PROJETOS/curso_python/05_arquivos_midia_e_analise/aula197)** | Manipulação de PDFs | Leitura de PDF original, separação de páginas individuais e mesclagem em um único PDF (`MERGED.pdf`) |
| **`aula198.py`** | Utilitários | Scripts adicionais de automação |
| **[aula199/](file:///d:/PROJETOS/curso_python/05_arquivos_midia_e_analise/aula199)** | Planilhas Excel com `openpyxl` | `creating.py` (criação e escrita de planilhas) e `reading.py` (leitura, edição e fórmulas) |
| **[aula200/](file:///d:/PROJETOS/curso_python/05_arquivos_midia_e_analise/aula200)** | Processamento de Imagens | `main.py` com redimensionamento proporcional e compressão de imagens via Pillow |
| **[aula201/](file:///d:/PROJETOS/curso_python/05_arquivos_midia_e_analise/aula201)** | Multithreading & Concorrência | Scripts `aula0001.py` a `aula0006.py` cobrindo `Thread`, `args`, `join()`, estado compartilhado e `threading.Lock` |

---

## 🚀 Como Executar os Exemplos

```bash
# Executar a manipulação de PDFs
python 05_arquivos_midia_e_analise/aula197/main.py

# Criar uma planilha Excel automatizada
python 05_arquivos_midia_e_analise/aula199/creating.py

# Redimensionar imagens da pasta
python 05_arquivos_midia_e_analise/aula200/main.py

# Testar execução concorrente com Threads
python 05_arquivos_midia_e_analise/aula201/aula0001.py
```
