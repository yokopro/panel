## OAuth2: PocketID

### 创建 OIDC 客户端

登录 PocketID 管理面板并导航至：Settings（设置） → OIDC Clients（OIDC 客户端） → Add OIDC Client（添加 OIDC 客户端）。

```
# 请将 YOUR_PANEL_DOMAIN 替换为您 Remnawave 面板的实际地址
https://YOUR_PANEL_DOMAIN/oauth2/callback/pocketid
```

### Remnawave 中的 OAuth2 设置

创建好 OIDC 客户端后，复制 Client ID 和 Client Secret 并填入对应区域。在下方输入允许登录的邮箱地址列表。 

在 Plain Domain（纯域名）字段中，输入 PocketID 所在的域名。只需输入域名即可——不要包含路径和 https://，例如：pocketid.your-domain.com。

### 自定义声明 / Custom Claims (v2.4.0+)

Remnawave 还支持通过 Custom Claims 进行授权。
使用此方法时，您无需手动指定邮箱地址列表。

Key(键)

```
remnawaveAccess
```

Value(值)

```
true
```

相应地，如果用户的 Token 中包含此键值对（remnawaveAccess: true），他们将被允许登录。
