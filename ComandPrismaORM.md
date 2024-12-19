## 1. Instalar o Prisma e o Client

npm install @prisma/client
npm install prisma --save-dev

## 2. Inicializar o Prisma

npx prisma init

## 3. Gerar o Prisma Client

npx prisma generate

## 4. Migrar o Banco de Dados

npx prisma migrate dev --name nome-da-migracao

## 5. Verificar o Banco de Dados

npx prisma studio

## 6. Resetar o Banco de Dados (em desenvolvimento)

npx prisma migrate reset

## 7. Aplica mundanças e corrigir estrutura do schema

npx prisma format
