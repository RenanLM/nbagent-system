# 🏀 NBAgent – Inteligência Artificial para Análise e Previsão de Jogadores da NBA

NBAgent é um projeto derivado da Imersão IA Alura + Google Gemini 2025, baseado em **agentes de IA**, utilizando a Google AI Development Kit (ADK) e o modelo **Gemini 2.0 Flash**, com o objetivo de **analisar estatísticas recentes de jogadores da NBA e gerar previsões realistas de desempenho**, levando em consideração fatores como lesões, classificação nos playoffs e eliminação.

---

## 🎯 Objetivo

> Criar uma cadeia de agentes que simule o trabalho de um olheiro ou analista profissional da NBA, com foco em:
- Buscar dados atualizados de um jogador
- Analisar tendências de desempenho
- Gerar previsões realistas (apenas se aplicável)
- Validar a coerência das previsões

---

## 🧠 Como funciona?

O sistema é composto por 4 agentes interligados:

1. **Agente Coletor de Dados**: pesquisa estatísticas recentes do jogador.
2. **Agente Analista Estatístico**: interpreta os dados e identifica tendências.
3. **Agente Previsor**: gera uma previsão de desempenho (se aplicável).
4. **Agente Validador**: avalia a coerência e consistência da previsão gerada.

⚠️ Caso o jogador esteja lesionado, eliminado dos playoffs ou não esteja mais participando da temporada, **não são feitas previsões futuras**, apenas análises com os dados disponíveis.

---

## 🚀 Como usar

Você pode executar o projeto diretamente no Google Colab:

[🔗 Acesse o notebook no Google Colab](https://colab.research.google.com/drive/1bMUCEKgzPp0nmXYLGIYgOfSz-K3cgJKW?authuser=2#scrollTo=1HXCX9GegLpy)

> **Requisitos:**
> - Uma conta Google com acesso à API do [Google AI Studio](https://makersuite.google.com/)
> - A variável de ambiente `GOOGLE_API_KEY` configurada no Colab com `userdata`

---

## 🛠 Tecnologias Utilizadas

- [Google GenAI](https://ai.google.dev/)
- [Google AI Development Kit (ADK)](https://ai.google.dev/gemini-api/docs/tools/adk)
- Gemini 2.0 Flash
- Google Search Tool
- Python 3 (via Google Colab)

---

## 🧩 Estrutura do Projeto

```bash
📁 nbagent-system/
│
├── 🧠 NBAgent.ipynb
├── README.md

