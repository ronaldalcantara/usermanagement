<h1>API de Gerenciamento de Usuários</h1>
Esta é uma API RESTful para gerenciamento de usuários, construída com Node.js, Express e TypeScript, seguindo princípios de Clean Architecture, SOLID e Clean Code.

<h1>Pré-requisitos</h1>
<li>Node.js v16+</li>
<li>npm ou yarn</li>
<li>TypeScript v4+</li>
<li>SQLite3</li>

<h1>Instalação</h1>

Clone o repositório:
<li>git clone</li>
<li>cd express-api</li>

<h3>Instale as dependências:</h3>
<li>npm install ou yarn install</li>

<h3>Configure o ambiente:</h3>
Crie um arquivo .env na raiz do projeto:
<li>PORT=3000</li>
<li>DB_PATH=./database.sqlite</li>
<li>NODE_ENV=development</li>

<h1>Executando a API</h1>
Modo desenvolvimento:
npm run dev ou yarn dev

Modo produção:
npm run build
npm start ou yarn build
yarn start

Endpoints
Usuários
<li>POST /api/v1/users - Criar novo usuário</li>
<li>GET /api/v1/users - Listar todos os usuários (com filtros)</li>
<li>GET /api/v1/users/:id - Obter usuário por ID</li>
<li>PUT /api/v1/users/:id - Atualizar usuário</li>
<li>DELETE /api/v1/users/:id - Remover usuário</li>

Health Check
<li>GET /health - Verificar status da API</li>

<h1>Testes</h1>

Para executar os testes:
npm test ou yarn test

<h1>Docker</h1>
Para executar com Docker:

<h3>Construa a imagem:</h3>
docker build -t express-api .

<h3>Execute o container:</h3>
docker run -p 3000:3000 express-api

<h2>Boas Práticas Implementadas</h2>
<li>Clean Architecture</li>
<li>Princípios SOLID</li>
<li>DTOs para validação de entrada</li>
<li>Tratamento centralizado de erros</li>
<li>Segurança básica (helmet, CORS)</li>
<li>TypeORM para acesso a dados</li>
<li>Documentação de código</li>
<li>Variáveis de ambiente</li>
<li>Dockerização</li>
<hr>

<h3>Contato</h3>
Ronaldo de Alcântara - ronaldothealcantara@gmail.com
