## Sobre o Projeto

Este é um backend para uma API de e-commerce desenvolvida com Python e Flask. Ele gerencia autenticação de usuários, produtos e carrinho de compras, permitindo operações CRUD seguras. O projeto utiliza SQLAlchemy para integração com banco de dados e Flask-Login para controle de sessão.

### Tecnologias Utilizadas:
- **Flask**: Framework leve e poderoso para aplicações web em Python.
- **Flask-SQLAlchemy**: ORM para manipulação de banco de dados.
- **Flask-Login**: Gerenciamento de sessões e autenticação de usuários.
- **Flask-CORS**: Permissão para chamadas de diferentes origens.
- **Dotenv**: Gerenciamento de variáveis de ambiente.

### Funcionalidades Principais:
- **Autenticação de Usuário**: Login, logout e gerenciamento de sessão.
- **Gestão de Produtos**: Adição, edição, remoção e listagem de produtos.
- **Carrinho de Compras**: Adição, remoção, visualização e checkout de produtos.
- **Proteção de Rotas**: Algumas operações são protegidas por autenticação.

### Como Rodar o Projeto:
1. Clone o repositório.
2. Crie e ative um ambiente virtual.
3. Instale as dependências com `pip install -r requirements.txt`.
4. Crie um arquivo `.env` com as variáveis `SECRET_KEY` e `DATABASE_URL`.
5. Execute a aplicação com `python app.py`.

### Endpoints Disponíveis:
- **/login** (POST): Autenticação de usuário.
- **/logout** (POST): Finaliza a sessão do usuário.
- **/api/products** (GET): Lista todos os produtos.
- **/api/products/add** (POST): Adiciona um novo produto.
- **/api/products/update/<id>** (PUT): Atualiza um produto.
- **/api/products/delete/<id>** (DELETE): Remove um produto.
- **/api/cart** (GET): Visualiza o carrinho.
- **/api/cart/add/<id>** (POST): Adiciona um produto ao carrinho.
- **/api/cart/remove/<id>** (DELETE): Remove um produto do carrinho.
- **/api/cart/checkout** (POST): Finaliza a compra.

Esse projeto é ideal para quem deseja construir uma base sólida para um sistema de e-commerce. Sinta-se à vontade para contribuir e personalizar conforme suas necessidades!

