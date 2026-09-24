
### `backend-api/README.md`
```markdown
# Acme Retail — Backend API

REST API powering the Acme Retail product catalog and order management.

## Tech Stack
- Node.js + Express
- PostgreSQL
- Redis (caching)

## Endpoints
| Method | Path | Description |
|---|---|---|
| GET | /products | List all products |
| GET | /products/:id | Get product details |
| POST | /orders | Create a new order |
| GET | /orders/:id | Get order status |

## Getting Started
```bash
npm install
npm run dev
