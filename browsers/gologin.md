# GoLogin 怎么收费？免费版、云端启动与 API 限制

[返回产品总览](../README.md) · 核验日期：2026-10-27

GoLogin 的选择重点在于环境保存、跨设备使用和云端运行方式。个人在自己的电脑上使用几个固定环境，与团队在云端打开环境、分享资料和接入程序，对应的套餐条件差别较大。

## 免费 3 个环境，还有每月创建次数

官方 [Pricing 帮助文档](https://support.gologin.com/en/articles/14617029-pricing)把免费档分成两个额度：账号内同时保留最多 3 个环境，每自然月最多新建 25 个。删除环境不会返还创建次数，额度在每月 1 日 UTC 00:00 重置。

三个固定账号长期重复使用，与每天创建新环境是不同需求。前者主要受保存名额影响，后者会消耗月度创建额度；如果已经创建了 25 次，即使删到只剩一个，也不能靠腾出保存空间继续无限新建。

## 云端使用和导出功能，要看付费档

上述帮助文档列出的免费档限制包括：不能添加团队成员、分享环境、导出 Cookie、批量创建、在云端启动环境或调用 API。免费档适合个人在本地轻量使用；需要这些工作流时，应把付费方案放入预算。

Professional 提供 10、50、100 个环境等选择，公开月付起价为 9 美元。该帮助文档注明新价格适用于 2026 年 1 月起注册的账号，老账号切换需联系支持。本文保留月付口径；年付折算数字应与一次实际付款的周期一起查看。[当前价格页](https://gologin.com/pricing/)

## 桌面客户端、云浏览器和移动端怎样选

[系统要求文档](https://support.gologin.com/en/articles/3452486-supported-platforms-installation)列出 Windows、macOS、Ubuntu/Mint，并另列 Android 和 iOS 的要求。下载前应按所用设备进入对应入口，桌面客户端和移动端的使用流程需要分别安排。

如果工作主要发生在自己的电脑上，先比较本地环境的保存和启动体验。经常需要从其他设备进入工作环境，才进一步评估云端运行的可用时长、同时运行数和分享权限，避免购买暂时用不到的资源。

## 已有脚本，怎样评估 API 接入

GoLogin 的 [API Quickstart](https://gologin.com/docs/api-reference/introduction/quickstart)提供 API 客户端与调用示例，API key 从账号设置的 API 区域取得。接口适合把创建、运行环境等动作接入已有程序。

免费档不开放 API，开发任务需要从对应付费计划安排。比较时应同时记录接口权限和环境名额，不能因为产品有 API 文档，就把免费版也当成完整开发环境。

## 与其他产品比较时，哪些条件更重要

只需要本地保存几个账号时，可同时比较[比特浏览器](bitbrowser.md)的免费环境和 [MoreLogin](morelogin.md)的双用户方案。如果明确需要 GoLogin 的跨设备或云端工作流，再按并发会话和使用时长选择付费档。

[比特浏览器与 GoLogin 对比](../comparisons/bitbrowser-vs-gologin.md)按本地账号管理和云端任务分别讨论，两类需求的费用不能只用一个最低月费概括。

官方入口：[官网](https://gologin.com/) · [价格](https://gologin.com/pricing/) · [免费档限制](https://support.gologin.com/en/articles/14617029-pricing)
