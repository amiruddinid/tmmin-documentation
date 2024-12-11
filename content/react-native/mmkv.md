---
part: Documentation
title: Using NextBook
---

# MMKV
## What's MMKV ?

**MMKV** in React Native is a high-performance key-value storage library that provides fast and efficient local storage solutions for your app. It is based on **MMKV (Mobile Memory Key-Value)**, an open-source storage engine developed by **Tencent**. MMKV is designed to provide a faster, more memory-efficient alternative to other storage methods like `AsyncStorage` in React Native.

## Why use MMKV ?

1.   **Performance**: MMKV is optimized for speed, offering better performance than `AsyncStorage` for apps that require frequent and fast read/write operations, such as apps that manage session tokens, user preferences, or temporary data.
    
2.   **Efficient Memory Usage**: It helps reduce memory consumption and speed up app performance, especially for apps that need to handle large amounts of data locally.
    
3.   **Built-in Encryption**: MMKV provides an easy way to store encrypted data, which is essential for apps that need to keep sensitive information secure (e.g., user credentials or personal data).
    
4.   **Better Handling of Complex Data**: MMKV allows you to store complex data types directly without the need for manual serialization or deserialization, making it easier to work with structured data.
    
5.   **Cross-Platform Compatibility**: Since it works on both **iOS** and **Android**, MMKV simplifies the process of developing apps that need fast local storage across different platforms.
    
6.   **Atomic Transactions**: MMKV ensures that your data operations are performed atomically, preventing data corruption when the app is performing multiple simultaneous operations on the storage.