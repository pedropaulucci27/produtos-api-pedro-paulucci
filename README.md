# API REST de Produtos
 
Nome: Pedro Paulucci de Noronha
matrícula: 202501246982

## Descrição
API REST desenvolvida em Node.js com Express para gerenciamento de produtos.

## Como executar 

1. Instalar dependências:
npm install

2. Rodar o projeto
npm run dev

3. API será iniciada em: http://localhost:3000


## Endpoints 

| Método | Rota | Descrição | Status de sucesso | Status de erro |
|---|---|---|---|---|
| GET | /api/v1/produtos | Lista todos os produtos | 200 OK | — |
| GET | /api/v1/produtos/:id | Busca um produto pelo ID | 200 OK | 404 Not Found |
| POST | /api/v1/produtos | Cria um novo produto | 201 Created | 400 Bad Request |
| PUT | /api/v1/produtos/:id | Atualiza completamente um produto | 200 OK | 404 Not Found |
| DELETE | /api/v1/produtos/:id | Remove um produto pelo ID | 204 No Content | 404 Not Found |

