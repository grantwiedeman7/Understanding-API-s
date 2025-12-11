# Common API Errors and How to Fix Them

When working with APIs, you're guaranteed to run into a few common errors.

This page covers the most frequent beginner API mistakes and how to fix them.

---

## 1. Wrong Endpoint

If you misspell an endpoint or use the wrong URL, the API can’t find what you're asking for.

Example error:

```
404 Not Found
```

**Fix:**  
Check the exact endpoint spelling and structure in the API documentation.

---

## 2. Missing or Incorrect Parameters

Some APIs require parameters. If they're missing or invalid, you may get:

```
400 Bad Request
```

**Fix:**  
Add the proper parameters, such as:

```
?city=Chicago
?participants=2
```

---

## 3. Using the Wrong HTTP Method

Some APIs expect `GET`, others expect `POST`, `PUT`, etc.  
Using the wrong method results in:

```
405 Method Not Allowed
```

**Fix:**  
Check whether the API expects GET (retrieve data) or POST (send data).

---

## 4. Rate Limiting

If you make too many requests too quickly, the API may block you temporarily.

Example:

```
429 Too Many Requests
```

**Fix:**  
Wait a few seconds and reduce how often you send requests.

---

## 5. Invalid API Key (Only for Some APIs)

Some APIs require an API key. If it’s missing or incorrect:

```
401 Unauthorized
```

**Fix:**  
Use the correct key and include it exactly where the API expects it.

---

## Summary

Most API errors can be solved by checking:

1. Is the endpoint correct?
2. Are all required parameters included?
3. Am I using the right HTTP method?
4. Am I making too many requests?
5. Does this API require a key?

Understanding these errors will make debugging API calls much easier.

---

## Navigation
[Back: Making Your First API Call](04-making-your-first-api-call.md)  
[Back to Home](README.md)
