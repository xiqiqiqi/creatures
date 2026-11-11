# creatures.xiqiqi.com

奇兽 · 珍禽异兽

水怪、野人、海怪、神话生物、都市怪物。

## 配置

- channel: `creatures`
- domain: `creatures.xiqiqi.com`
- accent: `#6B7A4A`
- core: `^0.1.0`

## 部署

- 发布：GitHub Actions（`.github/workflows/deploy.yml`）
- 构建时检出 `oddities-core` 与 `oddities-and-mysteries`
- 自定义域名：见 `CNAME`，并在 Pages 设置中绑定
- 构建由 `oddities-core` 统一执行，本仓不写页面代码

## 目录

```text
site.config.ts   # 站点配置
CNAME            # 自定义域名
package.json     # core 版本
```

页面代码在 `oddities-core`，内容在 `oddities-and-mysteries`。