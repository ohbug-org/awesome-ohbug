<div align="center">
  <a href="https://ohbug.net" target="_blank">
    <img src="https://raw.githubusercontent.com/ohbug-org/blog/master/images/ohbug_logo.svg" alt="Ohbug" height="72">
  </a>
  
  <p>An open source application information monitoring platform.</p>
</div>

# OhbugExtensionList

Ohbug 扩展列表，存放所有经过 Ohbug 官方认证的扩展（extension）。

[English](./README.md) | 简体中文

## 贡献

欢迎您的贡献！本目录只接受 **Ohbug Extension**，审核通过后将展示在 **Ohbug Market** 供用户选择使用。

如果你希望将自己的 **Ohbug Extension** 加入到 **Ohbug Market** 中，请提交 [PR](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request) 按照以下要求修改本目录下的 `list.json` 文件以及在根目录下 `README.md` 中 `Extensions` 段落加入您插件的仓库地址。

修改 `list.json` 文件中的 `data` 字段，按照下方格式加入您的 **Ohbug Extension** 信息。

```json
{
  "name": "OhbugExtensionRrweb",
  "author": "chenyueban <jasonchan0527@gmail.com>",
  "repository": {
    "type": "git",
    "url": "https://github.com/ohbug-org/ohbug-extension-rrweb"
  },
  "key": "rrweb",
  "ui": {
    "name": "OhbugExtensionUIRrweb",
    "cdn": "https://cdn.jsdelivr.net/npm/@ohbug/extension-rrweb@latest/dist/ui.umd.min.js"
  }
}
```
