# 畫面截圖(README 用)

這個資料夾專門放 README 裡引用的 demo 圖片。**不要放到 `public/`**——`public/` 的東西會被 Next.js 當成靜態資源一起部署上線,截圖只是文件用途,沒必要讓使用者下載得到。

## 檔名約定

根目錄 README 目前引用下面這幾張,直接用這些檔名存進來就會自動顯示:

| 檔名              | 內容                                   |
| ----------------- | -------------------------------------- |
| `home.png`        | `/` landing 首頁                       |
| `map.png`         | `/map` 海況地圖(台灣 SVG 海圖 + 25 區) |
| `map-detail.png`  | `/map` 選取某一區的詳情面板 + 12h 走勢圖 |
| `about.png`       | `/about` 關於 / 聯絡 / roadmap         |
| `demo.png`        | `/demo` 五種資料狀態展示               |

## 規格

- 格式:PNG(截圖)或 GIF(操作錄影)
- 寬度:1440px 左右,GitHub 會自動縮放
- 單檔大小:盡量壓在 1MB 以內,整個 repo 才不會肥起來(壓縮可用 [squoosh.app](https://squoosh.app))
- 深色/淺色:全站只有一套配色,截一種就好

## 加新圖

1. 把檔案丟進這個資料夾
2. 在根目錄 `README.md` 的「畫面預覽」章節加一行:

```markdown
![說明文字](docs/screenshots/檔名.png)
```

路徑用相對路徑(`docs/screenshots/...`),GitHub 和本機 Markdown 預覽都讀得到。
