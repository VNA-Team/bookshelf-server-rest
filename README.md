# Bookshelf backend

The goal in this application is to showcase a real-world scenario of an
application using Primsa. It will cover:

- Data modeling
- CRUD
- Aggregations
- REST API layer
- Validation
- Testing
- Authentication
- Authorization
- Continous Integration
- Deployment

# Data model

- **Book**: All of the books that user can choose to read
- **Item**: User's list book. User is reading book or finished it.
- **User**: A person with an account.
-

# Tech Stack

- Backend:
  - PostgreSQL
  - Node.js
  - Prisma
  - TypeScript
  - Jest
  - Hapi.js

# How to use

Install npm dependencies:

```bash
npm install
```

Run local database

```bash
npm run postgres:start
```

Start local dev

```bash
npm run dev
```
