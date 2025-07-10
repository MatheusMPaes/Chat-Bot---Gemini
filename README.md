# Google Gemini Chatbot

Este projeto é um chatbot interativo que utiliza o modelo **Gemini 2.0 Flash** da plataforma **Google AI Studio**.  
Ele permite que você envie prompts em tempo real e receba respostas do modelo, com tratamento automático de falhas como sobrecarga do servidor.

---

## Funcionalidades

- Integração com a API do Google Gemini
- Seleção de modelo (`gemini-2.0-flash`)
- Loop interativo para envio de prompts
- Reenvio automático em caso de erro 500 (servidor sobrecarregado)
- Exibição do histórico de conversas (opcional)
- Pronto para rodar tanto no **Google Colab** quanto **localmente**

---

## Requisitos

- Python 3.8 ou superior
- Conta no [Google AI Studio](https://aistudio.google.com/)
- Chave de API ativa
- Conexão com a internet

---

## Como obter sua API Key

1. Acesse: [https://aistudio.google.com/apikey](https://aistudio.google.com/apikey)
2. Clique em **“Create API key”**
3. Copie a chave gerada
4. Use-a no seu ambiente:
   - No Google Colab: via `userdata.get()`
   - Localmente: via `.env` ou `os.environ`

---
