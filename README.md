# 💳 JulianaCard - API de Análise de Crédito

Sistema web completo composto por uma interface de solicitação de cartão e uma API RESTful em Node.js para análise de crédito, validação de dados e registro de histórico.

## 🛠️ Tecnologias Utilizadas

* **Back-end:** Node.js, Express, CORS
* **Front-end:** HTML5, CSS3, JavaScript (Fetch API)

## 📌 Rotas da API (Endpoints)

* **`POST /api/analisar-credito`**
  Recebe `nome`, `cpf` e `renda` no corpo da requisição (JSON), valida os dados e retorna o status da proposta (`APROVADO` ou `RECUSADO`) junto com o limite liberado.
* **`GET /api/historico`**
  Retorna o total de análises realizadas e a lista completa de propostas processadas.

## ⚙️ Como executar o projeto localmente

1. Clone este repositório:
      `git clone https://github.com/Regiane-Dora/julianacard.git'

2. Acesse a pasta do projeto:
   `cd julianacard`
3. Instale as dependências:
   `npm install`
4. Inicie o servidor da API:
   `npm start`
5. Abra o arquivo `index.html` no seu navegador para testar o formulário.
