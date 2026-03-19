# 寫作 — 專注打字 PWA

一個全黑、極簡的打字環境，支援離線使用與安裝到桌面／手機。

---

## 安裝方式

### 方法一：GitHub Pages（免費，推薦）

1. 到 [github.com](https://github.com) 建立免費帳號
2. 新增一個 Repository，名稱隨意（例如 `focus-writer`）
3. 把這個資料夾裡的所有檔案上傳
4. 進入 Settings → Pages → Source 選 `main` branch → Save
5. 幾分鐘後會得到網址，例如 `https://yourname.github.io/focus-writer`
6. 用手機或電腦瀏覽器開啟該網址，然後「加入主畫面」

### 方法二：本機測試（需要 Node.js）

```bash
npx serve .
```
開啟 `http://localhost:3000`

### 方法三：Python 本機伺服器

```bash
python3 -m http.server 8080
```
開啟 `http://localhost:8080`

---

## 安裝到手機

**iPhone / iPad：**
Safari → 分享按鈕 → 加入主畫面

**Android：**
Chrome → 右上角選單 → 安裝應用程式

## 安裝到電腦

**Chrome / Edge：**
網址列右側會出現安裝圖示 ⊕，點擊即可

---

## 功能

- 全螢幕黑色打字環境
- 自動儲存（本地，不上傳任何資料）
- 字數統計
- 離線可用
- 支援手機、平板、桌面

---

檔案結構：
```
focus-writer/
├── index.html      ← 主頁面
├── manifest.json   ← PWA 設定
├── sw.js           ← 離線快取
├── icons/
│   ├── icon-192.png
│   └── icon-512.png
└── README.md
```
