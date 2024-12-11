---
part: Documentation
title: Using NextBook
---

# express rate limit

## What's express rate limit?

`express-rate-limit` is a middleware for **Express.js** applications that helps to prevent abuse by limiting the number of requests a client can make to the server within a specific time frame. It is a popular tool for implementing **rate-limiting** in web applications to safeguard against **DoS (Denial of Service)** attacks, **brute force attacks**, and **excessive resource consumption**.

## Why use express rate limit?
1.   **Preventing abuse**: Protects your server from too many requests coming from a single source (e.g., a bot or malicious user).
2.   **Managing traffic**: Ensures that server resources are distributed fairly and that no single client consumes all the bandwidth or processing power.
3.   **Improving security**: Helps prevent brute-force login attempts, where a malicious user tries multiple password combinations in a short time.