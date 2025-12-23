## 认证方式：密码 (Password)

### 修改或重置密码

使用 Rescue CLI 来重置或修改密码：

```bash
docker exec -it remnawave remnawave
```

进入 Rescue CLI 后，选择 Reset superadmin（重置超级管理员）选项。
### 启用紧急密码认证

如果你禁用了“密码”认证方式，但随后失去了对其他认证方式（如 OAuth2）的访问权限，你可以通过 Rescue CLI 强制重新启用“密码”认证：

```bash
docker exec -it remnawave remnawave
```

进入 Rescue CLI 后，选择 Enable password authentication（启用密码认证）选项。
