# APEX / F1 街機賽車

一款使用 Three.js 與 WebGL 製作的第一人稱 3D 街道賽車遊戲。坐在駕駛艙內觀看有建築、護欄、路肩與對手車的立體賽道，並可用鍵盤或畫面方向盤轉向。Three.js 已打包在遊戲檔案內，不需另外下載引擎；遊玩仍需使用支援 WebGL 的瀏覽器。

## 遊玩方式

- `↑` / `W` 加速，`↓` / `S` 煞車
- `←`、`→` / `A`、`D` 轉向
- `空白鍵` 使用 ERS 氮氣加速
- 手機可拖曳方向盤轉向，按住「加速」按鈕前進
- 完成三圈，盡可能取得第一名

本機可直接以瀏覽器開啟 `index.html`，也可用 VS Code Live Server 預覽。

## 發布

專案使用 GitHub Actions 將根目錄靜態網站發布到 GitHub Pages。推送到 `main` 後會自動建置與部署。到 GitHub 專案的 **Settings → Pages**，將 Source 設為 **GitHub Actions**。

