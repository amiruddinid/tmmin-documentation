---
part: Documentation
title: Using NextBook
---

# Http status codes

## What's Http status codes ?

HTTP status codes are three-digit numbers returned by a server in response to a client's request. These codes indicate the result of the server's attempt to process the request, and they are categorized into five classes based on the first digit of the code. Below are the main categories of HTTP status codes and their meanings:
- **1xx - Informational**
- **2xx - Success**
- **3xx - Redirection**
- **4xx - Client Error**
- **5xx - Server Error**

## Why use Http status code ?
1.   **Client-Side Handling**: They help clients (e.g., browsers or mobile apps) understand how to react to the response, whether to display content, show an error message, or retry the request.
2.   **Server-Side Debugging**: Developers can use status codes to debug issues and handle errors effectively.
3.   **Search Engine Optimization (SEO)**: Proper handling of HTTP status codes helps with SEO, especially when handling redirects (301, 302) or ensuring pages return 404 when not found.