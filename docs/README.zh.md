# AuroraSpeak Studio 简介

AuroraSpeak Studio 让 ChatGPT 拥有自然流畅的语音体验，可用于口语训练、会议排练或轻松聊天，全程在本地浏览器中完成。

![AuroraSpeak Studio 界面预览](../assets/demo-zh.png)

## 功能亮点
- 多语言会话：即时文本与语音同步，支持多种发音风格
- 隐私优先：会话记录默认保存在浏览器本地
- 自适应界面：针对桌面、平板与移动设备优化
- 模块化语音引擎：可以选择本地识别或接入自定义云服务
- 丰富的提示与模板，帮助用户快速进入角色

## 快速开始
1. 安装依赖
   ```bash
   yarn install
   ```
2. 启动开发服务器
   ```bash
   yarn dev
   ```
3. 在浏览器访问 `http://localhost:5173`，并通过引导向导配置首选的语音识别与合成方案。

## 构建与发布
- 使用 `yarn build` 生成生产版本
- 通过 `yarn preview` 验证编译结果
- 将 `dist/` 目录部署到任意静态站点或容器环境中

## 技术架构
- 前端框架：React + TypeScript，构建工具为 Vite
- 样式系统：Tailwind CSS 搭配自定义主题
- 状态管理：模块化 store，包含会话缓存与设置同步
- 音频流水线：基于 Web Speech API，配有可插拔适配层
- 国际化：内置英语、西班牙语与简体中文资源包

## 项目进展
- ✅ 核心对话、语音识别与播放流程已完成
- ✅ 支持主题切换与跨设备布局
- 🚧 正在打磨自定义音色与场景模板
- 📜 更新历史可查看 `CHANGELOG.md`

## 贡献指南
欢迎提交 Issue 与 Pull Request。请在贡献前查阅 `docs/developer-guide.zh.md` 中的协作说明。

## 许可协议
本项目采用 MIT 许可证发布，详细内容请参阅 `LICENSE`。
