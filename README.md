# PhraseFrame

<img src="assets/brand-mark.png" alt="PhraseFrame" width="88">

[English](README.en.md) · [下载最新 Windows Beta](../../releases)

PhraseFrame 是一个本地优先的 Windows 桌面语言笔记工具。它将
多标签文字/媒体卡片、模块化富文本编辑、评论与笔记、本地全文搜索和可恢复
回收站放在一个不要求云账户的工作区中。

![PhraseFrame 应用界面](assets/app-overview.png)

## 下载

从 [GitHub Releases](../../releases) 下载最新预发布版本：

- 普通用户优先使用 NSIS `Setup.exe`。
- MSI 用于管理员或受管部署。
- 使用同一 Release 中的 `SHA256SUMS.txt` 校验下载文件。

当前 Beta 尚未进行代码签名，Windows SmartScreen 可能显示“未知发布者”。
请确认下载来自本仓库并核对 SHA-256。

## 数据与隐私

- 用户自行选择本地工作区，正文不依赖云账户。
- 应用不包含遥测、广告分析或应用自营云同步。
- 搜索索引可以从工作区文件重建。
- 卸载应用不会删除用户自行选择的工作区。

完整说明见 [隐私说明](PRIVACY.md)。

## 已知限制

- 当前只支持并验证 Windows x64。
- 不要同时运行多个实例编辑同一工作区。
- 外部媒体引用依赖原文件路径，移动文件后需要重新定位。
- Beta 可能包含缺陷；重要工作区应保持独立备份。

## 反馈

请通过 [Issues](../../issues) 报告问题或提出建议。不要上传含私人笔记、真实
媒体或个人路径的完整工作区。安全问题请按照 [安全政策](SECURITY.md) 私下报告。

## 许可

PhraseFrame Free Beta 是专有软件，免费不等于开源。安装或使用即
表示接受 [免费 Beta 最终用户许可协议](EULA.txt)。本仓库不分发应用源代码。

Copyright © 2026 PhraseFrame. All rights reserved.
