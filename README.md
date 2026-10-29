# AAT 豪宅内容工作室

面向豪宅从业者与团队，在豆包工作里完成定位、选题、写稿、制作安排、成品归档和复盘。

## 安装 0.22.0 试用版

把下面整段发给豆包工作。已有资料和Key保留，旧版替换先由本人确认。

```text
请安装 AAT 豪宅内容工作室 0.22.0 公开试用版。本次只安装技能，不下载或安装口播工作台源码，也不把缺少的配套环境说成就绪。

固定安装脚本：https://github.com/Lucas-Zhang-JJ/aat-property-studio/releases/download/v0.22.0/install.sh
脚本 SHA256：568f2f1939637bb4cba557e37cb38c77e90a1a6a3f9a7b731a978ffcdc8ace03
固定清单：https://github.com/Lucas-Zhang-JJ/aat-property-studio/releases/download/v0.22.0/install-manifest.json
清单 SHA256：3ffc9395e02b4085c96b4fd8acd72681ff5830e6b5af8a81376b0b14ca0a0ae9

先读取内置“创建技能”指引，取得文档支持且已存在的workspace/.user_skills。下载脚本至临时目录，SHA256匹配后用/bin/sh执行，参数为 --manifest 上述清单URL --sha256 上述清单SHA256 --skill-root 实际技能根目录。安装器准备独立Node和锁定依赖、自检并原样注册Skill；不要重写源码、搜索历史日志或修改私有数据库。发现旧版，展示差异并等待本人同意替换后传--replace当前指纹，保留备份和回滚回执，保护已有DATA、模型Key和登录资料。失败说明实际原因，不能反复自动重试。

完成后在新会话确认能发现技能，从.aat-install.json取实际Node/CLI，调用doctor和video-production-options。配套工作台需使用者自行合法安装；如果已经有，复用原登记，再运行workbench-status、workbench-check及presenter-check分别说明实际状态。没有工作台或配音环境时，先报告缺项，不从非授权链接下载源码，不声称一体安装完成。普通定位、选题、写稿和其他现有内容流程仍可继续。已有本机配套环境的用户可以继续动画生成和剪辑。

先locate找旧资料，确无旧库才引导在空目录初始化。默认豆包原生，模型Key仅本人私有配置；切换模型由本人明确选择，不静默回退。不要发布内容、发消息或改定时。macOS已验证，Windows仍未验收。
```

## 这版有什么

支持小红书图文、公众号文章、抖音短视频、播客的独立流程，以及用户口吻、房产知识、个人资产、对标、待写清单和独立复盘。短视频有真人出镜、AAT动画讲解、已有视频加工三种方式。

已配置配套环境时，动画讲解沿用固定Talking形象及免费本地MeloTTS中文女声，可试听、查看进度、中断后继续、送工作台加字幕及剪辑，再预览归档。动画循环动嘴，非逐字口型，不支持本人克隆。

**本次公开发布只包含AAT技能。口播工作台及媒体/配音环境不包含在公开下载中，首次安装不会自动获得这部分能力。**工作台含独立第三方许可，待授权范围确认后再提供单独分发；已有合法安装可继续连接。技术验证包括253项检查、隔离真实视频完整链路，以及正式豆包新会话版本/能力读回；不能替代使用者内容验收。

模型预设含11个无Key方案，本人已有配置优先，补Key后需实际验证权限与能力。用户资料、Key与平台登录不随包上传；云端模型仍会处理本次获准材料。小红书RPA须本人登录并逐篇授权，其他新增平台仍手动发布。

[下载及版本说明](https://github.com/Lucas-Zhang-JJ/aat-property-studio/releases/tag/v0.22.0) · [安装提示词文件](https://github.com/Lucas-Zhang-JJ/aat-property-studio/releases/download/v0.22.0/install-prompt.md)
