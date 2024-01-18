# Start a Working Express Server

## Overview
In the `myApp.js` file, creating an Express app object is straightforward. This object possesses numerous methods, a key one being `app.listen(port)`, which sets your server to listen on a specified port, making it operational. For testing, we've already included this method in the `server.js` file.

## Serving Your First String
Express routes follow the structure `app.METHOD(PATH, HANDLER)`. Here:
- `METHOD` is an HTTP method in lowercase.
- `PATH` is a relative path on the server, which can be a string or a regular expression.
- `HANDLER` is a function called by Express when the route is matched, typically in the form `function(req, res) {...}`, where `req` is the request object, and `res` is the response object.

### Example
```javascript
function(req, res) {
  res.send('Response String');
}
```

This handler serves the string 'Response String'.


### Task
Use the app.get() method to respond to GET requests at the root (/) path with the string "Hello Express". Ensure your code functions correctly by checking the logs. If using Replit, you can view the results in the preview.

### Note
Add all code for these lessons within the initial few lines of code provided.
