## OAuth2: GitHub

### 创建 OAuth 应用
首先，你需要创建一个 OAuth 应用。 点击以下链接开始创建：https://github.com/settings/applications/new

在 Authorization callback URL（授权回调地址）字段中，输入你面板的访问地址。

```bash
# 请将 YOUR_PANEL_DOMAIN 替换为你面板的实际地址
https://YOUR_PANEL_DOMAIN/oauth2/callback/github
```

请务必记得将 YOUR_PANEL_DOMAIN 替换为正确的面板地址。

### Remnawave 中的 OAuth2 设置

创建好 OAuth2 应用后，请复制 Client ID 和 Client Secret。将这些数据填入对应的配置区域。随后在下方输入允许登录的邮箱地址列表。
