
# envalid

## What's envalid ?

Envalid is a small library for validating and accessing environment variables in Node.js (v6.0 or later) programs, aiming to:

- ensure that your program only runs when all of its environment dependencies are met

- give you executable documentation about the environment your program expects to run in

- give you an immutable API for your environment variables, so they don't change from under you while the program is running

## Why use envalid?

1. **Environment Variable Validation**:

   One of the core features of **Envalid** is its ability to **validate environment variables** to ensure they are set correctly. It can check that environment variables are present, have the correct data type (e.g., string, number, boolean), and meet specific constraints. This is important because missing or malformed environment variables can lead to runtime errors or unexpected behavior in your application.

2. **Improved Error Handling**:

   When using **Envalid**, you get immediate feedback if required environment variables are missing or invalid. This is much better than relying on traditional checks with `process.env` and throwing custom errors. Envalid automatically throws a descriptive error when a required environment variable is missing or doesn't meet the validation criteria.

3. **Type Safety**:

   **Envalid** ensures that environment variables are correctly typed. For example, you can ensure that a variable expected to be a number is indeed a number, or that a string is properly formatted. This reduces the chance of runtime errors caused by invalid data types and makes your code more predictable and reliable.

4. **Default Values**:

   With **Envalid**, you can define **default values** for environment variables that may not be explicitly set in your environment. This ensures your application behaves predictably, even when some variables are not provided.

5. **Simplifies Configuration Management**:

   **Envalid** allows you to define and enforce a **configuration schema** for your environment variables, which makes it easier for other developers or team members to understand the environment variable expectations for your application. This can also help reduce confusion during onboarding or when deploying the app.