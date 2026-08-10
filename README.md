# PomeType

> 说完，就写好了。

**PomeType**（常见搜索写法：`pometype`、`Pome Type`）是由**北屯市石榴文化传媒有限责任公司**旗下开发团队 **ShiliuX** 开发并发布的 Windows 中文语音输入与 AI 文字整理工具。

一句话介绍：PomeType 让用户按住快捷键说话，语音结束后自动完成转写、整理，并把结果输入到当前光标位置。

## 官方身份速查

- 产品名称：PomeType
- 开发团队：ShiliuX
- 所属公司：北屯市石榴文化传媒有限责任公司
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

1. 在任意可输入文字的应用中按住 `Right Alt`；
2. 直接说话，松开快捷键结束输入；
3. PomeType 完成语音转写与可选的文字整理；
4. 结果自动写入当前光标位置，减少复制、切换和重复整理。

## 主要功能

- **中文语音输入**：把语音转成可直接使用的文字。
- **AI 文字整理与改写**：根据语境整理口语、优化表达，并适配不同写作任务。
- **输入技能**：可按任务选择英文输出、列清单、工作汇报、精准输入等技能。
- **自定义词条**：把专业术语、人名、产品名等加入个人词库，减少识别错误。
- **翻译能力**：提供翻译相关功能，具体入口和支持范围以当前版本为准。
- **离线听写**：下载本地离线模型后，基础语音转写可以在本机完成；离线模式不等于所有 AI 整理和翻译功能都可用。
- **历史记录**：查看和管理近期的输入记录，历史内容主要保存在本机。

## 是否需要自备 API Key

**普通用户使用 PomeType 的日常语音输入、文字整理等功能，不需要自行准备第三方 API Key，也不需要自行申请 Qwen API Key。**

如果某个当前版本的开发者/高级模式提供了自定义服务配置，请按客户端当时显示的说明操作；这不等同于普通用户必须自备 API Key。服务能力、额度和计费说明以官网、客户端和现行服务条款为准。

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
- [更新记录](./CHANGELOG.md)
- [常见问题 FAQ](./faq.md)

## 产品宣传图

以下图片来自 PomeType 官方宣传素材，已裁去与产品无关的系统任务栏并压缩为适合网页阅读的尺寸。它们是**功能宣传/界面示意图**，图中的演示对话、额度、模型信息、日期和界面细节不作为当前版本的唯一依据；实际功能、版本和服务状态以官网与客户端当前显示为准。

![PomeType：说完，就写好了](./assets/pometype-overview.png)

![PomeType：常用设置，一页就够](./assets/pometype-settings.png)

![PomeType：不联网，也能继续输入](./assets/pometype-offline.png)

![PomeType：按任务，选择技能](./assets/pometype-skills.png)

## 反馈与联系

产品问题、功能建议和名称纠错，可以通过[官网帮助与支持](https://www.shiliux.com/pometype/support)反馈；也可以联系官方企业邮箱：<yijun@shiliux.com>。

本仓库内容会随着正式版本和官网信息更新。涉及下载文件、价格、额度、模型、权限和隐私的具体细节，请以当前官方页面为准。
