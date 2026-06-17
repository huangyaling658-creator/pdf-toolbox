# PDF 工具箱 · 11 合 1

> 纯本地处理，文件不上传服务器。打开网页即用，关掉即走。

🔗 **在线使用：[pdf.santaya.chat](https://pdf.santaya.chat)**

![type](https://img.shields.io/badge/纯前端-本地处理-2e7d5b) ![privacy](https://img.shields.io/badge/隐私-文件不上传-2e7d5b) ![license](https://img.shields.io/badge/部署-GitHub%20Pages-2e7d5b)

---

## 这是什么

一个把常用 PDF 操作打包在一起的网页工具箱。所有处理都在你**浏览器本地**完成——文件不经过任何服务器，不上传、不留存，关掉页面就什么都没了。适合处理合同、证件、简历这类不方便上传到第三方网站的文件。

## 11 个工具

| 工具 | 作用 |
|---|---|
| 📎 合并 | 多个 PDF 合成一个 |
| ✂️ 拆分 | 一个 PDF 拆成多个 / 按页提取 |
| 🔄 旋转 | 逐页实时预览，按需旋转 |
| 🗑️ 删页 | 删除不需要的页面 |
| 🔀 重排 | 拖拽调整页面顺序 |
| 🖼️ 图片转 PDF | 多张图片合成 PDF |
| 📤 PDF 转图片 | PDF 每页导出为图片 |
| #️⃣ 页码 | 批量添加页码 |
| 💧 水印 | 实时预览，可调大小/角度/透明度 |
| ✍️ 签名 | 手写签名，拖拽到任意页任意位置 |
| 🗜️ 压缩 | 缩小文件体积 |

## 特点

- **本地优先**：基于 [pdf-lib](https://pdf-lib.js.org/) + [pdf.js](https://mozilla.github.io/pdf.js/)，全程在浏览器里跑，零后端。
- **所见即所得**：旋转、水印、签名都是实时预览，调好再导出。
- **Dark Botanical 风格**：深色护眼的暗调植物美学界面。
- **零安装**：打开网页就能用，无需注册、无需下载客户端。

## 技术栈

- 纯静态 HTML / CSS / JS
- [pdf-lib](https://pdf-lib.js.org/) — PDF 生成与编辑
- [pdf.js](https://mozilla.github.io/pdf.js/) — PDF 渲染与预览
- 部署在 GitHub Pages，自定义域名 `pdf.santaya.chat`

## 本地运行

```bash
git clone https://github.com/huangyaling658-creator/pdf-toolbox.git
cd pdf-toolbox
# 任意静态服务器即可，例如：
npx serve .
```

或直接用浏览器打开 `index.html`。

---

由 [Santa](https://github.com/huangyaling658-creator) 一个人 + AI 打造。
