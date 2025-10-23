KEYORA 招商落地页（GitHub Pages）
- 上传本目录所有文件到你的 GitHub 仓库根目录（例如 keyora-site）。
- Settings → Pages：Source 选 Deploy from a branch，分支 main，目录 /(root)。
- 自定义域名：在 Pages 的 Custom domain 输入你的 .com 域名并保存，然后到 DNS 服务商：
  - A 记录（@）指向 185.199.108.153 / 109.153 / 110.153 / 111.153
  - AAAA 记录（@）指向 2606:50c0:8000::153 / 8001::153 / 8002::153 / 8003::153
  - CNAME（www）指向 <你的用户名>.github.io
- 回到 Pages 勾选 Enforce HTTPS。 
