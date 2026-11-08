# 使用指南

1. 修改 `docs` 目录中的 Markdown 文件。
2. 在本地预览并检查页面及链接。
3. 提交修改并推送到 `main` 分支。
4. 在 Actions 页面查看构建与部署状态。
5. 打开网站检查内容是否更新。

## 常用命令

- `python -m mkdocs serve`：本地预览。
- `python -m mkdocs build --strict`：构建网站并严格检查警告。

```bash
# 本地启动预览服务的具体示例
python -m mkdocs serve --dev-addr=127.0.0.1:8000

## 我的实践体会
强烈建议在每次修改完文档后，都在本地运行一次 mkdocs serve。因为本地预览是实时的，修改保存后浏览器会自动刷新。这样可以在推送到 GitHub 之前，提前发现链接错误或格式问题，避免浪费 Actions 的构建时间。
