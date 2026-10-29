# AAT 豪宅内容工作室

面向豪宅从业者与团队，在豆包工作里完成定位、选题、写稿、制作、归档和独立复盘。

## 安装 0.22.1 完整试用版

把下面整段发给豆包工作。会安装技能，复用或安装口播工作台，并准备本机媒体与中文配音环境；已有版本替换先由本人确认。

```text
请安装 AAT 豪宅内容工作室 0.22.1及配套口播工作台。只从以下固定版本获取文件，无需我手动下载或上传 ZIP：
https://github.com/Lucas-Zhang-JJ/aat-property-studio/releases/download/v0.22.1/install.sh
安装脚本 SHA256：ea13048d070cc8de569b559d76849c824557f5486ffcf18a5d1452921b9128b5
清单：https://github.com/Lucas-Zhang-JJ/aat-property-studio/releases/download/v0.22.1/install-manifest.json
清单 SHA256：9df53f00850fe884dbffe76c70b71b15abe9b529336d09a211912a8deb680d74

先读取你内置“创建技能”的指引，取得文档支持的、已经存在的 workspace/.user_skills 路径；不要搜索历史日志、私有配置、数据库或缓存来寻找注册接口。下载脚本到临时目录并核对上述SHA256，匹配后用 /bin/sh 执行，参数为 --manifest 清单URL --sha256 清单SHA256 --skill-root 实际技能根目录。安装器自动准备独立Node与锁定依赖，校验原始发布文件、自检并注册Skill；同时检查已登记工作台，有则复用，没有则下载固定版本并安装到本机用户目录，准备独立Python、FFmpeg/FFprobe、语音模型和渲染浏览器，自动连接并实际检查。同时准备已验收的Talking动画与MeloTTS中文女声，并实际合成短句验证；首次依赖下载约1GB，需预留约5GB空间；显示进度，不改系统Python、全局PATH或现有工程。当前工作台一体安装适配macOS14及以上Apple Silicon；其他系统报告支持状态，不猜路径或换不兼容包。若我明确提供已有工作台路径，传--workbench-root该路径，不全盘搜索；已登记目录失效先找回，不另建资料替代。不要自行生成或重写技能源码。
若发现旧版，先展示旧版与拟安装的0.22.1，再等待我明确同意替换，按当前指纹传--replace；保留回滚回执，不覆盖用户DATA、凭据或登录资料。登录/系统权限由我本人完成，不绕过。失败报告实际原因，保留现有版本，不反复重试。
完成后在新会话实际确认技能可发现，按安装回执中的node/cli路径运行doctor、model-stages、workbench-status、workbench-check和presenter-check。明确分别说明技能安装、工作台连接、转写/粗剪和实际渲染检查结果；缺依赖或端口冲突不能称可开始剪辑。先locate找旧资料，确无旧库才引导选择空目录初始化。默认使用豆包原生；运行model-profiles确认包内11个无密钥预设可见，不覆盖已有模型配置。若我要求换模型，展示实际文本、视觉、图片、转录模型和缺项，由我通过私有文件或环境变量补Key（不在聊天粘贴密钥）并选择，全链路统一使用，不静默回退豆包。不要替我发布内容、发消息或改定时。
```

## 本版能力

小红书图文、公众号文章、抖音短视频、播客各走独立流程，共用定位、个人口吻、房产知识、用户资产、对标、待写清单和复盘。短视频可选真人出镜、AAT动画讲解或已有视频加工。

AAT动画讲解按确认脚本生成固定Talking动画与免费本地MeloTTS中文女声，可试听、查看进度、中断后继续；原片送工作台加字幕、按需制作画面、预览、导出并归档。循环动嘴，非逐字口型，不是本人克隆。真人拍摄与其他录音仍由本人完成。

新装自动准备配套工作台与私有Python/FFmpeg、转写模型、中文配音模型、渲染浏览器；当前完整新装支持macOS14及以上Apple Silicon，首次依赖约1GB，建议预留5GB。已有工作台可复用，原工程和素材保留；实际检查失败会报告缺项，安装成功不等于内容已经验收。其他系统暂未完成完整安装验收。

工作台基于Overlay Studio并包含video-talkcraft组件，原许可与署名随包保留；维护者已确认本次修改版公开分发和商业使用均在其授权范围内。分发说明见工作台包内AAT-DISTRIBUTION-NOTICE.md，不移除原作者的许可。

模型预设有11个无Key方案，本人已有配置优先；文本、视觉、图片等AI阶段随本人选择的模型方案执行，缺能力不静默回退。资料、Key和登录留在本人电脑，云端模型仍会处理本次获准材料。小红书RPA须本人登录并逐篇授权，新增平台仍手动发布。

[下载与版本说明](https://github.com/Lucas-Zhang-JJ/aat-property-studio/releases/tag/v0.22.1) · [安装提示词文件](https://github.com/Lucas-Zhang-JJ/aat-property-studio/releases/download/v0.22.1/install-prompt.md)
