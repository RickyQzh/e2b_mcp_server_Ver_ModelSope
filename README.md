# e2b-fastmcp-server

基于 E2B 沙箱与 FastMCP 的 MCP 服务器。


## PyPI包
快速使用：
```bash
npx @modelcontextprotocol/inspector uvx e2b-fastmcp-server@latest
```

## 环境变量
支持通过 `.env` 或系统环境变量配置，需要 E2B (https://e2b.dev/) 提供的api-key。

## 开发与构建
在项目根（包含 `pyproject.toml` 的目录）执行：
```bash
uv add build twine
uv run -m build
```
产物位于 `dist/` 目录，包含 `.whl` 与 `.tar.gz`。


