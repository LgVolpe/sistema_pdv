# Sistema PDV
**API de Ponto de Venda (Frente de Caixa)**

Este projeto consiste em uma API para um sistema de Ponto de Venda (PDV) que gerencia categorias, clientes, pedidos, produtos e usuários. A API permite criar, listar e atualizar esses dados com autenticação segura e manipulação de valores monetários em centavos.

---

## Tecnologias Utilizadas
- Node.js
- Express.js
- PostgreSQL
- JWT (JSON Web Token)

---

## Pré-requisitos
- Node.js instalado
- PostgreSQL instalado
- Git (opcional)

---

## Instale as Dependências
```bash
npm install
Inicie o Servidor
npm run dev
Acesse a API
A API estará disponível em http://localhost:3000 por padrão. Você pode usar ferramentas como o Postman ou Insomnia para testar as rotas da API.

Rotas da API
GET /categorias - Listar categorias
POST /usuarios - Cadastrar usuário
POST /login - Efetuar login do usuário
GET /perfil - Detalhar perfil do usuário logado
PUT /perfil - Editar perfil do usuário logado
Contribuição
Sinta-se à vontade para contribuir com melhorias neste projeto. Abra um problema ou envie uma solicitação de pull.

### Instruções para colar no GitHub:

1. Crie um arquivo chamado `README.md` na raiz do seu repositório no GitHub (se ainda não existir).
2. Cole o texto formatado acima nesse arquivo.
3. Commit e faça o push do arquivo para o seu repositório no GitHub.

Esse formato é otimizado para ser visualizado corretamente no GitHub e separa as seções de forma clara. Quando você visualizar o repositório no GitHub, ele será exibido com a formatação que você deseja!


