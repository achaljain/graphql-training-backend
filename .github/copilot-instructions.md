<!-- Use this file to provide workspace-specific custom instructions to Copilot. For more details, visit https://code.visualstudio.com/docs/copilot/copilot-customization#_use-a-githubcopilotinstructionsmd-file -->

# E-Commerce GraphQL API with TypeORM and PostgreSQL

This is a GraphQL API for an e-commerce platform built with:
- TypeScript
- Node.js & Express
- Apollo Server
- TypeORM
- PostgreSQL
- Type-GraphQL

## Workspace Structure

- `/src/entities`: Database entity models (User, Product, Category, Cart, CartItem)
- `/src/resolvers`: GraphQL resolvers for each entity
- `/src/services`: Business logic services
- `/src/migrations`: TypeORM migrations
- `/src/config`: Configuration files

## API Features

- User authentication (register/login)
- Product management (create, list, get by id)
- Category management (create, list, get by id)
- Cart operations (add to cart, remove from cart, view cart)

## Tips for working with this codebase

When helping with this codebase:
- Use TypeORM decorators for entity definitions
- Use Type-GraphQL decorators for GraphQL schema definitions
- Follow the existing patterns for resolvers and services
- Maintain strong typing throughout
- Use best practices for TypeScript and GraphQL
