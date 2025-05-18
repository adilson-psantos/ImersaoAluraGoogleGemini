# ImersaoAluraGoogleGemini
# Resumo do código para GitHub

## Chatbot de Apoio Emocional com Troca Sutil de Agentes (Google Gemini)

Este projeto implementa um chatbot de apoio emocional utilizando a API do Google Gemini, com a funcionalidade de trocar sutilmente entre diferentes agentes sem que o usuário perceba uma mudança abrupta de personalidade.

### Funcionalidades:

* **Múltiplos Agentes:** Quatro agentes com características distintas (Maria - Calma, Carlos - Motivador, Sofia - Recursos, Lucas - Empático).
* **Seleção Inteligente de Agente:** A escolha do agente é feita dinamicamente com base nas palavras-chave da mensagem do usuário, com uma lógica que prioriza a sutileza na transição.
* **Troca Sutil de Agente:** A mudança de agente ocorre apenas se a nova escolha de palavras-chave for significativamente mais forte do que o agente atual, evitando trocas repentinas. Uma mensagem discreta informa ao usuário sobre o ajuste na forma de ajuda.
* **Histórico da Conversa:** Mantém um histórico individual da conversa para cada agente, permitindo respostas mais contextuais.
* **Encerramento Amigável:** Permite que o usuário encerre a conversa com palavras-chave específicas.

### Tecnologias Utilizadas:

* **Python:** Linguagem de programação principal.
* **google-generativeai:** Biblioteca Python para interagir com os modelos Gemini do Google.
* **Google Colab Userdata:** Utilizado para gerenciar de forma segura a chave da API do Google Gemini (ideal para execução no Google Colab).

### Como Usar:

1.  **Configure a Chave da API do Google Gemini:** Utilize o `google.colab.userdata.get('GOOGLE_API_KEY')` para fornecer sua chave da API de forma segura no Google Colab.
2.  **Execute o Código:** Execute as células do código em um notebook do Google Colab.
3.  **Interaja com o Chatbot:** Responda às perguntas do chatbot e observe como ele adapta sutilmente a forma de ajuda com base no conteúdo da conversa.

Este código busca proporcionar uma experiência de conversação mais fluida e natural, onde a mudança de "ajudante" ocorre de maneira discreta, focando nas necessidades do usuário ao longo da interação.
