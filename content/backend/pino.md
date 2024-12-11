---
part: Documentation
title: Using NextBook
---

# Pino

## What's Pino ?

**Pino** is a fast and lightweight JSON-based logging library for Node.js applications. It's designed for high-performance logging with low overhead, which makes it especially useful for backend services that need to handle large volumes of log data in production environments.

## Why use Pino ?

1. **High Performance**:

   **Pino** is designed to be extremely fast and efficient. It is one of the fastest logging libraries available for Node.js, with low overhead on the application. It achieves this by using **asynchronous log processing** and **minimal processing** for each log entry.

2. **Structured Logging**:

   Unlike traditional logging systems that output logs as plain text, **Pino** generates **structured logs** in JSON format. This makes it easier to parse, search, and analyze logs programmatically.

3. **Asynchronous Logging**:

   **Pino** is built to be non-blocking and **asynchronous**, meaning it does not interfere with the performance of your application. Logs are written asynchronously, so the application doesn't wait for the log to be processed, preventing any slowdowns.

4. **Efficient for Distributed Systems**:

   **Pino** is highly suited for **microservices** and **distributed systems**. It can generate structured logs with unique **trace IDs** and **span IDs**, which allow you to track requests across multiple services in your system.

5. **Error Handling and Contextual Logging**:

   **Pino** allows you to add rich context to your logs, such as user data, request metadata, or error details. This makes it easier to diagnose issues and provides more actionable insights.