# next-route-middleware

Next js routing middelware with access control

Next js App with Tailwind CSS, TypeScript and Mongodb database.

Clone the repo and run below command in your terminal.

---

yarn

yarn add -g prisma

yarn dev

---

Generating types with Codegen
GraphQL Codegen can be used for many different scenarios. But in the context of a GraphQL API, you will want typings for your resolvers. These are generated automatically based on your GraphQL schema.

you can customize the schema path with respective file.

.graphql or .gql file extenssion required

---

schema: src/**/*.graphql
generates:
./src/types/resolvers-types.ts:
plugins: - add: |- - typescript - typescript-resolvers

---
after this open the terminal and run below command in the same dir.

---

prisma generate

--- 

after this commands open your browser and type http://localhost:3000/graphql
