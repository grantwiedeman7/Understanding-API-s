# Making Your First API Call

Now that you understand endpoints and JSON, let’s make a real API request using a public, free API.

We will use the **Bored API**, which returns a simple activity suggestion.

---

## Step 1: The API Endpoint

Here’s the URL: https://catfact.ninja/fact


When you visit that link in any browser, the API sends back JSON like this:

```json
{
  "fact": "Cats have five toes on their front paws but only four on their back paws.",
  "length": 79
}
```

## Step 2: How to Make the Request

You can make the request in several simple ways:

### 1. In your browser
Paste the URL into the address bar.

### 2. Using curl (optional)
```
curl https://catfact.ninja/fact
```

### 3. Using an API testing tool (optional)
Tools like Postman let you paste the URL and click “Send.”

---

## Step 3: Understanding the Response

The JSON shows:

- `"activity"`  -> Suggested activity
- `"type"` ->  Category
- `"participants"` -> How many people it’s for

This is the basic structure almost every API uses.

---

## Step 4: Adding Parameters (Optional)

You can customize your request by adding parameters:

```
https://www.boredapi.com/api/activity?participants=2
```

Example JSON result:

```json
{
  "activity": "Go for a picnic",
  "type": "social",
  "participants": 2
}
```

Parameters allow you to request more specific data.

---

## Summary

To make an API call:

1. Choose an endpoint  
2. Make the request  
3. Read the JSON response  

This is the foundation of how modern apps communicate with APIs.

---

## Navigation

[Back: Understanding Endpoints and JSON](03-json-and-endpoints.md)  
[Next: Common API Errors](05-common-errors.md)

