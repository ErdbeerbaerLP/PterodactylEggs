Fosscord
===
An open source discord server. https://fosscord.com/

How to install
---
- Import egg into pterodactyl
- Create server and wait for installation to Finish
  - Assign ports 3001, 3002, 3003, 3004 and 3005 to the Server
  - Assign at minimum 512MB storage (mind that by default config, you need more storage for CDN files)
- Create database for Fosscord
- Set the database uri in the Startup tab of the server
- Start the server. It should be reachable under IP-ADDRESS:3001 then
- Configure the fosscord server by editing the config table in the database, check fosscord documentation for more information