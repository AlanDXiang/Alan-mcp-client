# mcp-client

这是一个基于MCP协议的客户端实现。

## 项目简介

本项目旨在提供一个简单易用的MCP协议客户端，支持与服务器端进行高效通信。

## 安装依赖

```bash
pip install -r requirements.txt
```

## 使用示例

```python
from client import MCPClient

client = MCPClient('localhost', 8080)
client.connect()
response = client.send_request('hello')
print(response)
```

## 目录结构

```
├── docs                # 文档目录
│   └── MCP快速入门实战.pdf
├── README.md           # 项目说明文档
├── client.py           # 客户端核心代码
├── main.py             # 主程序入口
├── pyproject.toml      # Python项目配置文件
└── uv.lock             # 依赖版本锁定文件
```

## 贡献者

欢迎提交Pull Request和Issue。