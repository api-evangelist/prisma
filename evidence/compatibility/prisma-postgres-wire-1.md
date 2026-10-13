<!-- fetched 2026-10-13 from https://www.prisma.io/docs/postgres by sweep-shape-compat.py; text extracted from the provider's own page -->

Overview | Prisma Postgres | Prisma Documentation 
 For the complete Prisma documentation index optimized for AI agents, see https://www.prisma.io/docs/llms.txt . A markdown version of every docs page is available by appending .md to its URL.
 Prisma ORM 8 is here. The docs now default to Prisma ORM 8. Prisma ORM 7 docs stay at /orm/v7. Read the docs 
 All docs Postgres
 Introduction
 Prisma Postgres create-db Best Postgres for AI apps Database
 Database Connecting to your database Connect to Prisma Postgres without Accelerate Connection pooling Query Insights Backups Extensions Serverless driver Tools & Integrations
 Raycast MCP Studio VSCode Infrastructure as Code
 Terraform Pulumi More
 Error reference Troubleshooting Prisma Postgres FAQ Migrate from EA to GA 
 Prisma home 
 / docs Prisma documentation home / Postgres 
 ⌘ K 
 Ask AI Ctrl I 
 Ask AI 
 Login 
 Prisma Postgres 
 Prisma Postgres
 Copy Markdown Open 
 Connect to Prisma Postgres from Prisma ORM, serverless runtimes, and PostgreSQL clients.
 Prisma Postgres is managed PostgreSQL 17 with PgBouncer pooling on every plan and daily backups on paid plans, taken only on days the database has activity; host the app next to it on Prisma Compute , or connect from any Postgres client.
 To your application it is a regular PostgreSQL database behind a connection string:
 Your application 
 ↓ DATABASE_URL 
 Prisma Postgres 
 Any PostgreSQL client works: Prisma ORM, psql , Kysely, Drizzle, node-postgres , or anything else that speaks Postgres.
 Getting started 
 1. Create a database 
 The fastest way, with no account required:
bun 
pnpm 
yarn 
npm 
 bunx create-db@latest 
 create-db creates a temporary Prisma Postgres database and prints a connection string plus a claim URL. Open the claim URL to keep the database in your workspace. See create-db for details. You can also create databases in the Console or with the Prisma CLI ( npx prisma postgres create ). If your data already lives in a PostgreSQL database on your laptop or another host, migrate it to Prisma Postgres in three steps: create the database, pg_dump , pg_restore .
 2. Copy the connection string 
 create-db prints it once; for an existing database, open it in Prisma Console and click Connect to your database . Store it where your app reads configuration:
 .env 
 DATABASE_URL="postgres://...@db.prisma.io:5432/postgres?sslmode=require" 
 3. Connect and run a query 
 Pick the client you use; each quickstart takes you from connection string to a first query:
 Prisma ORM quickstart
 Define a data contract and query with Prisma ORM.
 Prisma ORM 7 quickstart
 Connect with the current GA release of Prisma ORM.
 Kysely quickstart
 Connect Prisma Postgres from Kysely.
 Drizzle ORM quickstart
 Connect Prisma Postgres from Drizzle ORM.
 Also available: the TypeORM quickstart and Connecting to your database , which covers connection strings for psql , GUI tools, and serverless runtimes.
 If you work with a coding agent, copy this prompt:
 Use with your agent View Copy prompt 
 Use with your agent Copy prompt 
 Create a Prisma Postgres database for this project. 
 1. Run `npx create-db@latest`. It creates a temporary Prisma Postgres database without an account and prints a connection string plus a claim URL. 
 2. Put the connection string in `.env` as DATABASE_URL and wire it into whichever of Prisma ORM, Kysely, Drizzle, TypeORM, or node-postgres the project already uses (detect it from package.json; if none, ask me). Verify the connection with one trivial query such as `select 1`. 
 3. Remind me to open the claim URL to keep the database in my Prisma workspace. 
 Current docs: https://www.prisma.io/docs/postgres.md. 
 What's included 
 Each Prisma Postgres database includes the following, with no extra services to configure:
 Connection pooling : a dedicated PgBouncer instance runs alongside your database, with nothing to set up or manage. It also works for serverless and edge deployments. See Connection pooling .
 Edge and serverless support : connect from Cloudflare Workers, Vercel Edge Functions, and other edge runtimes via the serverless driver , which uses HTTP instead of TCP.
 Automated backups (Starter, Pro, and Business plans): daily snapshots, kept for 7 or 30 days depending on the plan. See Backups .
 Local development 
 Run Prisma Postgres locally with prisma dev , then switch to cloud when ready.
 Local Postgres 
 Use with the rest of Prisma 
 Each integration is optional, and Prisma Postgres works with any PostgreSQL client.
 If you use Prisma ORM , the quickstart provisions a database and connects it to your data contract.
 If you deploy on Prisma Compute , each branch of a Compute project can have its own Prisma Postgres database; pass the connection string through environment variables .
 For a multi-service application, Prisma Composer (Early Access) declares a database as a service dependency and injects the connection at runtime.
 Manage 
 Connecting to your database 
 Connection pooling 
 Backups 
 PostgreSQL extensions 
 Troubleshooting 
 FAQ 
 Billing and limits 
 Prisma Postgres uses usage-based pricing and includes spend controls.
 Pricing 
 Operations-based billing explained 
 FAQ: estimating costs 
 In Prisma Console, you can track usage, set spend limits, and view billing details.
 Technical details 
 Prisma Postgres is based on PostgreSQL v17 and uses a unikernel-based architecture.
 Learn more: Prisma Postgres: Building a modern PostgreSQL service .
 Note
 Postgres, PostgreSQL, and the Slonik Logo are trademarks or registered trademarks of the PostgreSQL Community Association of Canada and are used with permission.
 Edit on GitHub 
 create-db
 Create a temporary Prisma Postgres database with one command and no sign-up, for prototypes, tests and coding agents. Claim it with a Prisma account to keep it.
 On this page
 Getting started 1. Create a database 2. Copy the connection string 3. Connect and run a query What's included Local development Use with the rest of Prisma Manage Billing and limits Technical details
