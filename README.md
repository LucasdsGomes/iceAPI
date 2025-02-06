🍦 Sorveteria API

 

📌 Descrição

A Sorveteria API é uma aplicação desenvolvida em Ruby on Rails que funciona como um CRUD para gerenciar produtos de uma sorveteria, incluindo sabores, categorias e pedidos. A API permite que os clientes consultem os produtos disponíveis, realizem pedidos e os administradores gerenciem os dados da sorveteria.

🚀 Funcionalidades

✅ Gerenciamento de Produtos: Criar, listar, atualizar e excluir produtos do cardápio.

✅ Gerenciamento de Sabores: Adicionar, editar e remover sabores de sorvete.

✅ Gerenciamento de Categorias: Organizar produtos em categorias como sorvetes, picolés e milkshakes.

✅ Sistema de Pedidos: Criar, listar e atualizar status de pedidos dos clientes.

🛠 Tecnologias Utilizadas

Backend: Ruby on Rails

Banco de Dados: PostgreSQL

Autenticação: Devise (se aplicável)

Serialização: ActiveModel::Serializers

Testes: RSpec (opcional)

📦 Instalação e Execução

🔧 Requisitos

Certifique-se de ter instalado:

Ruby 3.x

Rails 7.x

PostgreSQL

Bundler

📜 Passos para Executar

# Clone o repositório
git clone https://github.com/seu-usuario/sorveteria-api.git
cd sorveteria-api

# Instale as dependências
bundle install

# Configure o banco de dados
rails db:create db:migrate db:seed

# Inicie o servidor
rails s

A API estará rodando em http://localhost:3000.

📌 Endpoints

🛒 Produtos

GET /produtos  # Lista todos os produtos
POST /produtos  # Cria um novo produto
GET /produtos/:id  # Detalha um produto específico
PUT /produtos/:id  # Atualiza um produto
DELETE /produtos/:id  # Remove um produto

🍨 Sabores

GET /sabores  # Lista todos os sabores
POST /sabores  # Adiciona um novo sabor
PUT /sabores/:id  # Atualiza um sabor
DELETE /sabores/:id  # Remove um sabor

📦 Pedidos

GET /pedidos  # Lista todos os pedidos
POST /pedidos  # Cria um novo pedido
PUT /pedidos/:id  # Atualiza o status de um pedido

📸 Prints do Frontend

![image](https://github.com/user-attachments/assets/adfad138-610f-408e-8cd8-bd466ea0eace)


🤝 Contribuição

Se deseja contribuir com melhorias, siga os seguintes passos:
