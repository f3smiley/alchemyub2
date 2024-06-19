Shared Dependencies:

1. Environment Variables:
   - `ALCHEMY_API_KEY`
   - `PORT`
   - `NODE_ENV`

2. Node.js Packages:
   - `express`
   - `body-parser`
   - `alchemy-sdk`
   - `dotenv`

3. File Paths:
   - `/home/ubuntu/API_Server_Setup/server.js`
   - `/home/ubuntu/API_Server_Setup/.env`
   - `/etc/systemd/system/api-server.service`

4. Systemd Service Configuration:
   - `api-server.service`

5. NPM Scripts:
   - `start` (implicitly used when running `npm start`)

6. Express.js Server Configuration:
   - `app` (instance of express)
   - `PORT` (for the server to listen on)

7. Alchemy SDK Configuration:
   - `settings` (configuration object for Alchemy SDK)
   - `alchemy` (instance of Alchemy SDK)

8. API Endpoints:
   - `'/'` (root endpoint)
   - `'/block'` (blockchain interaction endpoint)

9. Console Log Messages:
   - `Server running on port ${PORT}` (server start message)

10. Systemd Service Properties:
    - `Description`
    - `ExecStart`
    - `WorkingDirectory`
    - `User`
    - `Group`
    - `Environment`
    - `EnvironmentFile`

11. UFW Configuration Commands:
    - `ufw allow ssh`
    - `ufw allow http`
    - `ufw allow 3000/tcp`