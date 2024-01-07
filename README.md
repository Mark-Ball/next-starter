This is a starter kit to quickly set up a project using the following technologies:
- NextJS
- Tailwind
- Prisma

## Getting Started

First, run the development server:

```bash
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Database Setup

We use Prisma as our ORM.

Sync the database with the Prisma schema
```bash
yarn prisma db push
```

Seed initial data
```bash
yarn prisma db seed
```

You can now view the data by connecting your favourite tool (DBeaver, Valentina Studio, PG Admin etc) to the database. Alternatively Prisma provides a UI to explore your database:

```bash
yarn prisma studio
```

Then view the database on `localhost:5555`
