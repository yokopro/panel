## Telegram OAuth2

要配置“通过 Telegram 登录”功能，你需要一个 Telegram 机器人（Bot）。此外，你还需要对该机器人进行特定配置，以确保功能正常运行。
### 机器人配置

1. 打开 @BotFather (https://t.me/botfather)

2. 发送 `/mybots` 命令并选择所需的机器人。

3. 选择 `Bot settings` → `Domain`

4. 选择 `Set domain`

    向机器人发送一条包含访问 Remnawave 所用域名的消息：

    ```
    https://panel.domain.com
    ```

### 访问权限配置

在输入机器人 Token 后，你需要指定允许登录的管理员 ID 列表。
1. 使用需要授权的账号启动此机器人： – https://t.me/Get_myidrobot
2. 该机器人会回复你的 ID，请将其输入到对应的配置字段中。

---

### 常见错误解决方法

###### 错误：BOT_DOMAIN_INVALID

此错误是由于机器人域名配置不正确引起的。请重新查看上方的“机器人配置”章节，如有必要，请重新执行该步骤。

###### 错误：登录时未收到 Telegram 确认码
另一种方案： 你可以尝试先在 Telegram 的“官方”资源，例如（https://fragment.com ） 上进行登录。
由于浏览器内的 Telegram 会话（Session）是共享的，之后你可以再次尝试登录面板。
