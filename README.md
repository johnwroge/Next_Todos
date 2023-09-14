
## Getting Started

This application is a basic todo list generator that utilizes server side rendering to display components. The app utilizes a local prisma database which will need to be initialized prior to running the application.

First, 

```npm i prisma --save-dev```

```npx prisma init --datasource-provider sqlite```

create database schema in prisma file ... 

Create a local database by creating an .env file
example:

'''
DATABASE_URL="file:./dev.db"
'''

do a migration into our dev environemnt:

```npx prisma migrate dev --name init```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

