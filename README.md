# Next.js 14 #

## Prisma, SQLite, TailwindCSS, TypeScript, ESLint, Prettier ##

### pnpm create next-app ###

dependencies:

+ next 14.1.3
+ react 18.2.0
+ react-dom 18.2.0

devDependencies:

+ @types/node 20.11.28
+ @types/react 18.2.66
+ @types/react-dom 18.2.22
+ autoprefixer 10.4.18
+ eslint 8.57.0
+ eslint-config-next 14.1.3
+ postcss 8.4.35
+ tailwindcss 3.4.1
+ typescript 5.4.2

### Commands used at startup ###

+ pnpm add --save-dev eslint-config-prettier
+ pnpm install sqlite3
+ pnpm add --save-dev prisma
+ pnpm prisma init
+ pnpm prisma db push
+ pnpm up

### Tips ###

#### Prisma ####

+ `pnpm prisma init` - Initialize Prisma
+ `pnpm prisma db push` - Create the database and tables
+ `pnpm prisma generate` - Generate the Prisma client
+ `pnpm prisma studio` - Open the Prisma Studio
+ `pnpm prisma migrate dev --name init` - Create a migration
+ `pnpm prisma migrate deploy` - Deploy the migration
+ `pnpm prisma migrate resolve` - Resolve the migration
+ `pnpm prisma migrate reset` - Reset the migration
+ `pnpm prisma migrate status` - Show the migration status
+ `pnpm prisma migrate list` - List the migrations
+ `pnpm prisma migrate up` - Apply the migration
+ `pnpm prisma migrate down` - Revert the migration
+ `pnpm prisma format` - Format the schema
+ `pnpm prisma introspect` - Introspect the database

#### Sources ####

+ <https://dev.to/azadshukor/setting-up-nextjs-13-with-prisma-and-sqlite-1lld>
+ <https://nextjs.org/docs/app/building-your-application/configuring/eslint>
