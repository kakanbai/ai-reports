# AI Reports

面向投资与 AI 工具观察的公开报告库。站点默认发布到 <https://kakanbai.github.io/ai-reports/>；后续可在 GitHub Pages 设置中绑定 `report.915666888.xyz`。

## 报告目录

- `reports/a-share-morning/`：A 股早报
- `reports/a-share-review/`：A 股复盘
- `reports/github-ai/`：GitHub AI 工具与项目观察
- `reports/investment-watch/`：投资观察与跟踪清单

每份新报告建议使用 `YYYY-MM-DD.md` 命名，并从首页添加链接。

## 发布与通知

- 推送到 `main` 会更新 GitHub Pages。
- 推送到 `main` 或手动运行「飞书通知」工作流会尝试发送通知。请在仓库 Secrets 中设置 `FEISHU_WEBHOOK`；未设置时该工作流会安全跳过通知。

## 自定义域名（预留）

在 GitHub Pages 设置中填入 `report.915666888.xyz`，并在域名 DNS 中添加指向 `kakanbai.github.io` 的 CNAME 记录。绑定完成后，在仓库根目录新增 `CNAME` 文件，内容为该域名。
