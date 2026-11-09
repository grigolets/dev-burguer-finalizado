# 🍔 DevBurger
Aplicação web completa para uma hamburgueria, com experiência pensada tanto para o cliente quanto para quem gerencia a loja.
O cliente pode navegar pelo cardápio, montar seu pedido e pagar online. O administrador acompanha todos os pedidos em tempo real, gerencia produtos e categorias e atualiza o status de cada pedido.
Projeto desenvolvido durante o curso DevClub, com foco em criar uma aplicação real, do back-end ao front-end.
## O que o projeto faz
**Para o cliente:**
- Criar conta e fazer login de forma segura
- Explorar o cardápio organizado por categorias
- Adicionar produtos ao carrinho e finalizar o pedido
- Pagar de forma integrada com o Stripe
**Para o administrador:**
- Visualizar todos os pedidos em uma tabela expansível, com detalhes dos produtos
- Filtrar pedidos por status: Pedido Realizado, Em Preparação, Pronto, Entrega a caminho e Entregue
- Cadastrar, editar e organizar produtos e categorias
- Atualizar o status do pedido conforme ele avança na cozinha e na entrega
## Tecnologias utilizadas
**Front-end:**
- React para construir a interface
- Vite para um ambiente de desenvolvimento rápido
- Material-UI para os componentes da tabela de pedidos
- Styled-components para a estilização
- Axios para a comunicação com a API
**Back-end:**
- Node.js com Express para a criação da API
- PostgreSQL para armazenar usuários, produtos e categorias
- MongoDB para armazenar os pedidos, que precisam de mais flexibilidade
- Sequelize e Mongoose para a conexão com os bancos de dados
- JWT para autenticação e segurança das rotas
- Multer para o upload de imagens dos produtos
- Stripe para o processamento dos pagamentos
**Ferramentas:**
- Beekeeper Studio para visualizar o PostgreSQL
- MongoDB Compass para visualizar o MongoDB
## Autor
**Giovanni Bruno Grigolete**
