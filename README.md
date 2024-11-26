
Uma API Flask para analisar currículos em PDF, com integração com MongoDB Atlas e OpenAI para fornecer análises baseadas em dados de FAQ e prompts personalizados.

## Funcionalidades

- **Upload de currículos**: Aceita arquivos PDF e analisa seu conteúdo.
- **Análise de currículos**: Classifica o currículo, fornece justificativas e sugere melhorias usando LangChain e OpenAI.
- **Gerenciamento de FAQs**: Permite adicionar e listar perguntas frequentes (FAQs) para enriquecer o contexto das análises.
- **Simulação de Chat**: Responde a mensagens simulando um chat baseado no conteúdo das FAQs.
- **Armazenamento em MongoDB**: Salva currículos processados e FAQs para consultas futuras.

## Tecnologias Utilizadas

- Python
- Flask
- LangChain
- OpenAI
- MongoDB Atlas
- pdfplumber
- dotenv

---

## Instalação

1. Clone este repositório:
   ```bash
   git clone https://github.com/mariagomeess/back-residencia.git
   cd residencia-main

2. Crie um ambiente virtual e instale as dependências:

python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt

---

## Como Executar

python app.py

Acesse a aplicação em: http://127.0.0.1:5000/
