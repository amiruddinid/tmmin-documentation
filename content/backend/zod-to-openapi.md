---
part: Documentation
title: Using NextBook
---

# Zod to OpenAPI

## What's Zod to OpenAPI ?

The **"Zod to OpenAPI"** process refers to **generating OpenAPI documentation** directly from **Zod schemas**. Since Zod is commonly used to validate and define the types of data in backend applications, it makes sense to reuse these schemas for generating **OpenAPI** specifications. This avoids the need for duplicating schema definitions in multiple places (once for validation and once for API documentation).

### What Are Zod and OpenAPI?

-   **Zod**:
    
    -   Zod is a TypeScript-first schema declaration and validation library. It allows you to define **schemas** for data (e.g., request payloads, responses) and validate them at runtime. Zod provides an intuitive API to create strongly typed, validated data structures, which can be used for input validation, transforming data, and type-checking.

- **OpenAPI**:

	-   OpenAPI is a specification (formerly known as Swagger) used to define and document **RESTful APIs**. It describes API endpoints, request/response formats, data types, authentication methods, and more. OpenAPI documentation is typically used to automatically generate interactive documentation for APIs (like **Swagger UI**) and to generate client SDKs.
-   OpenAPI documentation is typically written in YAML or JSON format.

## Why use Zod to OpenAPI ?

1.   **Single Source of Truth**:
    
       With Zod to OpenAPI, you can define your data validation and OpenAPI schema in a single place. This avoids duplicating the definitions for both validation (in Zod) and documentation (in OpenAPI).
2.   **Type Safety**:
    
       Since Zod is TypeScript-first, using it for both validation and OpenAPI schema generation ensures that your API documentation is in sync with your TypeScript types, providing better type safety across your application.
3.   **Automatic Generation**:
    
       Instead of manually writing OpenAPI specifications in YAML or JSON, you can automate the process by directly converting Zod schemas to OpenAPI-compliant JSON. This can save time and reduce the likelihood of human error in API documentation.
4.   **Consistent API Documentation**:
    
       If your API validation schemas are already defined in Zod, generating OpenAPI documentation from them ensures that the **API specs** reflect the actual data validation logic, making it easier to maintain consistency between your backend logic and API documentation.
5.   **Integration with Tools**:
    
       Once you have OpenAPI documentation generated from your Zod schemas, you can leverage tools like **Swagger UI** to automatically generate interactive API documentation for testing and exploring your API. This can improve the developer experience and make your API easier to understand for clients.