# 🚀 JustRunMy 自动续期（GitHub Actions）

这是一个基于 GitHub Actions 的自动化脚本，用于定时登录并自动续期 JustRunMy 应用。

为了保护账号和代理安全，所有敏感信息均通过 GitHub Secrets 进行配置。

━━━━━━━━━━━━━━━━━━━━━━

🔐 Secrets 配置说明

| Secret 名称         | 是否必填 | 说明                                        |
|---------------------|----------|---------------------------------------------|
| JUSTRUNMY_EMAIL     | ✅ 必填  | JustRunMy 登录邮箱                          |
| JUSTRUNMY_PASSWORD  | ✅ 必填  | JustRunMy 登录密码                          |
| GOST_PROXY_TARGET   | ✅ 必填  | Gost 代理完整地址（需包含协议，如 socks5://） |

━━━━━━━━━━━━━━━━━━━━━━

📌 示例填写格式（复制下面三行，分开添加）：

JUSTRUNMY_EMAIL=abc@def.com  
JUSTRUNMY_PASSWORD=abc123  
GOST_PROXY_TARGET=socks5://user:pass@123.456.789.012:1080

━━━━━━━━━━━━━━━━━━━━━━

📍 添加路径（如何添加 Secrets）：

1. 进入你的 GitHub 仓库  
2. 点击顶部的「Settings」  
3. 左侧菜单选择「Secrets and variables」 → 「Actions」  
4. 点击绿色的「New repository secret」按钮  
5. 分别添加上面的三个变量名称与对应值

━━━━━━━━━━━━━━━━━━━━━━

⚠️ 注意事项：

- Secrets 是私密的，不会显示在代码中
- 三个变量都为 **必填项**
- 不要把变量值写入到代码文件中
