# 📚 步步高 AI 学习伙伴

基于 MiniMax 多能力模型的家庭教育场景 Demo，涵盖三大功能：

- 📖 **陪读模式** — 中英文故事多音色 TTS 朗读
- 🗣️ **口语陪练** — AI 英语对话伙伴，多场景实战
- 🧩 **思维训练** — 数学/编程/谜题/科学问答

## 使用方法

### 方式一：直接打开
双击 `index.html` 在浏览器中打开即可使用（推荐 Chrome/Edge）。

### 方式二：本地服务
```bash
cd bubugaoban
python3 -m http.server 8080
# 访问 http://localhost:8080
```

## 配置

首次使用需要填写 MiniMax API Key（在网页顶部的输入框），Key 仅在本地存储，不会被上传。

获取 API Key: [MiniMax 开放平台](https://platform.minimax.chat/)

## 三大功能详解

### 📖 陪读模式
- 输入任意中英文故事文本
- 选择4种音色：甜美女声 / 磁性男声 / 童声 / 温和长辈
- 调节语速，生成 MP3 在线播放

### 🗣️ 口语陪练
- 日常对话 / 旅行英语 / 面试英语 / 角色扮演 四个场景
- AI 实时反馈，纠正表达错误
- 支持多轮上下文对话

### 🧩 思维训练
- 数学思维 / 编程启蒙 / 逻辑谜题 / 科学探索
- 内置趣味题目，点击即可提问
- 适合亲子互动，家长孩子一起玩

## 技术栈

- 纯前端（HTML + CSS + JS），无框架依赖
- 调用 MiniMax TTS API（`speech-02-hd`）和 Chat API（`MiniMax-Text-01`）
- CDN 外部资源：零（全部内联）

## License

MIT
