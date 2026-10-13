# 🎙️ AudioMinute

## Gerador de Atas e Tarefas a partir de Reuniões

O **AudioMinute** é um protótipo baseado em Inteligência Artificial que transforma gravações de reuniões em atas organizadas e planos de ação.

### 🎯 Objetivo

Demonstrar como a Inteligência Artificial pode ser utilizada para aumentar a produtividade no ambiente corporativo, automatizando a criação de atas e a identificação de tarefas.

### ⚙️ Funcionamento

1. O usuário envia uma gravação da reunião.
2. O áudio é convertido em texto usando o modelo de transcrição da OpenAI.
3. A Inteligência Artificial analisa a transcrição.
4. O sistema identifica título, data, resumo, tópicos, decisões, responsáveis, tarefas e prazos.
5. A ata pode ser exportada para TXT ou DOCX.

### 🧠 Tecnologias

- Python
- Streamlit
- OpenAI API
- Whisper
- Modelo de linguagem
- Engenharia de prompts
- python-docx

### 📁 Estrutura

```text
AudioMinute/
├── app.py
├── requirements.txt
├── README.md
└── .gitignore
```

### 🚀 Execução local

Instale as dependências:

```bash
pip install -r requirements.txt
```

Configure sua chave da OpenAI.

Windows PowerShell:

```powershell
$env:OPENAI_API_KEY="SUA_CHAVE"
```

Depois:

```bash
streamlit run app.py
```

### ☁️ Streamlit Cloud

1. Crie um repositório no GitHub.
2. Envie os arquivos deste projeto.
3. No Streamlit Cloud, crie uma nova aplicação.
4. Selecione o repositório e `app.py`.
5. Em **Settings → Secrets**, adicione:

```toml
OPENAI_API_KEY = "SUA_CHAVE"
```

6. Publique a aplicação.

### 🔐 Segurança

Nunca coloque sua chave da OpenAI diretamente no `app.py` ou em um repositório público. Use o recurso Secrets do Streamlit Cloud.

### 👩‍💻 Projeto

**Nome:** AudioMinute  
**Área:** Produtividade Corporativa / Áudio, Transcrição e Inteligência Artificial  
**Líder:** Ayila Melissa
