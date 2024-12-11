---
part: Documentation
title: Using NextBook
---

# Helmet

## What's Helmet ?

**Helmet** is a security middleware for Express.js applications. It helps secure your Node.js application by setting various HTTP headers that improve security and protect against common web vulnerabilities.

Helmet is essentially a collection of middleware functions that can be used to set specific HTTP headers to defend against attacks like **cross-site scripting (XSS)**, **clickjacking**, and **content injection**. It provides easy-to-use middleware to secure HTTP headers for your Express.js application.

## Why use Helmet ?

1.   **Protection Against Cross-Site Scripting (XSS)**: Cross-site scripting (XSS) attacks occur when malicious scripts are injected into websites. **Helmet** helps mitigate XSS risks by setting the **Content-Security-Policy (CSP)** header, which restricts the sources from which scripts, images, and other resources can be loaded. This reduces the attack surface for potential XSS attacks.
    
2.   **Clickjacking Protection**: **Clickjacking** is a malicious technique where a user is tricked into clicking something different from what they think they are clicking, often by embedding content from the target website into an iframe. The **X-Frame-Options** header added by Helmet prevents this by disallowing your pages from being embedded in iframes on other websites.
    
3.   **Content Type Sniffing Prevention**: **Content type sniffing** is a technique where browsers try to detect the content type of a resource based on its content. Attackers can exploit this behavior to force browsers to treat a malicious file as a different type, such as an executable or script. Helmet sets the **X-Content-Type-Options** header to prevent browsers from sniffing content types, ensuring files are treated according to their declared MIME type.
    
4.   **HTTP Strict Transport Security (HSTS)**: **HSTS** is a web security policy mechanism that helps protect websites against **man-in-the-middle (MITM) attacks**. When a browser receives the **Strict-Transport-Security** header, it knows that it should always use HTTPS to access the site, thus preventing attackers from downgrading the connection to HTTP. This is particularly useful for enforcing secure connections in production environments.

5. **Simplified Security Setup**: Implementing security best practices across a Node.js application can be complex. Helmet simplifies this process by providing default security headers that cover most common use cases. You can easily enhance your application's security by including the Helmet middleware, without the need to manually configure each individual security header.