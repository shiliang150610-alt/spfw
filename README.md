spfw-allinone/
│
├─ backend/
│   ├─ src/
│   │   ├─ controllers/
│   │   ├─ middlewares/
│   │   ├─ services/
│   │   └─ index.ts
│   ├─ package.json
│   ├─ tsconfig.json
│   └─ README.md
│
├─ frontend/
│   ├─ src/
│   │   ├─ components/
│   │   ├─ pages/
│   │   ├─ App.tsx
│   │   └─ main.tsx
│   ├─ public/
│   ├─ vite.config.ts
│   ├─ package.json
│   ├─ tsconfig.json
│   └─ README.md
│
├─ electron/
│   ├─ main.ts
│   ├─ preload.ts
│   └─ package.json
│
├─ package.json
└─ README.md
# 全能文件浏览器（spfw-allinone）

## 一键开发和构建
```bash
# 克隆仓库
git clone https://github.com/你的用户名/spfw-allinone.git
cd spfw-allinone

# 安装依赖
npm install

# 启动开发环境（前后端联调）
npm run start

# 构建发布版（web端和electron桌面端）
npm run build:backend
npm run build:frontend
npm run build:electron
```

## 发布Web应用：将 frontend/dist 静态资源挂载到 Nginx 或任意 web 服务器即可。

## 发布为桌面应用：Electron 输出目录下打包即可发布 Windows/Mac/Linux 桌面端。
