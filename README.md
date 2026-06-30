# etf-rotation-page

Gitee Pages 静态页面仓库。

用途：

- 前端展示 ETF 策略结果
- 通过浏览器请求腾讯云 SCF JSON 接口

页面文件：

- `index.html`

使用方式：

1. 部署 Gitee Pages
2. 打开页面
3. 输入你的 SCF 域名
4. 点击 `V7` / `V8`

接口要求：

- `/api/v7?mode=json`
- `/api/v8?mode=json`
- `/api/cache/refresh`
