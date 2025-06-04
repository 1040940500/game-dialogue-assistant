# 🎮 游戏攻略问答平台 - 多轮对话 + 用户管理

这是一个基于 Gradio + OpenAI GPT 的多轮问答平台，支持用户登录、历史记录管理以及游戏问题答疑。

## ✨ 项目特点

- 多用户支持，基于用户名管理历史记录
- 使用 OpenAI 接口构建多轮问答逻辑
- 支持历史记录保存/清空（通过 `history_storage.py` 模块）
- 使用 Gradio 构建美观交互界面，支持聊天展示样式自定义

## 🧠 技术栈

- Python
- Gradio
- OpenAI API（通过 ChatAnywhere 接口代理）
- 自定义 JSON 本地记录历史

## 📦 安装与运行

```bash
pip install -r requirements.txt
python app.py
```

## 🔐 注意事项

请在代码中设置你的 OpenAI API Key，并避免上传 `.env` 或密钥文件。

## 📸 截图

（可选上传项目截图，展示界面）