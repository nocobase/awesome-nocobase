# Awesome NocoBase

> A curated list of NocoBase plugins, JS block scripts, etc.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[NocoBase](https://www.nocobase.com/) is an open-source AI + no-code platform for building business systems fast. Instead of generating everything from scratch, AI works on top of production-proven infrastructure and a WYSIWYG no-code interface, so you get both speed and reliability.

## Contents

- [Awesome NocoBase](#awesome-nocobase)
  - [Contents](#contents)
  - [Community Plugins](#community-plugins)
  - [Contributing](#contributing)

## Community Plugins

| Plugin name | Description | 中文描述 |
| --- | --- | --- |
| [NocoBase Hooks](https://github.com/Bunnarin/nocobase-plugin-hooks) | A hooks system for NocoBase similar to PocketBase's `pb_hooks`, allowing you to write full plugin-like code that extends NocoBase functionality directly from the `storage/hooks/` directory. | 一个类似 PocketBase `pb_hooks` 的 NocoBase 钩子系统，允许你直接在 `storage/hooks/` 目录中编写像完整插件一样的代码，扩展 NocoBase 功能。 |
| [Global Search](https://github.com/trumanharry/nocobase-globalsearch-plugin) | A custom NocoBase plugin that adds a global cross-collection search feature to the admin interface. | 一个自定义 NocoBase 插件，为管理界面添加全局跨数据表搜索功能。 |
| [kkFileView File Preview](https://github.com/STlxx-lin/nocobase-plugin-file-previewer-kkfileview) | Multi-engine file preview plugin for NocoBase supporting kkFileView, BaseMetas, Microsoft Online, and offline File Viewer for Office, PDF, CAD, 3D, and media files. | 多引擎文件预览插件，深度集成 kkFileView、BaseMetas、微软在线及离线 File Viewer，支持 Office、PDF、CAD、3D 模型、音视频及压缩包全格式预览。 |
| [Office File Previewer](https://github.com/OneTwoSmall/nocobase-custom-plugins/tree/main/plugins/%40nocobase/plugin-file-previewer-office) | A powerful and flexible file preview plugin for NocoBase that supports multiple preview modes for office documents and other file formats. | 一个强大且灵活的 NocoBase 文件预览插件，支持 Office 文档及其他文件格式的多种预览模式。 |
| [Enhanced Table Block](https://github.com/OneTwoSmall/nocobase-custom-plugins/tree/main/plugins/%40nocobase/plugin-enhanced-table-block) | An enhanced table block plugin for NocoBase. It provides advanced tabular features to improve data visualization and manipulation within your application. | 一个 NocoBase 增强表格区块插件，提供高级表格功能，改善应用中的数据可视化和操作体验。 |
| [Auth: Email](https://github.com/OneTwoSmall/nocobase-custom-plugins/tree/main/plugins/%40nocobase/plugin-auth-email) | Email authentication with verification code. | 支持通过邮件验证码进行身份认证。 |
| [Custom Login Page](https://github.com/taichuy/nocobase-plugin-login-lite) | Custom Login Page Configuration Plugin for NocoBase (Lite Version). This plugin allows you to customize the appearance and behavior of the NocoBase login page directly from the admin panel. | NocoBase 自定义登录页配置插件（精简版），允许你直接在管理面板中自定义登录页的外观和行为。 |
| [Block: Tabs](https://github.com/vokylin/plugin-block-tabs) | A powerful NocoBase plugin that provides tabbed interface components for organizing multiple blocks, reducing page scrolling and improving content organization. | 一个强大的 NocoBase 插件，提供标签页界面组件来组织多个区块，减少页面滚动并改善内容编排。 |
| [Watermark-shuiyin1](https://github.com/fengwenkai168/nocobase-plugin/) | The NocoBase watermark plugin overlays a semi-transparent watermark on pages displaying the current logged-in username to prevent screenshot leaks, and supports customizing watermark text, opacity, and font size in the plugin settings. | NocoBase 水印插件能在页面上覆盖半透明水印，显示当前登录用户名以防止截图泄密，并支持在插件设置中自定义水印文字、透明度和字号。 |
| [Role Switcher](https://github.com/michaelxmn/plugin-role-switcher) | A NocoBase plugin that adds a **Role Switcher** to the top navigation bar, making role switching faster and easier to discover. | 一个在顶部导航栏中添加 **角色切换器** 的 NocoBase 插件，让角色切换更快捷、更易发现。 |
| [Per-User Column Settings](https://github.com/Albert-mah/nocobase-plugin-user-columns) | Per-user table column settings for client-v2 tables: one toolbar action lets every end user show/hide, drag-reorder, pin and resize columns for themselves, spreadsheet-style, without touching the shared page schema. | 为 client-v2 表格提供按用户保存的列设置：每位终端用户都可以通过一个工具栏操作，以类似电子表格的方式显示或隐藏、拖拽排序、固定及调整列宽，且不会修改共享页面 Schema。 |
| [Field Sequence Pro](https://github.com/ericto888/nocobase-plugin-field-sequence-pro) | Extends the official auto-increment field with three powerful features: form variable values, value mapping dictionaries, and multi-dimensional isolated counters, while retaining all core functionalities. | 在官方自动编码字段基础上增强，新增表单变量取值、值映射字典和多维度隔离计数三大特性，同时保留官方全部核心功能。 |
| [HTTP Error Handler](https://github.com/Albert-mah/plugin-http-error-handler) | Global 4xx/5xx fallback: JS-expression rules render friendly error pages or 302 redirects for unhandled API errors — static rules, zero DB writes, hot-reloaded from a settings page. | 全局 4xx/5xx 错误兜底：通过 JS 表达式规则，将未处理的 API 错误展示为友好错误页面或 302 重定向；规则为静态配置、无需写入数据库，并可在设置页热更新。 |
| [Workflow: URL Trigger](https://github.com/Albert-mah/plugin-workflow-url-trigger) | URL event trigger + HTTP response node for workflows: webhook-style entry points with glob/regex matching, request context as variables, and full control over the reply (JSON / redirect / block). | 为工作流提供 URL 事件触发器和 HTTP 响应节点：支持通配符或正则匹配，将请求上下文作为变量，并可完全控制响应内容（JSON、重定向或区块）。 |
| [Workflow: Crypto](https://github.com/Albert-mah/plugin-workflow-crypto) | AES encrypt/decrypt workflow node — exchange encrypted payloads with external systems, with variable inputs and auto-parsed JSON after decrypt. | AES 加密/解密工作流节点：可与外部系统交换加密载荷，支持变量输入，并会在解密后自动解析 JSON。 |
| [Workflow: Auth Token](https://github.com/Albert-mah/plugin-workflow-auth-token) | Sign real NocoBase login JWTs from a workflow step — build SSO auto-login links and programmatic tokens (pairs with URL Trigger + Crypto for a full SSO flow). | 在工作流步骤中签发真实的 NocoBase 登录 JWT：可构建 SSO 自动登录链接和程序化令牌；可与 URL Trigger、Crypto 组合，实现完整的 SSO 流程。 |
| [Verification: Image Captcha](https://github.com/simousa/nocobase-plugin/tree/main/plugin-verification-code) | Require users to enter a verification code (character-based or arithmetic-based) when logging in, registering, recovering a password, or submitting public forms. | 在用户登录、注册、找回密码以及公开表单提交时要求输入验证码（字符验证码/算数验证码）。 |
| [View:  timeline](https://github.com/youchaoyun/nocobase-timeline) | timeline is a NocoBase timeline block plugin for displaying multi-record data along a time dimension. It works well for project milestones, event history, engineering progress, and other chronological scenarios. | timeline 是一个 NocoBase 时间轴区块插件，用于按时间维度展示多条记录数据，适合项目节点、事件轨迹、建设过程、历史变更等场景。 |
| [View:  gallery-view](https://github.com/youchaoyun/nocobase-gallery-view) | gallery-view is a NocoBase gallery view block plugin used to display multiple data records as image card carousels. It is suitable for product showcases, case studies, portfolio browsing, image-text content navigation, and similar scenarios. | gallery-view 是一个 NocoBase 画廊视图区块插件，用于将多条数据记录以图片卡片轮播的方式进行展示，适合产品展示、案例展示、作品集浏览、图文内容导览等场景。 |
| [Multi Tab Page](https://github.com/simousa/nocobase-plugin/tree/main/plugin-tab-page) | It is a NocoBase multi-tab plugin. Each time a menu/page is opened, a new tab is created. By clicking on the tab, you can switch between the opened pages. Make the menus and pages of NocoBase open, switch and close just like browser tabs. | 这是一个 Nocobase 多标签页插件。每打开一个菜单/页面就新增一个标签，点击标签即可在已打开的页面之间切换。让 NocoBase 的菜单和页面像浏览器标签页一样打开、切换、关闭。 |
| [Logger Pro](https://github.com/STlxx-lin/nocobase-plugin-logger-pro) | Enterprise-grade logging console, end-to-end request tracing, AI error diagnostics, user operation audit Diff view, and multi-channel alerting. | 企业级系统日志控制台、全链路请求追踪、AI 错误日志智能诊断、用户操作审计 Diff 对比及多渠道异常告警体系。 |
| [Online Count](https://github.com/STlxx-lin/nocobase-plugin-online-count) | Real-time online user counter, active session tracking, concurrent login policy, force logout, and historical online trend analytics. | 实时在线人数监控、在线用户与活跃会话管理、多端并发登录管控、一键强制下线及历史在线趋势分析。 |
| [Attachment Cleaner](https://github.com/STlxx-lin/nocobase-plugin-attachment-cleaner) | Scan, analyze, and clean orphaned or expired attachments with disk storage visualization. | 扫描、分析并清理 NocoBase 中的未引用孤立附件或过期附件，支持磁盘占用统计与一键安全清理。 |
| [Custom Icons](https://github.com/STlxx-lin/nocobase-plugin-custom-icons) | Custom SVG icons, external icon libraries import (Iconfont, Iconify, Caomei), and seamless integration with NocoBase IconPicker. | 自定义 SVG 图标扩展、第三方图标库市场（Iconfont、Iconify、创造狮等）在线导入与原生图标选择器无缝集成。 |
| [快速筛选](https://github.com/charce526/plugin-quick-filter) | Provide configurable option-based quick filtering and text search for the NocoBase data table action bar, while maintaining compatibility with both V1 Schema pages and V2 FlowEngine pages. | 为 NocoBase 数据表格操作栏提供可配置的选项快捷筛选与文本搜索，同时兼容 V1 Schema 页面与 V2 FlowEngine 页面。 |
| [扩展图标库](https://github.com/charce526/plugin-icon-library) | NocoBase icon library extension plugin. Provides 1400+ icons with semantic categories for visual configuration points such as menus, buttons, and page tabs. | NocoBase 扩展图标库插件。为菜单、按钮、页面标签等可视化配置位置提供 1400+ 个图标与语义分类。 |
| [Custom Login Page Pro](https://github.com/STlxx-lin/nocobase-plugin-custom-login-page) | Enterprise-grade visual custom login page builder driven by FlowEngine grid, featuring 14 built-in customizable blocks (Hero banner, feature matrix, stats, notices, QR codes, countdown), dual-mode workbench studio, and high-concurrency memory caching. | 企业级可视化自定义登录页与模块扩展插件，基于 FlowEngine 原生网格引擎驱动，内置 14 类开箱即用专属区块（品牌标语、特性矩阵、数据看板、公告、客服二维码、倒计时等），支持双层工作台设计器与高并发内存缓存。 |
| [Password Recovery](https://github.com/STlxx-lin/nocobase-plugin-password-recovery) | Enterprise self-service password recovery plugin for NocoBase with workflow triggers (SMS, DingTalk, WeCom, Feishu, SMTP), anti-abuse rate limits, multi-step verification wizard, and audit logs. | 企业级密码自助找回与工作流联动插件，支持登录页两步向导集成、数据表事件驱动工作流联动（支持企微/钉钉/飞书/邮件/短信等多渠道通知）、防刷限流与全流程运维审计。 |

## Contributing

Contributions are welcome. Please keep this list focused on NocoBase resources.

Before submitting a pull request:

- Add only public resources that are directly related to NocoBase.
- Use a concise one-line description.
- Keep entries alphabetized within each section when possible.
- Avoid duplicate links.
