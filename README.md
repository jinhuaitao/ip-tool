高级 IP 地址查询工具 (Advanced IP Query Tool)
这是一个轻量级、现代化的 IP 地址查询 Web 应用。采用单文件架构 (Single-File Architecture)，将 HTML、CSS 和 JavaScript 逻辑完美融合在一个独立文件中，无需复杂的构建工具或后端依赖，开箱即用。

✨ 核心特性
全自动化检测：页面加载时自动获取并展示访问者的公网 IP。

精准数据解析：支持 IPv4 和 IPv6，提供组织/ISP、ASN、国家、省份、城市、邮政编码及所在时区等详细信息。

交互式地图可视化：基于 OpenStreetMap 内嵌地图，直观展示 IP 所在的大致物理坐标。

现代化 UI 设计：

响应式网格布局，完美适配移动端与桌面端。

优雅的加载状态与错误提示机制。

一键复制 IP 功能，并配备平滑的 Toast 交互通知。

零外部依赖：纯原生 JavaScript (Vanilla JS) 编写，无冗余的第三方 UI 库。

🛠 技术栈与 API
前端技术：HTML5, CSS3 (CSS Variables, Flexbox/Grid), ES6 JavaScript

核心数据源：ipinfo.io API (默认使用免鉴权公开接口)

地图渲染：OpenStreetMap 嵌入式 iframe
