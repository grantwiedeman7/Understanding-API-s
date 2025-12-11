# How APIs Work

Now that you know what an API is, let's look at how it works behind the scenes.  
An API follows a simple request–response process where a client (you) asks a server for information.

---

## The API Workflow (Simple Breakdown)

1. **The client sends a request**  
   - This could be a website, phone app, or script.
   - You request data, like “Give me today’s weather.”

2. **The API receives the request**
   - The API checks whether the request is allowed.
   - It finds the correct resource you’re asking for.

3. **The server processes the request**
   - It pulls data from a database
   - Runs logic
   - Formats the response

4. **The API sends back a response**
   - Usually in JSON format 
   - The app uses that data to show something meaningful

---

## Real Example: Weather App API Request

You open your weather app.  
The app sends a request like:


The server responds with something like:

GET https://api.weather.com/today?city=Chicago

json:
{
  "city": "Chicago",
  "temperature": 42,
  "condition": "Cloudy"
}


