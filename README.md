## Lavalink File (application.yml)
#### Paste this inside your application.yml file:
```js
lavalink:
  server:
    bufferDurationMs: 400
    gc-warnings: true
    password: dottosimp
    playerUpdateInterval: 5
    soundcloudSearchEnabled: true
    sources:
      bandcamp: true
      http: true
      local: false
      soundcloud: true
      twitch: true
      vimeo: true
      youtube: true
    youtubePlaylistLoadLimit: 3
    youtubeSearchEnabled: true
logging:
  file:
    max-history: 10
    max-size: 1GB
  level:
    lavalink: INFO
    root: INFO
  path: ./logs/
metrics:
  prometheus:
    enabled: false
    endpoint: /metrics
sentry:
  dsn: ""
  environment: ""
server:
  address: 0.0.0.0
  port: <your port>
```
> Change **\<your port\>** to your server's port*.


## Where's the port?*
![Port of your Server](https://media.discordapp.net/attachments/898041892279836692/898586887218954320/1634310136.jpg) 
