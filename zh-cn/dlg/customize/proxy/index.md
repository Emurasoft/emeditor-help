# “网络代理”页面

**网络代理**页面允许您自定义与代理连接相关的设置。EmEditor 将使用此页面上的代理服务器设置通过 HTTP 和 HTTPS 连接到 `support.emeditor.org`，如果使用 AI 功能，它将使用代理服务器设置连接到 `api.openai.com`。

## “无代理”单选按钮

在不指定代理服务器设置的情况下连接到互联网。如果您不使用代理服务器或已[在 Windows 中使用代理服务器](https://support.microsoft.com/zh-cn/windows/use-a-proxy-server-in-windows-03096c53-0554-4ffe-b6ab-8b1deee8dae1#ID0EFD=Windows_11)，请使用此设置。

## “手动代理配置”单选按钮

选中以启用以下自定义代理设置。

### “协议”下拉列表框

选择 HTTP 或 SOCKS5 协议以连接到您的代理服务器。

### 主机名

指定您的代理的主机名或 IP 地址。

### 端口号

指定您的代理服务器的端口号。

### 代理认证

如果您的代理服务器需要用户名和密码才能连接，请启用此选项。

### 用户名

指定用于连接的用户名。

### 密码

指定用于连接的密码。您可以点击 o-o 显示或隐藏密码。用户名和密码将存储在您的计算机上。

### 代理网址

此字段显示对上面指定的所有设置进行编码的 URL。您可以点击 o-o 显示或隐藏 URL。EmEditor 将使用此 URL 连接到代理。

## “检查连接”按钮

点击此按钮以使用上述指定的设置测试与 `support.emeditor.org` 的连接。如果连接成功，此按钮左侧将显示“☑ 连接成功！”。

如果不成功，将出现错误消息以诊断问题。请仔细检查代理服务器的设置并确保代理可访问。

## “重置”按钮

重置为默认设置。