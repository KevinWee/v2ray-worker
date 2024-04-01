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

### 复制 Cloudflare Worker 的 Account ID 和 API Token
Account ID是Worker首页上右侧的Account ID, API Token 可以在第二次点击后创建。
创建的时候确认权限为“Edit Cloudflare Workers”，里面只有两个必填项，我都选择了全部。
