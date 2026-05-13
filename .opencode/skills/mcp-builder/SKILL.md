# MCP-Builder

> 快速创建 MCP (Model Context Protocol) 服务器 — 集成外部 API 和服务

## 使用方法

在 OpenCode 对话中输入 `@mcp-builder` 激活此技能。

## 支持的传输方式

- **stdio** - 通过标准输入输出通信
- **SSE** - Server-Sent Events（HTTP 流式）
- **WebSocket** - 双向实时通信

## 创建步骤

1. 定义工具列表（名称、描述、参数 schema）
2. 实现工具的执行逻辑
3. 配置传输方式
4. 生成完整的 MCP 服务器代码

## 输出内容

- 完整的 TypeScript/Python 服务器代码
- 客户端配置说明
- 工具定义文件（tools.json）
- 使用示例和测试用例

## 触发条件

当用户提到以下关键词时自动激活：
- "MCP 服务器"、"创建 MCP"、"mcp server"
- "集成外部服务"、"API 集成"
- "连接数据库"、"调用 API"