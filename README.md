# 🚀 JustRunMy 自动续期（GitHub Actions）

这是一个基于 GitHub Actions 的自动化脚本，用于定时登录并自动续期 JustRunMy 应用。

━━━━━━━━━━━━━━━━━━━━━━

🔐 Secrets 配置说明

| Secret 名称         | 是否必填 | 说明                                              |
|---------------------|----------|---------------------------------------------------|
| JUSTRUNMY_ACCOUNT     | ✅ 必填  | your@email.com,yourpassword                                |
| PRIVATE_REPO_TOKEN  | ✅ 必填  | github_pat_xxxxxx                                |
| GOST_PROXY   | ❌ 可选  | Gost 代理完整地址（需包含协议，如 socks5://）     |
| TG_BOT        | ❌ 可选  | chat_id,bot_token（可选）                |

━━━━━━━━━━━━━━━━━━━━━━
