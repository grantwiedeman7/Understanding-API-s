# Understanding Endpoints and JSON

APIs use two important pieces when sharing data:

- **Endpoints** (where you request data)
- **JSON** (the format data is returned in)

---

## What Is an Endpoint?

An **endpoint** is a URL that gives you specific information from an API.

Example:

**https://api.weather.com/today?city=Chicago**

Breakdown:

- `/today` → the endpoint  
- `?city=Chicago` → a parameter that tells the API which city you want  

Different endpoints return different types of data, similar to how different vending machine slots give different items.

---

## What Is JSON?

Most APIs return data in **JSON** (JavaScript Object Notation).  
It’s structured, readable, and used by almost every web app.

Example:

```json
{
  "city": "Chicago",
  "temperature": 42,
  "condition": "Cloudy"
}

Back: [How APIs Work](02-how-apis-work.md)
Next: [Making Your First API Call](04-making-your-first-api-call.md)
