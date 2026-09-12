# Paulo AI

Chatbot com IA generativa, busca em tempo real e captacao de leads, construido com Streamlit.

## O que faz

- Atendimento conversacional especializado por nicho de negocio (5 nichos + diagnostico automatico)
- Busca em tempo real via Tavily API para respostas com contexto atualizado
- IA generativa com Google Gemini (google-generativeai)
- Score automatico de leads (1-10) registrado direto em Google Sheets via gspread
- Painel administrativo com filtros para acompanhar os leads capturados

## Stack

- Python, Streamlit
- Google Generative AI (Gemini)
- Tavily API (busca web)
- Google Sheets API (gspread + service account)
- streamlit-autorefresh para manter a sessao ativa

## Deploy

Em producao: https://paulo-ai.streamlit.app

## Estrutura

Codigo principal em agente-ia/ (main.py, tools.py, auxiliar.py).

