## Route

```
GET /?u={encrypted_url}
```

## Scripts

```bash
# Encrypt a URL (Node.js) for testing purpose
node scripts/enc.js "https://example.com/video.m3u8"
```


## credits
shoutout to the following repos which provided inspiration and foundational logic:
- [zuhaz/rust-proxy](https://github.com/zuhaz/rust-proxy)
- [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere)
- [Eltik/M3U8-Proxy](https://github.com/Eltik/M3U8-Proxy)
- [Chance](https://github.com/Gratenes/m3u8CloudflareWorkerProxy)