// Init Tailwind
npx tailwindcss init

// Init shadcn-ui
npx shadcn-ui@latest init //new york slate colors(yes)

// Generate prisma schema for db (always run this when you make changes in schema.prisma file)
npx prisma generate

// Sync schema with db
npx prisma db push

// To start prisma db server on port 5555 (Good for managing data from db)
npx prisma studio
