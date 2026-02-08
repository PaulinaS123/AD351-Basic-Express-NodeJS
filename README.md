# AD351-Basic-Express-NodeJS
### Victoria Salomon
## Basic Express Server 

This project is a simple Node.js server built using Express.  
It demonstrates routing, conditional routing, regex routes, dynamic routes, query strings, and error handling.

## How to Run

1. Install dependencies:
   ```bash
   npm install
### How to Run the Project
1. Clone the repository:
    ```bash
    git clone <your-github-repo-link>
2. Navigate into the project folder:
    ```bash
    cd basic-express-server
3. Install dependencies:
   ```bash
   npm install
4. Start the server:
   ```bash
   node app.js
5. Open a browser and visit:
   ```bash
   http://localhost:3000

### Available Routes

- / → Returns Hello World
- /about → Returns About page
- /foo → Randomly returns:
- sometimes this
- and sometimes that
- /user or /username → Returns a regex route response
- /user/:username → Returns a personalized message (example: /user/paulina)
- /get?key=value → Logs query parameters to the console
- Any other route → Returns 404 - Not Found

### Notes

The server listens on port 3000 by default or uses the port provided by the environment.

Routes were tested using the browser and localhost URLs.


