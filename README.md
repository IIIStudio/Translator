# Translator

一个单页英文翻译工具：输入英文，按回车即可在原文下方逐句显示中文译文。

![](image/image.png)

## 功能

- 无需安装、无需构建，直接用浏览器打开 `index.html` 即可使用
- 输入英文后按回车，自动按句切分并翻译，译文以注音（`ruby`）形式显示在原文下方
- 支持多句同时翻译，并发请求提升速度
- 快捷键：
  - `Enter`：翻译
  - `Shift + Enter`：插入换行
  - `Esc`：清空内容

## 使用

直接用浏览器打开 `index.html`，或在任意静态服务器上托管：

```bash
# 例如使用 Python 启动本地服务器
python3 -m http.server 8000
```

然后访问 `http://localhost:8000`。

## 说明

- 翻译服务使用 [MyMemory](https://mymemory.translated.net/) 免费接口（英文 → 中文），翻译质量取决于该服务的免费额度与限制
- 全部代码在单个 `index.html` 中，无任何外部依赖

## 许可证

[MIT](LICENSE)
