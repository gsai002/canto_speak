# Canto Learning

一个专注于粤语学习的互动网站，帮助用户通过听、说、练掌握常用粤语表达。

## 网站简介

本网站提供以下核心功能：
- **300句常用粤语**：随机展示常用粤语例句，覆盖日常交流场景。
- **TTS 语音朗读**：支持粤语文本转语音（Text-to-Speech），帮助用户掌握标准发音。
- **语音录制与回放**：用户可以录制自己的发音并进行回放，方便自我纠正。
- **发音评分**：通过对比用户录音与标准发音，提供 0-100 的匹配度评分，实时反馈学习效果。

## 技术选型

本项目采用现代前端技术栈构建：

- **核心框架**: [React](https://react.dev/) (v18)
- **构建工具**: [Vite](https://vitejs.dev/)
- **样式方案**: [Tailwind CSS](https://tailwindcss.com/) (v4)
- **图标库**: [Lucide React](https://lucide.dev/)
- **代码规范**: ESLint

## 部署说明

### 本地开发

1. **安装依赖**

   ```bash
   npm install
   ```

2. **启动开发服务器**

   ```bash
   npm run dev
   ```
   
   启动后访问控制台输出的本地地址（通常是 `http://localhost:5173`）。

### 生产构建

1. **构建项目**

   ```bash
   npm run build
   ```
   
   构建产物将生成在 `dist` 目录下。

2. **本地预览构建产物**

   ```bash
   npm run preview
   ```
