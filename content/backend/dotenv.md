
# dotenv

## What's dotenv ?

Dotenv is a zero-dependency module that loads environment variables from a `.env` file into [`process.env`](https://nodejs.org/docs/latest/api/process.html#process_process_env). Storing configuration in the environment separate from code is based on [The Twelve-Factor App] methodology.

## Why use dotenv ?

1. **Centralized Configuration**:

   **Dotenv** allows you to keep your environment-specific configurations in a single `.env` file, making it easier to manage. This includes settings like API keys, database connection strings, ports, and other environment-specific values.

2. **Security (Avoid Hardcoding Secrets)**:

   Storing sensitive information such as API keys, database credentials, or other secrets directly in the codebase is a security risk, especially when code is pushed to version control systems like Git.

3. **Simplifies Local Development**:

   During local development, you often need to set up various environment variables for the app to function properly (such as database URLs or third-party API keys). Using **Dotenv**, you can quickly set these variables without having to manually configure your local environment.

4. **Maintainability**:

   By centralizing configuration settings in a `.env` file, **Dotenv** improves the maintainability of your application. When configuration changes are needed (e.g., changing a database URL or API endpoint), you only need to modify the `.env` file rather than searching through the codebase for hardcoded values.

5. **Cross-Platform Compatibility**:

   Since Dotenv loads environment variables from a `.env` file, it works consistently across different platforms, regardless of whether you're developing on macOS, Windows, or Linux. The `.env` file can be included in the project without worrying about platform-specific issues with setting environment variables.