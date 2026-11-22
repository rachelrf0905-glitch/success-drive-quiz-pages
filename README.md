# 测试网页 GitHub Pages 前端

此目录用于 GitHub Pages 静态托管。入口通过固定访问码解锁本页测验；不依赖动态验证码、数据库或 Worker API。

## 发布设置

- 在仓库 Settings → Pages 中选择 GitHub Actions，或从 main 分支根目录发布。
- 自定义域名：`quiz001.aitestemotion.top`
- DNS：将 `quiz001` 的 CNAME 指向 `rachelrf0905-glitch.github.io`

## 访问码说明

固定码校验在浏览器中执行，属于轻量页面门槛，不是安全认证。静态站点的访客可查看网页源码并绕过校验；请勿用它保护敏感内容。
