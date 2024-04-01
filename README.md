# V2Ray Worker
 Total solution for v2ray configs over Cloudflare's worker

## Deploy 
 1. Fork this Repo and enable Github Action
 2. Open CloudFlare and create KV namespace with name `settings` then copy the ID
 3. Go to this forked repo and set secrets with name `KV_NAME` and fill with KV settings ID
 4. Edit this `README.md` file, then find and replace this button url bellow with yours `https://github.com/USER/REPO_NAME` then save it.
 5. then press `Deploy With Workers` and follow the instruction

[![Deploy to Cloudflare Workers](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/KevinWee/v2ray-worker)

### Credits
Built-in vless config generator is based on [Zizifn Edge Tunnel](https://github.com/zizifn/edgetunnel), re-written using Typescript.
Proxy IPs source: https://rentry.co/CF-proxyIP

### Copy Cloudflare Worker Account ID and API Token
Account ID is on Workers & Pages Overview right side, click hyperlink named "Manage API tokens" can create an API Token.
when API Token creating, choose template named "Edit Cloudflare Workers" and make some choice then Saved.
