![Logo Swapcard](./assets/logo_swapcard.svg)

# Chat API in Node JS
Write a simple chat API using NodeJS.

## Prerequisites
- User and authentication
   - User creation
   - Authentication with session or stateless session
   - You must know which user sent a specific message
- Conversation channels
  - Create a channel
  - List the channels
  - List the messages inside a channel
  - Send a message to a channel
- Use a database (MongoDB/MySQL/PostgresQL/Cassandra or other)

## Bonus
- A ReactJS client. The client doesn’t need to implement every API feature but should be functional.
- Extended user:
  - Update/delete user
  - Email verification
  - Password recovery
- Extended channel: 
  - Delete a channel
  - A channel owner can invite/kick another user into to/from his channel
  - Users cannot read nor write into channel they aren’t a member of
- Extended message:
  - Update/delete messages
  - Add image/file to a message
  - Url metadata enrichment 
  - Message advanced search
- Api unit testing

## Objectives
- Try to keep it simple
- All the included features should work as intended
- Use modern JavaScript
- Using a strict syntactical superset of JavaScript like TypeScript or Flow is appreciated
- Using GraphQL is very appreciated, see: https://graphql.org/graphql-js/, https://www.apollographql.com/docs/react/essentials/get-started.html
