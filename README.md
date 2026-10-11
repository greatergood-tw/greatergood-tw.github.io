# Greatergood Official Website

靜態網站，透過 GitHub Pages 部署於 https://www.greatergood.com.tw 。

## Tailwind CSS (v4)

修改 `index.html` 的 class 後，需重新編譯並 commit `static/css/output.css`：

```bash
npm install
npm run build   # 輸出壓縮後的 static/css/output.css
npm run watch   # 開發時自動重新編譯
```

v4 會自動掃描專案內的檔案，不需要 `tailwind.config.js`。
