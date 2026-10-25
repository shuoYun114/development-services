# 烁云辉霞 · Android / Kotlin 项目排错

作者：烁云辉霞

承接范围明确的 Android / Kotlin 构建排错与小修复。先确认问题和验收条件，再确定价格与交付时间。

## 服务

| 项目 | 试行报价 | 交付 |
|---|---:|---|
| 单个构建问题诊断 | ¥199 | 诊断记录、复现情况和修复建议；不承诺所有问题均能修复 |
| 一个明确的小修复 | ¥499 起 | 约定范围的补丁、实际执行的验证说明；具备构建条件时提供安装包 |

这些是初始试行报价，最终范围与价格须双方书面确认。尚未提供付费客户案例或收入证明。

## 项目案例：腕上书笺

手机导入 TXT，通过安全 RFCOMM 蓝牙向 OPPO Watch X2 发送文档，两端本地保存与阅读。

- Kotlin / Jetpack Compose；手机与手表独立应用。
- UTF-8、UTF-16、GB18030 编码处理，大小限制和 SHA-256 校验。
- SQLite 事务保存；接收方保存后发送确认。
- 各端独立保存阅读位置与字号。

截至 2026-10-25，项目本地验证记录显示：手机和手表 Debug APK 已构建安装，核心单元测试、蓝牙真机传输及两端 Lint 已通过。本接单仓库不包含源码或设备日志。

**验证边界：**真机仅覆盖记录中的 OPPO Watch X2（OWW251，API 30）与 PLK110 手机（API 37）；完整断网后重启阅读验收尚未完成；尚未完成正式发布签名或商店上架。其他机型兼容性不作保证。

## 提交需求

在本仓库新建 [Issue](../../issues/new/choose)，提供：

1. 期望结果、实际结果和最小复现步骤。
2. 脱敏错误日志、Android / Gradle / Kotlin 版本。
3. 预算、期望时间及源码能否提供。

公开 Issue 只提交可公开的信息。不要上传密码、API 密钥、签名文件、客户数据、设备序列号或私有源码；如需私密材料，先约定合适渠道。

## 合作流程

确认可复现问题 → 书面约定范围、报价、时间、验收与付款方式 → 实现及验证 → 交付验收。

默认报价不包含新功能、额外机型适配、长期维护或商店审核。约定范围内包含一次修订，新增范围另行确认。付款、取消与未能交付时的处理方式，在开工前约定。

开发可使用 AI 辅助；只报告实际完成的工作与执行过的验证。需要客户本人审阅、操作或签署的步骤会明确列出。

## English

Android / Kotlin build diagnostics and small, clearly scoped fixes. Initial diagnostic price: CNY 199; small fixes: from CNY 499. Scope, acceptance criteria, schedule and payment terms must be agreed before work starts. AI-assisted development is disclosed; only executed validation is reported. Open an issue with a sanitized reproduction. Never post credentials or private source code.
