# Logistics Platform - Backend

Express.js backend server for the logistics platform.

## Setup

1. Install dependencies:
```bash
npm install
```

2. Create `.env` file from `.env.example`:
```bash
cp .env.example .env
```

3. Update `.env` with your database credentials

4. Run migrations (when created)

5. Start development server:
```bash
npm run dev
```

The server will run on http://localhost:5000

## API Routes

- `GET /api/health` - Health check endpoint

## Database Setup

Create a PostgreSQL database:

```sql
CREATE DATABASE logistics_db;
```

## Environment Variables

See `.env.example` for required variables.
