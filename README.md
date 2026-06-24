# 《白鷺學園的戀愛習題》— 桌面版 (exe)

本 repo 為 [gal](https://github.com/colinisgod1106/gal) 的 **Electron 桌面應用打包版**。

## 下載遊戲

前往 [Releases](https://github.com/colinisgod1106/gal-exe/releases) 下載最新版安裝程式（`.exe`）。

## 開發者：本地執行

1. 安裝 [Node.js](https://nodejs.org/) (v18+)
2. 安裝依賴：
   ```bash
   npm install
   ```
3. 啟動開發模式：
   ```bash
   npm start
   ```

## 打包成 exe

```bash
npm run dist
```

輸出在 `dist/` 資料夾。

## 技術棧

- 遊戲引擎：純 HTML5 + CSS3 + Vanilla JavaScript
- 桌面封裝：[Electron](https://electronjs.org/)
- 打包工具：[electron-builder](https://www.electron.build/)
