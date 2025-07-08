Projeto Final - Engenharia de Prompt com Python + ChatGPT

Este projeto foi desenvolvido como trabalho final do curso de Engenharia de Prompt. Ele automatiza a criação de roadmaps personalizados de estudo, utilizando o poder da IA via API do OpenRouter (ChatGPT).

🚀 Tecnologias utilizadas
- Python 3.11
- Google Colab
- Pandas
- OpenAI SDK com OpenRouter API
- FPDF (para gerar PDF dos roadmaps)

📌 O que o projeto faz?
- Lê uma planilha (`.xlsx`) com colunas: área, tema e objetivo
- Gera um prompt para cada linha
- Envia para a API do ChatGPT (modelo Mixtral via OpenRouter)
- Retorna a resposta e:
  - Salva em `.txt`
  - Gera um `.pdf` com todos os roadmaps organizados

⚙️ Como usar
1. Clone o repositório
2. Substitua a chave de API pela sua:
   - Acesse https://openrouter.ai/
   - Gere uma chave de API gratuita
   - Cole no local indicado no notebook
3. Faça upload da sua planilha (`sheet_prompt_var.xlsx`)
4. Execute o notebook. O `.txt` será baixado automaticamente e o PDF ficará salvo no ambiente.


Lembre-se: Nunca compartilhe sua chave da OpenRouter publicamente.
developed by: Vitor Bonfim



