---
part: Documentation
title: Using NextBook
---

# Husky

## What's Husky ?

Husky is a tool used in development workflows to enforce coding standards and run pre-commit or pre-push hooks in your Git repositories. It is primarily used in the **frontend** and **backend** development ecosystems to ensure code quality by automating tasks like linting, testing, formatting, or other validation steps before committing or pushing code to a repository.

## Why use Husky ?
1.   **Enforcing Code Quality**: In a backend project, you may want to ensure that all code committed to the repository follows certain standards like linting (e.g., ESLint) or code formatting (e.g., Prettier). Husky helps automate this process by running the relevant checks before each commit or push.
    
2.   **Running Tests**: To make sure new changes don't break existing functionality, you can configure Husky to run unit tests or integration tests before pushing code. For example, you can set up a **pre-push** hook that runs your test suite.
    
3.   **Standardizing Commit Messages**: With backend projects, especially in teams, it’s essential to have a consistent format for commit messages. You can use Husky with tools like **Commitlint** to enforce specific formats for commit messages, which can be crucial for maintaining readable and well-structured version history.
    
4.   **Preventing Broken Code**: By running checks like linting and tests before a commit or push, Husky ensures that broken code (e.g., code with syntax errors or failing tests) never gets committed to the repository.