## My Project Backend / Frontend boilerplate

### How to Run Locally

1. **Clone and Install Dependencies**
   ```bash
   git clone <your-repo-url>
   cd my-project-backend
   npm install
   ```

### Set up Environment Variables
2. Copy the `.env.example` file and rename it to `.env`
3. Fill in required credentials

### Start the Server
   ```bash
   npm run dev #auto-reload
   ```
   ```bash
   npm start
   ```

### Sharing & release example
- backend `package.json` Express / FastAPI etc (`nodemon` server restarts automatically when code changes)
  ```json
  {
  "name": "my-backend-api",
  "version": "1.0.0",
  "main": "server.js",
  "scripts": {
    "install": "npm install", 
    "dev": "nodemon server.js",
    "start": "node server.js"
  },
  "dependencies": {
    "cors": "^2.8.5",
    "dotenv": "^16.4.5",
    "express": "^4.19.2"
  },
  "devDependencies": {
    "nodemon": "^3.1.0"
  }
  }
   ```

- frontend `package.json` React / Vite
  ```json
  {
  "name": "my-frontend-app",
  "private": true,
  "version": "0.0.0",
  "type": "module",
  "scripts": {
    "dev": "vite",
    "build": "vite build",
    "start": "vite preview"
  }
  }
   ```
