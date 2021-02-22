### 配置使用

新建一个 `cloudflare worker`, 把此项目下 `cf-worker/index.js` 拷上去. 然后就能通过 worker 给的链接(可自定义)访问到你的服务. 如果你想像我一样自定义界面, 可以 fork 后更改, 部署到 github page 或 vercel 然后改 worker 里的`ASSET_URL`指向自己的部署.