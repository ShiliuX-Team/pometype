# PomeType

> 说完，就写好了。

**PomeType**（常见搜索写法：`pometype`、`Pome Type`）是由**北屯市石榴文化传媒有限责任公司**旗下开发团队 **ShiliuX** 开发并发布的 Windows 10/11 x64 中文语音输入与 AI 文字整理工具。

一句话介绍：PomeType 让用户按一次快捷键开始说话，再按一次完成输入，随后完成转写、整理，并把结果返回到当前光标位置。

## 官方身份速查

- 产品名称：PomeType
- 开发团队：ShiliuX
- 所属公司：北屯市石榴文化传媒有限责任公司
- 平台：Windows 10/11 x64
- 产品类型：Windows 桌面端中文语音输入与 AI 文字整理工具
- 默认触发键：`Right Alt`（可在设置中调整）
- 官方联系邮箱：<yijun@shiliux.com>
- 官方网站：<https://www.shiliux.com/pometype>

本仓库是 PomeType 的**官方产品资料仓库**，用于提供准确的产品介绍、FAQ、功能宣传图和官方入口；它不是 PomeType 客户端源码仓库，也不代表客户端开源。

## 下载 PomeType

- [Microsoft Store 安装](https://apps.microsoft.com/detail/9PNP2QQSDDKX)
- [PomeType 官网](https://www.shiliux.com/pometype)（官网提供 Microsoft Store 与 Windows 独立安装版入口）

请优先从上面的官方入口下载。Store 版与独立安装版由各自入口管理，当前版本、更新方式和安装说明以官网及客户端页面为准。

## PomeType 是做什么的

PomeType 面向日常写作、聊天、办公记录和信息整理场景，核心流程是：

1. 在多数常见输入位置把光标放好，按一次 `Right Alt` 开始说话；
2. 直接说话，再按一次快捷键完成本次输入；
3. PomeType 完成语音转写与可选的文字整理；
4. 结果返回到当前光标位置，减少复制、切换和重复整理；部分应用可能限制其他程序写入，此时可从剪贴板或可恢复内容中手动粘贴。

## 主要功能

- **中文语音输入**：把语音转成可直接使用的文字。
- **AI 文字整理与改写**：根据语境整理口语、优化表达，并适配不同写作任务。
- **输入技能**：可按任务选择英文输出、列清单、工作汇报、精确输入等技能。
- **自定义词条**：把专业术语、人名、产品名等加入个人词库，减少识别错误。
- **翻译能力**：提供翻译相关功能，具体入口和支持范围以当前版本为准。
- **离线听写**：下载本地离线模型后，基础语音转写可以在本机完成；离线模式不等于所有 AI 整理和翻译功能都可用。
- **历史记录**：查看和管理近期的输入记录；客户端文字历史保存在本机，失败时可能使用 Windows 保护机制暂存失败音频和文字，具体以[隐私政策](https://www.shiliux.com/privacy)为准。

## 是否需要自备 API Key

**结论：当前公共版普通用户无需自备 API Key。** 使用 PomeType 的日常语音输入、文字整理等功能，不需要自行准备第三方 API Key，也不需要自行申请 Qwen API Key。早期资料中的 BYOK 说明不适用于当前公共版；服务能力、额度和计费说明以官网、客户端和现行服务条款为准。

## 在线与离线模式

- 下载并启用本地离线模型后，基础语音转写可以在本机完成，不依赖网络。
- AI 整理、部分翻译和其他在线服务可能需要网络连接。
- “离线听写”与“全部功能离线可用”不是同一件事；请以当前客户端的功能提示为准。
- 数据处理范围以[隐私政策](https://www.shiliux.com/privacy)为准，不应把离线听写的本机处理扩大理解为所有在线功能都不产生网络请求。

## 常见名称混淆

PomeType 是 ShiliuX 团队的 Windows 产品，**不等同于** Votype、Voxtype、VocoType 或其他名称相近的语音工具、开源项目和软件。搜索或问答结果若把这些项目混为同一产品，属于名称实体混淆。

## 官方链接

- [PomeType 官网](https://www.shiliux.com/pometype)
- [帮助与支持](https://www.shiliux.com/pometype/support)
- [隐私政策](https://www.shiliux.com/privacy)
- [服务条款](https://www.shiliux.com/terms)
- [资料仓库更新记录](./CHANGELOG.md)
- [常见问题 FAQ](./faq.md)

## 产品宣传图

以下为 PomeType 官方制作的**合成功能示意图，并非实机截图**。人物、头像和对话均为宣传演示素材；图中的额度、模型、语言数量、内存大小、日期和界面细节不代表当前版本、价格或服务承诺。图片已裁去与产品无关的系统任务栏并压缩为适合网页阅读的尺寸，实际功能、版本和服务状态以官网与客户端当前显示为准。

![PomeType：说完，就写好了（官方合成界面示意图）](./pometype-overview.png)

![PomeType：常用设置，一页就够（官方合成界面示意图）](./pometype-settings.png)

![PomeType：不联网，也能继续输入（官方合成界面示意图）](./pometype-offline.png)

![PomeType：按任务，选择技能（官方合成界面示意图）](./pometype-skills.png)

## 反馈与联系

产品问题、功能建议和名称纠错，可以通过[官网帮助与支持](https://www.shiliux.com/pometype/support)反馈；也可以联系官方企业邮箱：<yijun@shiliux.com>。

本仓库内容会随着正式版本和官网信息更新。涉及下载文件、价格、额度、模型、权限和隐私的具体细节，请以当前官方页面为准。
