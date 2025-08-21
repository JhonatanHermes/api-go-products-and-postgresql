Portfólio: API de Gerenciamento de Produtos em Go

Um projeto de API REST desenvolvido em Go, com integração ao PostgreSQL usando Docker, que permite criar, listar, atualizar e deletar produtos de forma simples e eficiente.

🚀 Tecnologias Utilizadas

Go (Golang) – linguagem principal da API

PostgreSQL – banco de dados relacional

Docker & Docker Compose – containerização e facilitação do ambiente

DBeaver / Postman / Insomnia – ferramentas auxiliares para visualização e testes

🏗 Estrutura do Projeto
go-api/
│── cmd/
│   └── main.go              # Ponto de entrada da aplicação
│
│── controller/
│   └── product_controller.go # Endpoints da API
│
│── db/
│   └── conn.go              # Conexão com o banco de dados
│
│── model/
│   ├── product.go           # Estrutura do produto
│   └── response.go          # Estruturas de resposta da API
│
│── repository/
│   └── product_repository.go # Regras de acesso ao banco
│
│── usecase/
│   └── product_usecase.go   # Regras de negócio
│
│── Dockerfile               # Build da API em Go
│── docker-compose.yml       # Configuração do banco de dados
│── go.mod / go.sum          # Dependências do Go
