# 🎭 贴纸换脸 face-sticker

自动人脸检测 + 贴纸替换的纯前端小工具:上传图片自动识别人脸,弹窗实时预览贴纸效果,也支持手动标注微调。纯浏览器实现,图片不上传。

## ✨ 特性
- 👤 自动人脸检测,贴纸自动贴合(双向检测 + 智能去重,同一张脸不会贴两个)
- 👁️ 弹窗实时预览,所见即所得
- ✍️ 支持手动标注 / 调整位置,人脸框可一键 ✕ 删除、Ctrl+Z 撤销
- 🌐 检测模型多线路 CDN 自动切换,公司网络 / 弱网环境也能加载
- 🔒 纯前端本地处理,不上传服务器

## 🚀 使用
双击打开 `index.html`,或:
```bash
npx serve .
```
开发记录见 `devlog.html`。

## 项目更新与AI实践

微信搜索公众号 **「Pamela的AI笔记」** 或扫描下方二维码，获取项目更新、最新AI应用案例和实用教程。

<img src="assets/pamela-ai-notes-wechat.png" alt="微信公众号「Pamela的AI笔记」二维码" width="800">

## 🧩 技术
纯前端(HTML + JavaScript + 人脸检测),浏览器内运行。

---
🤖 由 [Claude Code](https://claude.com/claude-code) 协助整理
