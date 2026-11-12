# TVBox 点播源模板

这是一个用于 TVBox 的 JSON 配置起步模板，仅预留了一个授权点播 API 接口。仓库目前没有提供影视 API 或内容授权信息，因此模板中的 `https://example.com/api.php/provide/vod/` 是占位地址，不能直接使用。

## 配置

1. 将 `tvbox.json` 中的 `api` 替换为你拥有使用权的点播 API 地址。
2. 确认该接口提供 TVBox/苹果 CMS 兼容的 JSON VOD API；不同服务可能需要调整 `type`、接口路径或请求参数。
3. 将 `tvbox.json` 托管到你自己的 HTTPS 静态站点，并在 TVBox 中添加该文件的链接。
4. 只接入你拥有或获准分发的内容与接口。

如果你提供已获授权的 API 地址及其接口类型，我可以继续帮你适配配置并检查结构。
