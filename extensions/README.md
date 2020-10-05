<div align="center">
  <a href="https://ohbug.net" target="_blank">
    <img src="https://raw.githubusercontent.com/ohbug-org/blog/master/images/ohbug_logo.svg" alt="Ohbug" height="72">
  </a>
  
  <p>An open source application information monitoring platform.</p>
</div>

# OhbugExtensionList

The Ohbug extension list stores all extensions that have been officially certified by Ohbug.

English | [简体中文](./README-zh_CN.md)

## Contributing

Your contribution is welcome! This catalog only accepts **Ohbug Extension**, and will be displayed in **Ohbug Market** for users to choose from after approval.

If you want to add your own **Ohbug Extension** to the **Ohbug Market**, please submit [PR](https://docs.github.com/en/free-pro-team@latest/github/ collaborating-with-issues-and-pull-requests/creating-a-pull-request) Modify the `list.json` file in this directory according to the following requirements and add the paragraph `Extensions` in the root directory `README.md` The warehouse address of your plugin.

Modify the `data` field in the `list.json` file and add your **Ohbug Extension** information in the following format.

```json
{
  "name": "OhbugExtensionRrweb",
  "description": "To 'screen recording'",
  "author": "chenyueban <jasonchan0527@gmail.com>",
  "logo": "https://www.rrweb.io/favicon.png",
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
