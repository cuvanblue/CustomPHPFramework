set NODE_ENV=development && cd ./socioboard-api/User && pm2 start user.server.js && cd ../Feeds && pm2 start feeds.server.js && cd ../Publish && pm2 start publish.server.js && cd ../Notification && pm2 start notify.server.js && cd ../Update && pm2 start update.server.js && pm2 status
