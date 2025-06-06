<div align="center">

<h1 align="center">🧀 GoAmzAI = GO Amazing AI</h1>

全新精美的个人、团队、企业私有化AIGC平台

</div>

## 介绍
**介绍必看：** 产品说明、演示站、截图等相关内容请 [🧀 进入产品介绍](https://ipdj3sibjm.feishu.cn/docx/ARgjdOpTcohy2txfcPbclVbvnOf) 查看，本仓库仅含有基本介绍，且下述介绍内容可能不是最新内容，最新内容请均以此[🧀 产品介绍链接](https://ipdj3sibjm.feishu.cn/docx/ARgjdOpTcohy2txfcPbclVbvnOf)为准。

## 演示站点
- [🌍 Plus版演示站](https://demo6.goamzai.com)
- [🌍 Pro版演示站](https://prodemo6.goamzai.com)

## 技术架构
- 前端：Vue3 + NaiveUI
- 后端：Golang + Gin
- 数据支持：MySQL5.7 + Redis

## 扫码获取
### 微信扫码
> 备注：AIGC咨询

<img src='./images/wechat.png' width='180' alt='微信二维码'/>

### QQ扫码
> 备注：AIGC咨询

<img src='./images/qq.png' width='180' alt='QQ二维码'/>

## 你需要准备
- 域名
- 服务器：最低1C1G（CPU 1核心 + 1G内存）即可支持
- 对话模型平台API密钥（可选，如果你要使用对话功能） 
- 绘画平台订阅账户（可选，如果你要使用绘画功能）
- 其他模块（依据自己想法开启与否决定是否准备）：例如短信、邮件、内容审核平台等等

## 特性功能
> 以下功能列表可能并非实时最新的，最新内容请均以此 [🧀 产品介绍链接](https://ipdj3sibjm.feishu.cn/docx/ARgjdOpTcohy2txfcPbclVbvnOf) 为准。

| 功能 | 功能说明 | Plus版 | Pro版 | 企业版 |
|------|----------|--------|--------|--------|
| 🚀 极速部署 | 宝塔5分钟部署完成，低内存高并发，基础使用内存占用不到100MB | ✅ | ✅ | ✅ |
| ⚙️ 简单配置 | 配置文件仅需数据库配置即可启动 | ✅ | ✅ | ✅ |
| 🎛️ 在线配置框架 | 95%数据都可以后台在线统一管理 | ✅ | ✅ | ✅ |
| 📱 自适应布局 | 支持手机、平板、电脑等多种尺寸设备的浏览器在线访问 | ✅ | ✅ | ✅ |
| 🤖 对话多模型支持 | ChatGPT + Azure OpenAI + 文心一言 + 讯飞星火 + 智谱 + DeepSeek + 自定义对话模型支持 | ✅ | ✅ | ✅ |
| 🎭 自定义对话模型 | 包括模型名称、别名、单次积分扣除数量等等 | ✅ | ✅ | ✅ |
| 🗂️ 对话账号池 | 支持OpenAI、文心一言、讯飞星火、智谱、DeepSeek、OpenAISB、API2D、OneAPI | ✅ | ✅ | ✅ |
| 💬 对话多会话隔离 | 支持参数独立配置云端存储、消息云端漫游 | ✅ | ✅ | ✅ |
| 🛡️ 内容安全多层过滤 | 内置词库 -> 自定义词库 -> 第三方（百度云、腾讯云内容审核）安全检测，可同时启用 | ✅ | ✅ | ✅ |
| 🎨 对话多模态支持 | 支持官方图像多模态+prompt携带任意格式文件多模态 | ✅ | ✅ | ✅ |
| 📊 AI-PPT生成 | 支持主题或资料（文本、网址、Word、Excel等文件）导入创建PPT任务，支持在线大纲生成、AI大纲修改、众多PPT模板在线选择、流式动态生成预览、PPT生成后免费无限更换PPT模板等众多功能 | ✅ | ✅ | ✅ |
| 📄 文档解析对话 | 支持PDF文档解析对话 | ✅ | ✅ | ✅ |
| 🔌 开放式对话插件 | 已支持联网查询、IP信息、天气查询、快递查询等18+款插件，同时可结合开发文档扩展你自己的插件！支持ECMAScript5.1引擎、PHP、Python、NodeJS进行开发（插件持续增加中...） | ✅ | ✅ | ✅ |
| 🎥 AI视频支持 | 支持文生视频、图生视频，支持CogVideoX、可灵、SVD、Animate Diff、Stable Diffusion Animation、第三方API视频模型（如Luma）等，同时具有多模型切换及参数完全调配支持 | ✅ | ✅ | ✅ |
| 🎵 AI音乐支持 | 支持AI音乐生成，包含专业模式和简易模式等，具有非常完善的参数调控面板，同时持续对接各种主流音乐AI模型，如火山的BigMusic等 | ✅ | ✅ | ✅ |
| 🎯 AI绘画支持 | 同时支持多模型差异化的文生图 / 图生图 / 放大 / 微调 / 垫图 / 混图 / 咒语解析 / 平移(Pan) / 扩图(Zoom) / 变幻(Vary) / 区域重绘（不同模型含有的功能有差异）等 | ✅ | ✅ | ✅ |
| 🖼️ 火山智能绘图 | 支持在绘画面板上对火山智能绘图参数完全调控和生成，同时支持涂抹消除，涂抹编辑，智能扩图扩展操作 | ✅ | ✅ | ✅ |
| 🎪 Dalle3绘画 | 支持在绘画面板上对DallE-3的参数完全调控和生成 | ✅ | ✅ | ✅ |
| 🖌️ StabilityAI绘画 | 支持在绘画面板上对Stable Image Ultra、Stable Image Core、Stable Diffusion 3、SDXL的参数调控和生成 | ✅ | ✅ | ✅ |
| 🔄 绘画渠道管理 | 每个渠道同时支持单独的并发线程设定，线程隔离，支持火山引擎等 | ✅ | ✅ | ✅ |
| 📡 绘画渠道状态 | 支持在线启动、重启、关闭+队列数量实时查看 | ✅ | ✅ | ✅ |
| 🔀 绘画模式区分 | 支持普通/快速模式区分，可单独设置扣除积分 | ✅ | ✅ | ✅ |
| 📅 签到福利 | 用户可每日签到获得对应的设定积分 | ✅ | ✅ | ✅ |
| 🎲 随机签到奖励 | 支持每日签到奖励随机范围 | ✅ | ✅ | ✅ |
| 🌳 思维导图 | 一键根据需求生成思维导图，可导出PNG或SVG | ✅ | ✅ | ✅ |
| 🖼️ 画廊 | 用户绘图公开展示，包含点赞功能 | ✅ | ✅ | ✅ |
| 🏪 应用市场 | 可后台管理动态添加及其他管理 | ✅ | ✅ | ✅ |
| 👥 用户系统 | 邮箱+手机号码（登陆 / 注册 / 找回密码 / 修改密码 / 验证码登陆等等） | ✅ | ✅ | ✅ |
| 💰 支付系统 | 微信（支持扫码支付+JSAPI支持） / 支付宝（当面付、电脑网站支付） / 虎皮椒 / 彩虹易支付(为聚合支付，可对接其他更多支付平台) / 自定义外链 | ✅ | ✅ | ✅ |
| 🔑 第三方登录 | QQ / 微信扫码（个人订阅号、未认证公众号、已认证服务号均支持） / 微信网页授权 / 企业微信 / Github / Gitee / LinuxDo | ✅ | ✅ | ✅ |
| 📢 推广模块 | 支持用户推广分佣模式，分佣所获得的奖励可以兑换套餐 | ✅ | ✅ | ✅ |
| 🚨 风控系统 | 实时查看全站用户违规行为，包括但不限于文字、图片形式等内容的违规 | ✅ | ✅ | ✅ |
| 📦 套餐系统 | 支持周期内每日重置 + 固定周期内总量多种方式 | ✅ | ✅ | ✅ |
| 🎫 兑换码系统 | 兑换码系统（也可以称为卡密系统）系统 | ✅ | ✅ | ✅ |
| 🤝 邀请机制 | 好友邀请获得对应奖励，包含防止恶意自己邀请自己机制检测 | ✅ | ✅ | ✅ |
| 🎨 站点在线DIY | 例如主题色、LOGO、名称、SEO、区块圆角、自定义全局CSS、自定义全局流量统计等等均可在后台管理在线配置，让你的站点和别人的不一样，具有自己的风格～ | ✅ | ✅ | ✅ |
| 📋 侧边栏菜单控制 | 动态控制用户侧边栏菜单的显示和隐藏 | ✅ | ✅ | ✅ |
| 🔧 侧边栏动态菜单配置 | 支持内嵌网页、外部链接跳转、内部路径跳转等多种菜单配置 | ✅ | ✅ | ✅ |
| 📥 对话记录导出 | 支持将对话记录导出为PNG长图格式 | ✅ | ✅ | ✅ |
| 👻 游客访问支持 | 允许游客免登录访问界面 | ✅ | ✅ | ✅ |
| 📱 强制绑定验证 | 用户必须绑定手机或邮箱才可以使用系统 | ✅ | ✅ | ✅ |
| 🎭 头像管理 | 支持用户自定义上传头像，包含图像安全检测 | ✅ | ✅ | ✅ |
| 🚫 敏感词处理 | 支持敏感词噪音去除开关和自定义正则 | ✅ | ✅ | ✅ |
| ✨ LOGO动效 | 支持LOGO扫光动效展示 | ✅ | ✅ | ✅ |
| 🔒 用户封禁 | 支持实时封禁用户账户 | ✅ | ✅ | ✅ |
| 💭 绘画提示词库 | 支持自定义丰富的提示词 | ✅ | ✅ | ✅ |
| 🎴 绘画参考图库 | 支持自定义丰富的参考图 | ✅ | ✅ | ✅ |
| 📝 全局菜单编辑 | 支持内置菜单名称、图标、排序更改 | ✅ | ✅ | ✅ |
| 🌐 对话渠道代理 | 可每个单项自定义代理域支持 | ✅ | ✅ | ✅ |
| 🎯 代码主题适配 | 对话代码高亮主题模式跟随站点颜色模式 | ✅ | ✅ | ✅ |
| 🤔 深度思考状态 | 支持进行时状态显示和区域收缩/展开 | ✅ | ✅ | ✅ |
| 📋 模型列表展示 | 支持平铺展开和下拉选择（主要为视频、绘画等模块的模型选择） | ✅ | ✅ | ✅ |
| 🏠 自定义首页 | 自定义首页内容 | ❌ | ✅ | ✅ |
| 🔐 多点登录限制 | 限制用户多设备同时登录 | ❌ | ✅ | ✅ |
| 💎 积分类型区分 | 共分为：对话、绘画、视频、音乐、PPT、PDF、通用等 | ❌ | ✅ | ✅ |
| 📑 对话模型分组 | 支持分组+独立弹出层 | ❌ | ✅ | ✅ |
| 📣 营销通知工具 | 支持短信、邮件等多种营销通知方式 | ❌ | ✅ | ✅ |
| 🗑️ 消耗日志清除 | 支持定时清除消耗日志 | ❌ | ✅ | ✅ |
| 🌍 国际化支持 | 用户端i18n国际化支持 | ❌ | ✅ | ✅ |
| 🔗 独立渠道管理 | 支持视频、音乐、PPT等独立渠道管理（对已支持的模型多API密钥及渠道信息管理） | ❌ | ✅ | ✅ |
| 📤 在线分享功能 | 支持在线分享对话、HTML进行免登录查看 | ❌ | ✅ | ✅ |
| 📁 对话多格式导出 | 支持PNG、PDF、Markdown、TXT、SVG等格式导出 | ❌ | ✅ | ✅ |
| 📚 知识库 | 支持纯私有化的知识库管理，包括可自建ELT清洗渠道、向量模型数据库，并支持多种向量模型知识库检索，同时知识库可分享协作 | ❌ | ❌ | ✅ | 
| 🎊 更多功能 | 特性功能不止这一点，具体请查看我们的对应版本的演示站为准 | ✅ | ✅ | ✅ |

注：
- Plus版：基础功能+部分高级功能
- Pro版：包含Plus版全部功能，并增加更多专业功能
- 企业版：包含Pro版全部功能，并增加企业级特性 
- 以上版本对比中不包含已停售版本，且功能并非我们全部所有的功能，更多功能请查看产品及亲自体验演示站点吧。

## 截图
> 截图请参考以下来源的数据：

- [官网截图展示](https://d.goamzai.com/screenshot/user.html)
- [产品介绍展示](https://ipdj3sibjm.feishu.cn/docx/ARgjdOpTcohy2txfcPbclVbvnOf#ZHCFdoKrTorPXKxPKrwcn8t8nyd)
