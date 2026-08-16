# ⚡ Módulo 04: Módulos Nativos, Automação & Web Scraping

Python é mundialmente famoso por vir com "baterias inclusas". Neste módulo você explorará a biblioteca padrão do Python e ferramentas de ponta para **automação de tarefas**, **leitura de dados tabulares e JSON**, **envio de e-mails**, **manipulação do sistema de arquivos**, **Web Scraping** com BeautifulSoup e **Automação Web** com Selenium.

---

## 🎯 Objetivos de Aprendizagem

- Manipular datas, fusos horários, cálculos de prazos e internacionalização (`datetime`, `zoneinfo`, `calendar`, `locale`).
- Navegar, criar, copiar, mover e apagar arquivos e pastas com `os`, `shutil` e `pathlib.Path`.
- Compactar e descompactar arquivos `.zip` via script (`zipfile`).
- Ler e escrever arquivos de intercâmbio de dados: `.csv` e `.json`.
- Enviar e-mails transacionais e de marketing com templates dinâmicos em HTML (`smtplib` + `string.Template`).
- Proteger senhas e chaves de API com variáveis de ambiente (`os.environ`, `.env`, `python-dotenv`).
- Realizar Web Scraping seguro e eficiente (`requests` + `BeautifulSoup4`).
- Automatizar navegadores e interagir com formulários e botões usando **Selenium WebDriver**.
- Executar e monitorar comandos do sistema operacional com `subprocess`.

---

## 🗺️ Mapa de Conteúdo e Aulas

| Faixa de Aulas | Tópicos Principais | Conceitos Chave |
| :--- | :--- | :--- |
| **Aulas 161 a 167** | Datas, Horários e Prazos | `datetime.datetime`, `timedelta`, `dateutil.relativedelta`, formatação `strftime`, `strptime`, `calendar.monthcalendar`, `locale.setlocale` |
| **Aulas 168 a 174** | Sistema de Arquivos & `pathlib` | `os.listdir`, `os.walk`, `os.path.getsize`, `pathlib.Path`, `shutil.copy`, `shutil.rmtree` |
| **Aulas 175 a 180** | JSON, CSV e Dados Tabulares | `json.dumps`, `json.loads`, `csv.reader`, `csv.DictReader`, `csv.writer`, `csv.DictWriter` |
| **Aulas 181 a 185** | Aleatoriedade, E-mails e Variáveis de Ambiente | `random.choice`, `secrets.token_hex`, `os.environ`, `dotenv_values`, envio de e-mails com `smtplib` e `MIMEText`, templates HTML (`string.Template`) |
| **Aulas 186 a 188** | Compactação ZIP e Argumentos de Linha de Comando | Módulo `zipfile`, `sys.argv`, `argparse.ArgumentParser` |
| **Aulas 189 a 192** | HTTP e Web Scraping | Protocolo HTTP (GET, POST, Status Codes), `requests.get`, seletores CSS com `BeautifulSoup` (`bs4`), extração de links e textos (`aula190_site/`) |
| **Aulas 193 e 194** | Automação com Selenium & Subprocessos | `selenium.webdriver`, esperas explícitas (`WebDriverWait`), `By.XPATH`, `subprocess.run`, captura de saída do terminal |

---

## 🛠️ Como Executar os Exemplos

```bash
# Executar aula sobre manipulação de datas
python 04_modulos_e_automacao/aula162.py

# Executar exemplo de Web Scraping com BeautifulSoup
python 04_modulos_e_automacao/aula192.py

# Executar automação de navegador com Selenium
python 04_modulos_e_automacao/aula193/main.py
```
