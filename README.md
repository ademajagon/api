# API

This is a serverless API using the Neon Database. It's designed to be deployed on Cloudflare Workers.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need to have Node.js and npm installed on your machine. You also need to have a PostgreSQL database available for connection.

### Installing

1. Clone the repository
2. Install the dependencies with `npm install`
3. Copy the `.env.example` to `.env` and fill in your database connection details

### Scripts

- `npm run deploy`: Deploy the application using Wrangler
- `npm run dev`: Start the development server using Wrangler
- `npm run start`: Alias for `npm run dev`
- `npm run db:generate`: Generate the database schema using Drizzle Kit
- `npm run db:migrate`: Run the database migrations

## Built With

- [@neondatabase/serverless](https://www.npmjs.com/package/@neondatabase/serverless)
- [drizzle-orm](https://www.npmjs.com/package/drizzle-orm)
- [hono](https://www.npmjs.com/package/hono)
