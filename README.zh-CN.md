# FreeToken.link — 查找并验证免费大模型 API 路线

[English](README.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md)

[![FreeToken.link 产品概览](assets/freetoken-overview.png)](https://freetoken.link/zh)

**FreeToken.link 帮助开发者比较带日期的免费访问条件：查看官方 Key 申请路径、在支持的路线中从浏览器直接验证、生成不包含真实密钥的配置模板，并建立只关注重要变化的 Watchlist。**

访问中文站：**[freetoken.link/zh](https://freetoken.link/zh)**

> 这是公开的产品说明、发布资料和反馈仓库。这里不公开生产应用源码、供应商凭证、共享 Key、用户 Vault 数据或运营密钥。

## 为什么需要 FreeToken

普通“免费 AI API 列表”很容易过期。供应商可能随时调整绑卡要求、地区范围、额度、模型 ID 或申请流程，而营销页面仍然写着“免费”。

FreeToken 明确区分：

- 供应商官方文档说明了什么；
- 账号、地区和额度还可能受到什么限制；
- FreeToken 平台自有 Canary 实际观测过什么；
- 哪些路线仍然未知或尚未配置测试。

因此，“官网列为免费”不会被表述成“所有人此刻都一定可用”。

## 可以完成什么

| 任务 | 在线入口 |
| --- | --- |
| 用自然语言描述需要的 API | [按需求查找](https://freetoken.link/find) |
| 筛选已审查的模型和供应商 | [中文模型目录](https://freetoken.link/zh/models) |
| 查看官方 Key 申请步骤 | [申请 API Key](https://freetoken.link/zh/get-key) |
| 安全诊断已有 Key | [连接诊断](https://freetoken.link/doctor) |
| 从浏览器直接测试提示词 | [中文 Playground](https://freetoken.link/zh/playground) |
| 建立重要变化 Watchlist | [中文 Watchlist](https://freetoken.link/zh/watchlist) |
| 查看证据采集方式 | [来源覆盖](https://freetoken.link/sources) |
| 查看当前运行证据 | [状态页](https://freetoken.link/status) |

## 隐私和可信边界

- 在支持浏览器直连的检查中，API Key 和提示词从浏览器直接发送给所选供应商，不经过 FreeToken 的明文 Key 代理。
- 分享链接不会包含 API Key。
- 可选 Vault 同步只保存客户端加密后的密文，不保存口令或明文 Key。
- Watchlist 需要明确同意；未登录订阅必须通过邮件双重确认。
- FreeToken 不提供抓取、共享、转售或多人共用的 API Key。
- 社区目录只能提供发现线索，正式的访问条件必须有供应商官方来源支持。

详细说明见[验证方法](docs/VERIFICATION.md)和[隐私边界](docs/PRIVACY.md)。

## 纠错与反馈

如果发现模型 ID、额度、官方链接或免费条件已经变化：

1. 创建 **Source correction / 来源纠错** Issue；
2. 附上供应商官方来源和检查日期；
3. 不要提交 API Key、Token、包含个人信息的截图或私有响应。

证据要求见 [CONTRIBUTING.md](CONTRIBUTING.md)。

## 公开分发边界

主站 `https://freetoken.link/` 始终是产品和 SEO canonical。这个仓库用于开发者发现、透明说明、引用和反馈，不启用一个重复的 GitHub Pages 站点。

渠道发布资料见 [docs/LAUNCH-KIT.md](docs/LAUNCH-KIT.md)，多语言策略见 [docs/MULTILINGUAL.md](docs/MULTILINGUAL.md)。

FreeToken.link 为独立产品，与目录中列出的模型或 API 供应商不存在官方隶属或背书关系。
