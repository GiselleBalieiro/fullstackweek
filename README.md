# Totem de Pedidos - McDonald's (Simulação)

Este projeto é uma simulação de um **totem de pedidos** inspirado no modelo utilizado no **McDonald's** para pedidos no restaurante. O sistema foi desenvolvido utilizando **React**, **TypeScript**, **PostgreSQL**, **Prisma ORM**, **Tailwind CSS** e **Stripe** para processar os pagamentos, em conjunto com um curso de 14 horas de carga horária.

## Tecnologias Usadas

- **React**: Biblioteca para construção de interfaces de usuário interativas e reativas.
- **TypeScript**: Superset do JavaScript que adiciona tipagem estática ao código.
- **PostgreSQL**: Banco de dados relacional de código aberto.
- **Prisma ORM**: Ferramenta para interagir com bancos de dados de forma eficiente e segura.
- **Tailwind CSS**: Framework de CSS para estilização utilitária e responsiva.
- **Stripe**: API de pagamento para realizar transações financeiras de forma segura.

## Funcionalidades

- O sistema permite aos usuários visualizar o cardápio, adicionar produtos ao carrinho e finalizar o pedido.
- Ao finalizar o pedido, o usuário pode verificar o resumo da compra e o total.
- O pagamento é processado de forma segura utilizando a **Stripe**.
- A aplicação também permite a consulta de pedidos anteriores com base no CPF do cliente.

## Como Executar o Projeto  

1. Clone o repositório:  
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   
2. Acesse o diretório do projeto:
   cd seu-repositorio

3. Instale as dependências do projeto:
   npm install

4. Configure o banco de dados: 
   Certifique-se de que você tenha o PostgreSQL instalado e configurado. Crie um banco de dados e configure as variáveis de ambiente para a conexão com o banco de dados.

5. Configure a API do Stripe:
   STRIPE_SECRET_KEY="your_stripe_secret_key"

6. Rode as migrações com Prisma:
   npx prisma migrate dev

7. Inicie o servidor:
   npm run dev
