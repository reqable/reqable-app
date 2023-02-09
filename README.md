# Reqable
Reqable是一款跨平台的专业HTTP开发和调试工具，桌面版将于今年3月开始Beta测试，欢迎各位开发者参与[产品体验](https://reqable.com/)！  

## 平台
Reqable基于Flutter开发，计划支持Windows/Mac/Linux/Android/iOS平台。
其中，桌面端基本功能已经实现，即将开始beta测试，移动端预计2023年中下旬开始研发。

## REST
API测试是Reqable的核心功能之一，除了具备基本的HTTP功能测试外，还支持最新的HTTP3协议。
- 支持HTTP/1.1, HTTP2, HTTP3协议版本。
- 支持Json/Text/Urlencode/Multiparts/Binary等数据格式。
- 支持Cookie管理。
- 支持cURL导入和导出。
- 支持请求授权配置。
- 支持代理配置。
- 支持JSON/XML/图片/HEX/Multiparts等多种视图。

## Capture
API调试也是Reqable的核心功能，并且支持与REST进行联动，更加方便地对HTTP请求进行开发和调试。
- 支持HTTP/1.x, HTTP2协议版本。
- 使用经典的MITM HTTP代理方式进行数据抓包，支持HTTPS。
- 网关功能：对指定请求或响应进行屏蔽，挂起等操作。
- 重写功能：预设规则对指定请求或响应进行替换或者修改。
- 断点功能：实时对请求或响应进行断点操作，比如屏蔽，挂起或修改替换。
- 脚本功能：支持编写Python脚本处理请求或响应。
- 镜像功能：对指定域名配置镜像。
- 支持重发，高亮、筛选、搜索、HAR导入导出等。

## 其他
Reqable核心库使用C++编写，UI和逻辑使用Flutter框架开发，保证了整体的跨平台性。同时，Flutter框架也保证了应用整体良好的UI效果。
- 支持黑白两种主题模式。
- 支持多种主题色。
- 支持简体中文和英语两种语言。
- 支持多种代码高亮配色。
- 支持多窗口、托盘功能等。

## Beta测试
Beta版本的测试预计于今年3月开启，先后顺序是Mac/Windows/Linux平台，热烈欢迎大家届时参与！

## 原型

![](/arts/screenshot1.png)

![](/arts/screenshot2.png)
