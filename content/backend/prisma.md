---
part: Documentation
title: Using NextBook
---

# Prisma

## What's Prisma?

**Prisma** is an open-source **next-generation ORM (Object-Relational Mapping)** tool for Node.js and TypeScript. It simplifies database interactions by providing a type-safe, auto-generated query builder and schema management for relational databases (such as PostgreSQL, MySQL, SQLite, and SQL Server) and also supports MongoDB.

## Why use Prisma?

1. **Type Safety and Autocompletion**:

   **Prisma** generates a **TypeScript/JavaScript client** with type safety, which helps catch errors at compile time rather than runtime. This makes it easier to work with database models and ensures that your queries are correct.

2. **Simplifies Database Queries**:

   Prisma provides a **query builder** that abstracts complex SQL queries into simple and readable JavaScript/TypeScript code. You don’t need to write raw SQL queries for basic CRUD operations; Prisma handles it for you.

3. **Database Migrations**:

   Prisma provides an easy-to-use tool for managing **database migrations**. It ensures that your database schema is in sync with your application code by generating and applying migration files automatically.

4. **Automatic Schema Generation**:

   Prisma automatically generates the database schema and type definitions from your models defined in the **Prisma schema file** (`schema.prisma`). This means that there is no need to manually write SQL scripts to create or update database tables—everything is handled automatically through migrations.

5. **Seamless Relationship Management**:

   Prisma handles **relationships** between database tables (such as one-to-many, many-to-many, and one-to-one) very easily. You don’t have to write complex JOIN queries or manage foreign keys manually—Prisma manages relationships in a more intuitive and readable way.