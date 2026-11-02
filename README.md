# 工作搭子

个人工作管理网页：项目接续卡片、快速记录、待办、预期/实际时间线、想法停车场。

- 网页：https://daisyliu-s.github.io/gongzuodazi/
- 网页托管：GitHub Pages（改动推到 `main` 分支后约 1 分钟自动生效）
- 数据和登录：Firebase（Firestore + Authentication，项目 `gongzuodazi`）

## Firebase 控制台需要设置的
1. Authentication → 登录方法 → 启用「Google」（以及备用的「电子邮件/密码」）
2. Authentication → 设置 → 已获授权的网域 → 添加 `daisyliu-s.github.io`
3. Firestore → 规则 → 粘贴 `firestore.rules` 的内容 → 发布

## 备份
网页里「设置 → 导出备份」可以下载全部数据（JSON）。
