# 🧪 Testes manuais de API - ServeRest

Projeto de estudos em testes de API REST utilizando Postman e ServeRest.

O objetivo é praticar o envio de requisições, a análise das respostas da API e a validação do comportamento dos principais endpoints.

## 📌 Funcionalidades testadas

* Criação de usuário
* Autenticação de usuário
* Criação de produto
* Listagem de produtos
* Exclusão de produto

## 🛠️ Ferramentas utilizadas

* Postman
* ServeRest
* Git e GitHub

## 🔍 Validações realizadas

Durante os testes foram verificados:

* Método HTTP utilizado
* Endpoint da requisição
* Dados enviados no corpo da requisição
* Código de status retornado
* Conteúdo da resposta
* Comportamento apresentado pela API

## 📁 Estrutura do projeto

```text
api-testing-postman/
├── Postman/
│   └── Serverest.postman_collection.json
├── Prints/
│   ├── criar-produto.png
│   ├── deletar-produtos.png
│   └── listar-produtos.png
└── README.md
```

## ▶️ Como executar

1. Faça o download da collection disponível na pasta `Postman`.
2. Abra o Postman.
3. Clique em **Import**.
4. Selecione o arquivo `Serverest.postman_collection.json`.
5. Abra uma requisição da collection.
6. Clique em **Send**.
7. Analise o status e o conteúdo retornado pela API.

## 📸 Evidências

As evidências das execuções estão disponíveis na pasta `Prints`.

## 📚 Aprendizados

Este projeto permitiu praticar conceitos fundamentais de testes de API, como métodos HTTP, endpoints, corpo da requisição, códigos de status e análise das respostas retornadas.

## 🚧 Próximas evoluções

* Criação de cenários positivos e negativos
* Uso de variáveis de ambiente
* Inclusão de asserções no Postman
* Execução automatizada com Newman
* Integração com GitHub Actions

---

Projeto desenvolvido para fins de estudo e construção de portfólio em Quality Assurance.
