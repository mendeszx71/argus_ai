# ARGUS Complete

Assistente local estilo Claude/ChatGPT, com identidade própria.

## Recursos
- Chat persistente em SQLite
- Streaming de respostas
- Histórico de conversas
- Markdown + blocos de código
- Upload de TXT, MD, CSV, JSON e arquivos de código/texto
- Modo Ask
- Modo Agent com planner multiagente
- Researcher / Coder / Data / Critic
- Ollama local
- API FastAPI
- Interface web responsiva dark/light
- Painel de atividade do agente
- Exportação de conversa

## Instalação

1. Instale Ollama: https://ollama.com
2. `ollama pull llama3.2`
3. `python -m venv .venv`
4. Windows: `.venv\Scripts\Activate.ps1`
5. `pip install -r requirements.txt`
6. Copie `.env.example` para `.env`
7. `python -m uvicorn app.main:app --reload`
8. Abra http://127.0.0.1:8000

O projeto usa apenas o modelo local por padrão.
