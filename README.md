# 成健 · 全栈工程师

> **联系方式** | bcj15251769638@gmail.com
> **基本信息** | 男 · 1994 · 本科 · 8年开发经验
> **期望职位** | 全栈工程师 · 30k+
> **外语能力** | CET-6

## 个人优势

- 8年全栈开发经验，具备从 0 到 1 独立架构项目的能力，覆盖前端、后端、桌面端、小程序多端场景
- 深度参与 AI 工程化落地，主导企业级多模型网关、MCP Server、提示词工程等 AI 基础设施建设
- 熟悉实时音视频领域，基于 Agora RTC/RTM、TRTC 实现多人视频通话与实时消息系统

---

## 工作经历

### 上海某山科技有限公司

**全栈工程师** | 2022/05 ~ 至今

#### 核心项目

**1. AI 基础设施与多模型网关平台**

- 自主设计后端网关架构，统一对接 Azure OpenAI、豆包、DeepSeek、通义千问等多家 AI 服务商，提供对话、Function Call、图像/视频生成等完整 AI 能力
- 设计并管理 300+ 提示词模板，持续优化 Prompt 质量，支撑多条业务线的 AI 功能需求
- 开发公司内部 MCP Server（Model Context Protocol），为测试团队提供数据库自然语言查询能力，大幅提升工作效能
- 搭建公司内部 Dify 平台与独立 Supabase 实例，为团队提供 AI 工作流编排和内部工具支撑

**2. 督学工作台 Flutter 桌面端** — 在线视频教学教师端应用（Windows/macOS）

- 基于 Flutter 独立开发跨桌面端应用，从 Android 原生（Kotlin）迁移至 Flutter，覆盖 Windows 和 macOS 双平台
- 实现 Agora RTC/RTM + TRTC 双 SDK 实时音视频架构，支持多人视频伴学、动态监课、举手互动、私聊小窗等核心功能
- 设计 RTC/RTM 服务工厂模式，运行时按平台和业务场景自动切换音视频 SDK，多频道模式下无缝降级
- 采用 GetX 状态管理 + Dio 网络层 + go_router 路由，构建完整的 MVVM 分层架构
- 封装 JSBridge WebView 组件，复用 H5 页面实现学情分析、监课等模块，降低重复开发成本
- 集成七牛云/阿里云 OSS 文件上传、二维码签到、窗口管理等桌面端特性

**3. 前端静态资源发布 CLI 工具** （[npm](https://www.npmjs.com/package/gk-deploy-cli)）

- 基于 Node.js 开发命令行工具，实现前端项目构建、上传、发布全流程自动化，已发布至 npm 公共仓库
- 统一团队发布流程，减少人工操作失误

**4. Node.js 后端服务开发**

- 基于 NestJS/Koa 开发多个后端服务，负责中间件编写、接口鉴权、日志采集、异常处理等通用能力建设
- 对接消息队列（MQ）实现异步任务处理与服务解耦，保障高并发场景下的系统稳定性
- 使用 Dockerfile 构建标准化镜像，部署至阿里云 SAE（Serverless 应用引擎），实现自动弹性伸缩与持续交付
- 负责日常业务 RESTful API 开发、数据库设计与性能调优

**5. 跨端应用开发**

- 小程序端的功能开发与性能优化
- 基于 Tauri 框架开发桌面应用，实现 UDP 协议的局域网设备自动发现功能
- 负责日常业务的全栈开发，前后端协同

**技术栈：** Flutter/Dart · Node.js · Express/Koa/NestJS · React · TypeScript · Tauri · Agora RTC/RTM · TRTC · 阿里云 SAE/FC

---

### 某扬网络科技有限公司

**前端工程师** | 2018/09 ~ 2022/05

#### 核心项目

**地产营销 SaaS 平台** - 全渠道数字化营销解决方案

涵盖小程序、PC 端、后台管理系统、移动端 H5、数据大屏等多端应用

**主要职责：**

- 负责前端技术选型与架构设计，采用 Taro 框架构建跨端小程序，覆盖微信/支付宝等多平台
- 主导后台管理系统重构，引入 Qiankun 微前端架构，将多个独立系统统一整合，降低维护成本
- 开发并维护 15+ 营销活动模板，基于 Redux 实现商城模块状态管理，保障每周促销活动稳定上线
- 引入 TypeScript 提升类型安全，推进组件化开发，优化 Webpack 打包速度与小程序运行性能

**技术栈：** Taro · React · Redux · TypeScript · Qiankun · Nginx

---

## 技术能力

**前端开发**
- 框架：React、Next.js、Taro（跨端小程序）
- 语言：TypeScript、ES6+
- 架构：Qiankun 微前端、Redux 状态管理

**跨端与桌面开发**
- Flutter/Dart：GetX 状态管理、Dio 网络层、go_router 路由、桌面端适配（Windows/macOS）
- Tauri：Rust + Web 技术栈桌面应用开发

**后端开发**
- Node.js：Express、Koa、NestJS，中间件开发、MQ 消息队列对接
- 容器化：Docker 镜像构建与部署
- 云服务：阿里云 SAE、函数计算 FC、Serverless

**实时音视频**
- Agora RTC/RTM：多人视频通话、实时消息、多频道模式
- TRTC：腾讯实时音视频备选方案

**AI 工程化**
- 多模型网关设计（Azure OpenAI / DeepSeek / 豆包 / 通义千问）
- MCP Server 开发、Prompt Engineering、Dify 平台搭建

**开发工具**
- AI 辅助：Cursor + Claude Code
- 版本控制：Git
  
---

## 致谢

感谢您的阅读，期待与您交流！


