# Order Service

Node/Express service for order management.

## Prerequisites
- Node.js 18+
- PostgreSQL
- Product service reachable over HTTP

## Setup
```bash
npm install
npm start
```

## Environment Variables
- `DB_HOST` (default: `localhost`)
- `DB_NAME` (default: `ecommerce`)
- `DB_USER` (default: `postgres`)
- `DB_PASSWORD` (default: `password`)
- `PORT` (default: `3002`)
- `PRODUCT_SERVICE_URL` (default: `http://product-service:3001`)

## Endpoints
- `GET /health`
- `GET /orders`
- `POST /orders`
- `PATCH /orders/:id`

