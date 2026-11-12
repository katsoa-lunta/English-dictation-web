---
📚 英语听写练习
---

一款适合学生使用的纯网页英语单词听写工具。无需安装、无需后端，打开网页即可练习。

> 拍一拍，听一听，写一写 —— 英语听写如此简单。

---

## ✨ 在线体验

🔗 **<https://katsoa-lunta.github.io/english-dictation>**

---

## 🚀 功能特点

- 📷 **图片识别单词**：上传课本单词表或手抄单词照片，自动识别英文单词
- 🔊 **真人发音朗读**：使用系统语音逐个朗读单词，支持语速调节
- ✏️ **即时拼写反馈**：输入正确显示“正确”，错误时展示正确答案
- 📊 **练习结果统计**：正确率环形图、错词列表一目了然
- 🔄 **错题重练模式**：一键只练习拼错的单词
- 📱 **全平台适配**：手机、平板、电脑都能使用
- 🔒 **纯前端运行**：无需服务器，无需 API Key，保护隐私

---

## 📖 使用说明

1. 打开网页后，点击或拖拽上传一张包含英文单词的图片
2. 稍等片刻，应用会自动识别出图片中的单词
3. 检查识别结果，可删除多余单词或手动补充
4. 点击「开始听写」
5. 听发音，在输入框中输入听到的单词，按回车或点击「提交」
6. 练习结束后查看正确率和错词

---

## 🛠️ 技术栈

- **HTML5 / CSS3 / 原生 JavaScript** —— 单文件网页应用
- **Tesseract.js** —— 浏览器端 OCR 文字识别
- **Web Speech API** —— 浏览器语音合成（TTS）
- **GitHub Pages** —— 免费静态站点托管

---

## 📦 部署到 GitHub Pages

### 方式一：直接上传（最简单）

1. 在 GitHub 新建一个 Public 仓库，例如 `english-dictation`
2. 进入仓库，点击 **Add file → Upload files**
3. 上传 `index.html`
4. 打开 **Settings → Pages**
5. Source 选择 **Deploy from a branch**，Branch 选 **main / (root)**
6. 等待 1-2 分钟，访问 `https://你的用户名.github.io/english-dictation`

### 方式二：使用 Git

```bash
git clone https://github.com/你的用户名/english-dictation.git
cd english-dictation
# 将 index.html 放入此目录
git add index.html
git commit -m "Initial commit"
git push origin main
```

然后在仓库 Settings → Pages 中启用 GitHub Pages。

---

## ⚠️ 注意事项

1. **OCR 识别准确度**：Tesseract.js 对印刷体识别效果较好，手写体或复杂背景可能识别不准。识别后支持手动修改单词列表。
2. **语音发音质量**：取决于你的设备系统是否安装了英文语音包。推荐使用 Chrome 或 Edge 浏览器，语音效果较好。
3. **首次使用加载**：第一次打开应用时，Tesseract.js 会自动下载英文语言包（约 10MB），请保持网络连接。
4. **浏览器兼容性**：需要支持 Web Speech API 的现代浏览器（Chrome、Edge、Safari、Firefox 等）。

---

## 🙋 常见问题

**Q：为什么识别出来的单词不全？**  
A：请确保图片清晰、文字对比度高。识别后可以在单词列表中手动补充。

**Q：为什么没有声音？**  
A：请检查设备音量，并确认浏览器允许网页播放音频。部分移动浏览器需要用户点击一次页面后才能播放声音。

**Q：可以离线使用吗？**  
A：首次加载语言包后，部分浏览器支持离线缓存。但为获得最佳体验，建议联网使用。

---

## 📄 许可证

MIT License — 可自由使用、修改和分发。

---

如果觉得这个项目对你有帮助，欢迎点个 ⭐ Star！

---
