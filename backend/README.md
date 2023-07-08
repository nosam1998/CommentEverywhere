# Backend GraphQL Server for the CommentEverywhere app

### Structure

```
backend
 ┣ graph
 ┃ ┣ model
 ┃ ┃ ┗ models_gen.go
 ┃ ┣ generated.go
 ┃ ┣ resolver.go
 ┃ ┣ schema.gql - GraphQL Schema that is used to generate the rest of the code.
 ┃ ┗ schema.resolvers.go - The resolvers used for the GraphQL schema.
 ┣ README.md
 ┣ go.mod
 ┣ go.sum
 ┣ gqlgen.yml - The config for gqlgen
 ┣ server.go
 ┗ tools.go - For gqlgen (DO NOT TOUCH)
```
